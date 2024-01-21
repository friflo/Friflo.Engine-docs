#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ChildEntitiesChanged Struct

Is the event for event handlers added to [OnChildEntitiesChanged](Entity.OnChildEntitiesChanged.md 'Friflo.Engine.ECS.Entity.OnChildEntitiesChanged') or [OnChildEntitiesChanged](EntityStore.OnChildEntitiesChanged.md 'Friflo.Engine.ECS.EntityStore.OnChildEntitiesChanged').

```csharp
public readonly struct ChildEntitiesChanged
```

### Remarks
These events are fired on:
- [AddChild(Entity)](Entity.AddChild(Entity).md 'Friflo.Engine.ECS.Entity.AddChild(Friflo.Engine.ECS.Entity)')
- [InsertChild(int, Entity)](Entity.InsertChild(int,Entity).md 'Friflo.Engine.ECS.Entity.InsertChild(int, Friflo.Engine.ECS.Entity)')
- [RemoveChild(Entity)](Entity.RemoveChild(Entity).md 'Friflo.Engine.ECS.Entity.RemoveChild(Friflo.Engine.ECS.Entity)')

| Fields | |
| :--- | :--- |
| [Action](ChildEntitiesChanged.Action.md 'Friflo.Engine.ECS.ChildEntitiesChanged.Action') | |
| [ChildId](ChildEntitiesChanged.ChildId.md 'Friflo.Engine.ECS.ChildEntitiesChanged.ChildId') | The `Id` of the added / removed child entity |
| [ChildIndex](ChildEntitiesChanged.ChildIndex.md 'Friflo.Engine.ECS.ChildEntitiesChanged.ChildIndex') | The child position of the added / removed child entity in the parent [Entity](ChildEntitiesChanged.Entity.md 'Friflo.Engine.ECS.ChildEntitiesChanged.Entity'). |
| [EntityId](ChildEntitiesChanged.EntityId.md 'Friflo.Engine.ECS.ChildEntitiesChanged.EntityId') | The `Id` of the [Entity](ChildEntitiesChanged.Entity.md 'Friflo.Engine.ECS.ChildEntitiesChanged.Entity') that emitted the event. |
| [Store](ChildEntitiesChanged.Store.md 'Friflo.Engine.ECS.ChildEntitiesChanged.Store') | The [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') containing the [Entity](ChildEntitiesChanged.Entity.md 'Friflo.Engine.ECS.ChildEntitiesChanged.Entity') that emitted the event. |

| Properties | |
| :--- | :--- |
| [Child](ChildEntitiesChanged.Child.md 'Friflo.Engine.ECS.ChildEntitiesChanged.Child') | The added / removed child entity |
| [Entity](ChildEntitiesChanged.Entity.md 'Friflo.Engine.ECS.ChildEntitiesChanged.Entity') | The [Entity](ChildEntitiesChanged.Entity.md 'Friflo.Engine.ECS.ChildEntitiesChanged.Entity') that emitted the event - aka the publisher |

| Methods | |
| :--- | :--- |
| [ToString()](ChildEntitiesChanged.ToString().md 'Friflo.Engine.ECS.ChildEntitiesChanged.ToString()') | |
