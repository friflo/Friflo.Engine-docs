#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntitySchema](EntitySchema.md 'Friflo.Engine.ECS.EntitySchema')

## EntitySchema.GetTagType<T>() Method

Return the [TagType](TagType.md 'Friflo.Engine.ECS.TagType') of a struct implementing [ITag](ITag.md 'Friflo.Engine.ECS.ITag').

```csharp
public Friflo.Engine.ECS.TagType GetTagType<T>()
    where T : struct, Friflo.Engine.ECS.ITag, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntitySchema.GetTagType_T_().T'></a>

`T`

#### Returns
[TagType](TagType.md 'Friflo.Engine.ECS.TagType')