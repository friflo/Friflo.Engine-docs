# ![logo](docs/images/Json-Fliox.svg)   **Friflo.Engine.ECS API Reference**![SPLASH](docs/images/paint-splatter.svg)


This project contains the C# API reference of [**Friflo Engine ECS - GitHub**](https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md).    

Full API reference list: [Friflo.Engine.ECS - API](api/Friflo.Engine.ECS.md)

Common used structs and classes.

| Type                                          |           | Description
| --------------------------------------------- | --------- | -----------------------------
| [EntityStore](api/EntityStore.md)             | class     | Container of entities. Typically called `World` in other implementations.
| [Entity](api/Entity.md)                       | struct    | An object in an EntityStore. Contains components, tags, scripts and child entities.
|                                               |           |
| [IComponent](api/IComponent.md)               | interface | Attribute structs as component types.
| [ITag](api/ITag.md)                           | interface | Attribute structs as tags.
| [Script](api/Script.md)                       | class     | Base class of scripts that can be added to entities.
|                                               |           |
| [ArchetypeQuery](api/ArchetypeQuery.md)       | class     | Used to return components and entities matching the assigned query filter.
| [QueryJob](api/QueryJob.md)                   | class     | Enables parallel query execution.
| [ParallelJobRunner](api/ParallelJobRunner.md) | class     | Required for parallel (multi threaded) query execution.
| [CommandBuffer](api/CommandBuffer.md)         | class     | Record entity changes on arbitrary threads and Playback() them on the main thread.
|                                               |           |
| [EventFilter](api/EventFilter.md)             | class     | Used to filter structural changes made to entities like added/removed components/tags.
| [EventRecorder](api/EventRecorder.md)         | class     | Record entity changes like adding/removing commands/tags. Required for EventFilter's.
|                                               |           |
| [EntityBatch](api/EntityBatch.md)             | class     | Used to optimize adding/removing components/tags to entities via a fluent API.
| [CreateEntityBatch](api/CreateEntityBatch.md) | class     | Used to optimize entity creation via a fluent API.


## Hello World

The hello world examples demonstrates the creation of some entities  
and their movement using a simple `ForEachEntity()` call.  

Much more examples at [Friflo.Engine.ECS · Examples](https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md#examples)

```csharp
public struct Velocity : IComponent { public Vector3 value; }

public static void HelloWorld()
{
    var store = new EntityStore();
    for (int n = 0; n < 10; n++) {
        store.Batch()
            .Add(new Position(n, 0, 0))
            .Add(new Velocity{ value = new Vector3(0, n, 0) })
            .Add(new EntityName("hello entity"))
            .CreateEntity();
    }
    var query = store.Query<Position, Velocity>();
    query.ForEachEntity((ref Position position, ref Velocity velocity, Entity entity) => {
        position.value += velocity.value;
    });
}
```

