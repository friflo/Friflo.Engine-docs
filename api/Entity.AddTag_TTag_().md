#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.AddTag<TTag>() Method

Add the given [TTag](Entity.AddTag_TTag_().md#Friflo.Engine.ECS.Entity.AddTag_TTag_().TTag 'Friflo.Engine.ECS.Entity.AddTag<TTag>().TTag') to the entity.

```csharp
public bool AddTag<TTag>()
    where TTag : struct, Friflo.Engine.ECS.ITag, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Entity.AddTag_TTag_().TTag'></a>

`TTag`

#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')