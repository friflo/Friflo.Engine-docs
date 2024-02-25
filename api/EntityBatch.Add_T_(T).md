#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[EntityBatch](EntityBatch.md#'Friflo.Engine.ECS.EntityBatch')

## EntityBatch.Add<T>(T) Method

Adds an add component command to the [EntityBatch](EntityBatch.md#'Friflo.Engine.ECS.EntityBatch') with the given [component](EntityBatch.Add_T_(T).md#Friflo.Engine.ECS.EntityBatch.Add_T_(T).component#'Friflo.Engine.ECS.EntityBatch.Add<T>(T).component').

```csharp
public Friflo.Engine.ECS.EntityBatch Add<T>(in T component)
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityBatch.Add_T_(T).T'></a>

`T`
#### Parameters

<a name='Friflo.Engine.ECS.EntityBatch.Add_T_(T).component'></a>

`component` [T](EntityBatch.Add_T_(T).md#Friflo.Engine.ECS.EntityBatch.Add_T_(T).T#'Friflo.Engine.ECS.EntityBatch.Add<T>(T).T')

#### Returns
[EntityBatch](EntityBatch.md#'Friflo.Engine.ECS.EntityBatch')