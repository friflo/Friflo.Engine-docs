![logo](docs/images/friflo-ECS.svg)   ![SPLASH](docs/images/paint-splatter.svg)


[![Github Repo](https://img.shields.io/badge/Friflo.Engine.ECS-blue?logo=github&logoColor=white)](https://github.com/friflo/Friflo.Engine.ECS)
[![Wiki](https://img.shields.io/badge/Wiki-A200FF?logo=gitbook&logoColor=white)](https://friflo.gitbook.io/friflo.engine.ecs)
[![Demos](https://img.shields.io/badge/Demos-22aa22?logo=github&logoColor=white)](https://github.com/friflo/Friflo.Engine.ECS-Demos)

# **Friflo.Engine.ECS  ·  API Reference**


This project contains the C# API reference of [**Friflo Engine ECS - GitHub**](https://github.com/friflo/Friflo.Engine.ECS).    

| Namespace                                                             | Description                                                                                                                   |
| --------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| [Friflo.Engine.ECS](api/Friflo.Engine.ECS.md)                         | Contains types and methods to query, add, remove or change [Entity](api/Entity.md)'s in an [EntityStore](api/EntityStore.md). |
| [Friflo.Engine.ECS.Collections](api/Friflo.Engine.ECS.Collections.md) | Contains types to enable data binding for common .NET applications.                                                           |
| [Friflo.Engine.ECS.Index](api/Friflo.Engine.ECS.Index.md)             | Enables search for indexed component values in O(1) for types: string, int, enum, float, Guid, DateTime, .... <br/>Support efficient entity relationships like entity links (foreign keys) and back links (JOIN's).|
| [Friflo.Engine.ECS.Serialize](api/Friflo.Engine.ECS.Serialize.md)     | Contains types and methods to serialize / deserialize [Entity](api/Entity.md)'s as JSON.                                      |
| [Friflo.Engine.ECS.Systems](api/Friflo.Engine.ECS.Systems.md)         | Used to organize and execute a set of systems within a [SystemRoot](api/SystemRoot.md).                                       |
| [Friflo.Engine.ECS.Utils](api/Friflo.Engine.ECS.Utils.md)             | Utility types and methods typically used by generic libraries.                                                                |

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
|                                               |           |
| [EntitySerializer](api/EntitySerializer.md)   | class     | Enables serialization of entities to / from JSON.


## Hello World

The hello world examples demonstrates the creation of some entities  
and their movement using a simple `ForEachEntity()` call.  

Much more examples at [Friflo.Engine.ECS · Examples](https://github.com/friflo/Friflo.Engine.ECS#-examples)

```csharp
public struct Velocity : IComponent { public Vector3 value; }

public static void HelloWorld()
{
    var store = new EntityStore();
    for (int n = 0; n < 10; n++) {
        store.CreateEntity(new Position(n, 0, 0), new Velocity{ value = new Vector3(0, n, 0)});
    }
    var query = store.Query<Position, Velocity>();
    query.ForEachEntity((ref Position position, ref Velocity velocity, Entity entity) => {
        position.value += velocity.value;
    });
}
```

<a href="https://sdl-wasm-sample-web.vercel.app/docs/MonoGame/">
<img src="https://raw.githubusercontent.com/friflo/Friflo.Engine-docs/main/docs/images/MonoGame-wasm.png" width="600" height="405"/>
</a>

Interactive Browser Demo showing MonoGame WebAssembly integration. [Try out Demo](https://sdl-wasm-sample-web.vercel.app/docs/MonoGame/).  
*Note:* WebGL rendering performance cannot compete with Desktop build.