#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[CreateEntityBatch](CreateEntityBatch.md 'Friflo.Engine.ECS.CreateEntityBatch')

## CreateEntityBatch.AddTag<T>() Method

Add a tag that will be added to the entity when calling [CreateEntity()](CreateEntityBatch.CreateEntity().md 'Friflo.Engine.ECS.CreateEntityBatch.CreateEntity()').

```csharp
public Friflo.Engine.ECS.CreateEntityBatch AddTag<T>()
    where T : struct, Friflo.Engine.ECS.ITag, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.CreateEntityBatch.AddTag_T_().T'></a>

`T`

#### Returns
[CreateEntityBatch](CreateEntityBatch.md 'Friflo.Engine.ECS.CreateEntityBatch')