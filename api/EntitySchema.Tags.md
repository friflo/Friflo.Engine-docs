#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntitySchema](EntitySchema.md 'Friflo.Engine.ECS.EntitySchema')

## EntitySchema.Tags Property

return all <b>Tag</b> types - structs implementing [ITag](ITag.md 'Friflo.Engine.ECS.ITag')

```csharp
public System.ReadOnlySpan<Friflo.Engine.ECS.TagType> Tags { get; }
```

#### Property Value
[System.ReadOnlySpan&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.ReadOnlySpan-1 'System.ReadOnlySpan`1')[TagType](TagType.md 'Friflo.Engine.ECS.TagType')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.ReadOnlySpan-1 'System.ReadOnlySpan`1')

### Remarks
[TagIndex](TagType.TagIndex.md 'Friflo.Engine.ECS.TagType.TagIndex') is equal to the array index<br/>[Tags](EntitySchema.Tags.md 'Friflo.Engine.ECS.EntitySchema.Tags')[0] is always null