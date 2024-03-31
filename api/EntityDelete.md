#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## EntityDelete Struct

Is the event for event handlers added to [OnEntityDelete](EntityStore.OnEntityDelete.md 'Friflo.Engine.ECS.EntityStore.OnEntityDelete').

```csharp
public readonly struct EntityDelete
```

### Remarks
These events are fired on [DeleteEntity()](Entity.DeleteEntity().md 'Friflo.Engine.ECS.Entity.DeleteEntity()').

| Fields | |
| :--- | :--- |
| [Entity](EntityDelete.Entity.md 'Friflo.Engine.ECS.EntityDelete.Entity') | The entity that will be deleted. |

| Properties | |
| :--- | :--- |
| [Store](EntityDelete.Store.md 'Friflo.Engine.ECS.EntityDelete.Store') | The [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') of the entity that will be deleted. |

| Methods | |
| :--- | :--- |
| [ToString()](EntityDelete.ToString().md 'Friflo.Engine.ECS.EntityDelete.ToString()') | |
