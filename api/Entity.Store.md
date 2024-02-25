#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[Entity](Entity.md#'Friflo.Engine.ECS.Entity')

## Entity.Store Property

Returns the [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore') that contains the entity.

```csharp
public Friflo.Engine.ECS.EntityStore Store { get; }
```

#### Property Value
[EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore')

### Remarks
The [Store](Entity.Store.md#'Friflo.Engine.ECS.Entity.Store') the entity is [attached](StoreOwnership.md#Friflo.Engine.ECS.StoreOwnership.attached#'Friflo.Engine.ECS.StoreOwnership.attached') to. Returns null if [detached](StoreOwnership.md#Friflo.Engine.ECS.StoreOwnership.detached#'Friflo.Engine.ECS.StoreOwnership.detached')