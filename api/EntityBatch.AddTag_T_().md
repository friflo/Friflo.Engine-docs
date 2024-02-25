#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityBatch](EntityBatch.md 'Friflo.Engine.ECS.EntityBatch')

## EntityBatch.AddTag<T>() Method

Adds an add tag command to the [EntityBatch](EntityBatch.md 'Friflo.Engine.ECS.EntityBatch').

```csharp
public Friflo.Engine.ECS.EntityBatch AddTag<T>()
    where T : struct, Friflo.Engine.ECS.ITag, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityBatch.AddTag_T_().T'></a>

`T`

#### Returns
[EntityBatch](EntityBatch.md 'Friflo.Engine.ECS.EntityBatch')