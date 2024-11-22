#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[ArchetypeUtils](ArchetypeUtils.md 'Friflo.Engine.ECS.ArchetypeUtils')

## ArchetypeUtils.MinCapacity Field

Minimum: 64 see [Friflo.Engine.ECS.ArchetypeUtils.MaxComponentMultiple](https://docs.microsoft.com/en-us/dotnet/api/Friflo.Engine.ECS.ArchetypeUtils.MaxComponentMultiple 'Friflo.Engine.ECS.ArchetypeUtils.MaxComponentMultiple') to support padding for vectorization.

```csharp
public const int MinCapacity = 512;
```

#### Field Value
[System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

### Remarks
Could be less than 64 if using [Friflo.Engine.ECS.StructPadding&lt;&gt;.ByteSize](https://docs.microsoft.com/en-us/dotnet/api/Friflo.Engine.ECS.StructPadding-1.ByteSize 'Friflo.Engine.ECS.StructPadding`1.ByteSize') for [Friflo.Engine.ECS.StructHeap&lt;&gt;.components](https://docs.microsoft.com/en-us/dotnet/api/Friflo.Engine.ECS.StructHeap-1.components 'Friflo.Engine.ECS.StructHeap`1.components')