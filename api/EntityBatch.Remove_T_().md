#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[EntityBatch](EntityBatch.md#'Friflo.Engine.ECS.EntityBatch')

## EntityBatch.Remove<T>() Method

Adds a remove component command to the [EntityBatch](EntityBatch.md#'Friflo.Engine.ECS.EntityBatch').

```csharp
public Friflo.Engine.ECS.EntityBatch Remove<T>()
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityBatch.Remove_T_().T'></a>

`T`

#### Returns
[EntityBatch](EntityBatch.md#'Friflo.Engine.ECS.EntityBatch')