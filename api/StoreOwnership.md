#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS')

## StoreOwnership Enum

Describe the ownership state of an [Entity](Entity.md#'Friflo.Engine.ECS.Entity')

```csharp
public enum StoreOwnership
```
### Fields

<a name='Friflo.Engine.ECS.StoreOwnership.attached'></a>

`attached` 1

The entity is owned by an [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore').

### Remarks
Entities created with [CreateEntity()](EntityStore.CreateEntity().md#'Friflo.Engine.ECS.EntityStore.CreateEntity()') are automatically [attached](StoreOwnership.md#Friflo.Engine.ECS.StoreOwnership.attached#'Friflo.Engine.ECS.StoreOwnership.attached') to its [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore')<br/>

<a name='Friflo.Engine.ECS.StoreOwnership.detached'></a>

`detached` 0

The entity is not owned by an [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore').

### Remarks
When calling [DeleteEntity()](Entity.DeleteEntity().md#'Friflo.Engine.ECS.Entity.DeleteEntity()') its state changes to [detached](StoreOwnership.md#Friflo.Engine.ECS.StoreOwnership.detached#'Friflo.Engine.ECS.StoreOwnership.detached').<br/>