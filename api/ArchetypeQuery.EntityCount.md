#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery')

## ArchetypeQuery.EntityCount Property

Return the number of entities matching the query.

```csharp
public int EntityCount { get; }
```

#### Property Value
[System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

### Remarks
Execution time O(matching [Archetypes](ArchetypeQuery.Archetypes.md 'Friflo.Engine.ECS.ArchetypeQuery.Archetypes')).<br/>
Typically there are only a few matching [Archetypes](ArchetypeQuery.Archetypes.md 'Friflo.Engine.ECS.ArchetypeQuery.Archetypes').