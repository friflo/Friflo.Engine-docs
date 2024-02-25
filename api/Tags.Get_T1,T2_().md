#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[Tags](Tags.md#'Friflo.Engine.ECS.Tags')

## Tags.Get<T1,T2>() Method

Create an instance containing the given [ITag](ITag.md#'Friflo.Engine.ECS.ITag') types
[T1](Tags.Get_T1,T2_().md#Friflo.Engine.ECS.Tags.Get_T1,T2_().T1#'Friflo.Engine.ECS.Tags.Get<T1,T2>().T1') and [T2](Tags.Get_T1,T2_().md#Friflo.Engine.ECS.Tags.Get_T1,T2_().T2#'Friflo.Engine.ECS.Tags.Get<T1,T2>().T2').

```csharp
public static Friflo.Engine.ECS.Tags Get<T1,T2>()
    where T1 : struct, Friflo.Engine.ECS.ITag, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.ITag, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Tags.Get_T1,T2_().T1'></a>

`T1`

<a name='Friflo.Engine.ECS.Tags.Get_T1,T2_().T2'></a>

`T2`

#### Returns
[Tags](Tags.md#'Friflo.Engine.ECS.Tags')