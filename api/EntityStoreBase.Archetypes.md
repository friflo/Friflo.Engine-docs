#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStoreBase](EntityStoreBase.md 'Friflo.Engine.ECS.EntityStoreBase')

## EntityStoreBase.Archetypes Property

Array of [Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype')'s utilized by the entity store

```csharp
public System.ReadOnlySpan<Friflo.Engine.ECS.Archetype> Archetypes { get; }
```

#### Property Value
[System.ReadOnlySpan&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.ReadOnlySpan-1 'System.ReadOnlySpan`1')[Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.ReadOnlySpan-1 'System.ReadOnlySpan`1')

### Remarks
Each [Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype') contains all entities of a specific combination of <b>struct</b> components.