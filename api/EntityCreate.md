#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## EntityCreate Struct

Is the event for event handlers added to [OnEntityCreate](EntityStore.OnEntityCreate.md 'Friflo.Engine.ECS.EntityStore.OnEntityCreate').

```csharp
public readonly struct EntityCreate
```

### Remarks
These events are fired on [CreateEntity()](EntityStore.CreateEntity().md 'Friflo.Engine.ECS.EntityStore.CreateEntity()').

| Fields | |
| :--- | :--- |
| [Entity](EntityCreate.Entity.md 'Friflo.Engine.ECS.EntityCreate.Entity') | The created [Entity](Entity.md 'Friflo.Engine.ECS.Entity'). |

| Properties | |
| :--- | :--- |
| [Store](EntityCreate.Store.md 'Friflo.Engine.ECS.EntityCreate.Store') | The [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') containing the created entity. |

| Methods | |
| :--- | :--- |
| [ToString()](EntityCreate.ToString().md 'Friflo.Engine.ECS.EntityCreate.ToString()') | |
