#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntitySchema](EntitySchema.md 'Friflo.Engine.ECS.EntitySchema')

## EntitySchema.Scripts Property

return all [Script](Script.md 'Friflo.Engine.ECS.Script') types - classes extending [Script](Script.md 'Friflo.Engine.ECS.Script')

```csharp
public System.ReadOnlySpan<Friflo.Engine.ECS.ScriptType> Scripts { get; }
```

#### Property Value
[System.ReadOnlySpan&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.ReadOnlySpan-1 'System.ReadOnlySpan`1')[ScriptType](ScriptType.md 'Friflo.Engine.ECS.ScriptType')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.ReadOnlySpan-1 'System.ReadOnlySpan`1')

### Remarks
[ScriptIndex](ScriptType.ScriptIndex.md 'Friflo.Engine.ECS.ScriptType.ScriptIndex') is equal to the array index<br/>[Scripts](EntitySchema.Scripts.md 'Friflo.Engine.ECS.EntitySchema.Scripts')[0] is always null