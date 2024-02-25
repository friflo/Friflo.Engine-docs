#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[EntitySchema](EntitySchema.md#'Friflo.Engine.ECS.EntitySchema')

## EntitySchema.GetComponentType<T>() Method

Return the [ComponentType](ComponentType.md#'Friflo.Engine.ECS.ComponentType') of a struct implementing [IComponent](IComponent.md#'Friflo.Engine.ECS.IComponent').

```csharp
public Friflo.Engine.ECS.ComponentType GetComponentType<T>()
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntitySchema.GetComponentType_T_().T'></a>

`T`

#### Returns
[ComponentType](ComponentType.md#'Friflo.Engine.ECS.ComponentType')