#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[CreateEntityBatch](CreateEntityBatch.md 'Friflo.Engine.ECS.CreateEntityBatch')

## CreateEntityBatch.Add<T>(T) Method

Add the given [component](CreateEntityBatch.Add_T_(T).md#Friflo.Engine.ECS.CreateEntityBatch.Add_T_(T).component 'Friflo.Engine.ECS.CreateEntityBatch.Add<T>(T).component') that will be added to the entity when calling [CreateEntity()](CreateEntityBatch.CreateEntity().md 'Friflo.Engine.ECS.CreateEntityBatch.CreateEntity()').

```csharp
public Friflo.Engine.ECS.CreateEntityBatch Add<T>(in T component)
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.CreateEntityBatch.Add_T_(T).T'></a>

`T`
#### Parameters

<a name='Friflo.Engine.ECS.CreateEntityBatch.Add_T_(T).component'></a>

`component` [T](CreateEntityBatch.Add_T_(T).md#Friflo.Engine.ECS.CreateEntityBatch.Add_T_(T).T 'Friflo.Engine.ECS.CreateEntityBatch.Add<T>(T).T')

#### Returns
[CreateEntityBatch](CreateEntityBatch.md 'Friflo.Engine.ECS.CreateEntityBatch')