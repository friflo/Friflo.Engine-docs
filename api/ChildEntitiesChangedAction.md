#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ChildEntitiesChangedAction Enum

The modification type of an [ChildEntitiesChanged](ChildEntitiesChanged.md 'Friflo.Engine.ECS.ChildEntitiesChanged') event: [Add](ChildEntitiesChangedAction.md#Friflo.Engine.ECS.ChildEntitiesChangedAction.Add 'Friflo.Engine.ECS.ChildEntitiesChangedAction.Add') or [Remove](ChildEntitiesChangedAction.md#Friflo.Engine.ECS.ChildEntitiesChangedAction.Remove 'Friflo.Engine.ECS.ChildEntitiesChangedAction.Remove') entity.

```csharp
public enum ChildEntitiesChangedAction
```
### Fields

<a name='Friflo.Engine.ECS.ChildEntitiesChangedAction.Add'></a>

`Add` 0

An entity was added as a child to another [Entity](Entity.md 'Friflo.Engine.ECS.Entity').

<a name='Friflo.Engine.ECS.ChildEntitiesChangedAction.Remove'></a>

`Remove` 1

A child entity was removed from an [Entity](Entity.md 'Friflo.Engine.ECS.Entity').