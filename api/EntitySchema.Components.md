#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntitySchema](EntitySchema.md 'Friflo.Engine.ECS.EntitySchema')

## EntitySchema.Components Property

return all <b>component</b> types - structs implementing [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')

```csharp
public System.ReadOnlySpan<Friflo.Engine.ECS.ComponentType> Components { get; }
```

#### Property Value
[System.ReadOnlySpan&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.ReadOnlySpan-1 'System.ReadOnlySpan`1')[ComponentType](ComponentType.md 'Friflo.Engine.ECS.ComponentType')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.ReadOnlySpan-1 'System.ReadOnlySpan`1')

### Remarks
[StructIndex](ComponentType.StructIndex.md 'Friflo.Engine.ECS.ComponentType.StructIndex') is equal to the array index<br/>[Components](EntitySchema.Components.md 'Friflo.Engine.ECS.EntitySchema.Components')[0] is always null