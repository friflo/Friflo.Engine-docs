#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.Archetype Property

Returns the [Archetype](Entity.Archetype.md 'Friflo.Engine.ECS.Entity.Archetype') that contains the entity.

```csharp
public Friflo.Engine.ECS.Archetype Archetype { get; }
```

#### Property Value
[Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype')

### Remarks
The [Archetype](Entity.Archetype.md 'Friflo.Engine.ECS.Entity.Archetype') the entity is stored.<br/>Return null if the entity is [detached](StoreOwnership.md#Friflo.Engine.ECS.StoreOwnership.detached 'Friflo.Engine.ECS.StoreOwnership.detached')