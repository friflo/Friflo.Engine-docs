#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[CreateEntityBatch](CreateEntityBatch.md#'Friflo.Engine.ECS.CreateEntityBatch')

## CreateEntityBatch.Get<T>() Method

Get a component by reference previously added to the batch.<br/>
This enables creation of multiple entities using the same batch.

```csharp
public ref T Get<T>()
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.CreateEntityBatch.Get_T_().T'></a>

`T`

#### Returns
[T](CreateEntityBatch.Get_T_().md#Friflo.Engine.ECS.CreateEntityBatch.Get_T_().T#'Friflo.Engine.ECS.CreateEntityBatch.Get<T>().T')