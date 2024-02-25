#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[CreateEntityBatch](CreateEntityBatch.md#'Friflo.Engine.ECS.CreateEntityBatch')

## CreateEntityBatch.Add<T>() Method

Add a component that will be added to the entity when calling [CreateEntity()](CreateEntityBatch.CreateEntity().md#'Friflo.Engine.ECS.CreateEntityBatch.CreateEntity()').

```csharp
public Friflo.Engine.ECS.CreateEntityBatch Add<T>()
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.CreateEntityBatch.Add_T_().T'></a>

`T`

#### Returns
[CreateEntityBatch](CreateEntityBatch.md#'Friflo.Engine.ECS.CreateEntityBatch')