#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS')

## TreeMembership Enum

Describe the membership of an [Entity](Entity.md#'Friflo.Engine.ECS.Entity') to the [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore') tree graph.

```csharp
public enum TreeMembership
```
### Fields

<a name='Friflo.Engine.ECS.TreeMembership.floating'></a>

`floating` 0

The entity is not member of the [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore') tree graph.

<a name='Friflo.Engine.ECS.TreeMembership.treeNode'></a>

`treeNode` 1

The entity is member of the [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore') tree graph.

### Remarks
Requirement: The entity must be [attached](StoreOwnership.md#Friflo.Engine.ECS.StoreOwnership.attached#'Friflo.Engine.ECS.StoreOwnership.attached') to an [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore')