#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Tags](Tags.md 'Friflo.Engine.ECS.Tags')

## Tags.Get<T1,T2,T3>() Method

Create an instance containing the given [ITag](ITag.md 'Friflo.Engine.ECS.ITag') types
[T1](Tags.Get_T1,T2,T3_().md#Friflo.Engine.ECS.Tags.Get_T1,T2,T3_().T1 'Friflo.Engine.ECS.Tags.Get<T1,T2,T3>().T1'), [T2](Tags.Get_T1,T2,T3_().md#Friflo.Engine.ECS.Tags.Get_T1,T2,T3_().T2 'Friflo.Engine.ECS.Tags.Get<T1,T2,T3>().T2') and [T3](Tags.Get_T1,T2,T3_().md#Friflo.Engine.ECS.Tags.Get_T1,T2,T3_().T3 'Friflo.Engine.ECS.Tags.Get<T1,T2,T3>().T3').

```csharp
public static Friflo.Engine.ECS.Tags Get<T1,T2,T3>()
    where T1 : struct, Friflo.Engine.ECS.ITag, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.ITag, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.ITag, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Tags.Get_T1,T2,T3_().T1'></a>

`T1`

<a name='Friflo.Engine.ECS.Tags.Get_T1,T2,T3_().T2'></a>

`T2`

<a name='Friflo.Engine.ECS.Tags.Get_T1,T2,T3_().T3'></a>

`T3`

#### Returns
[Tags](Tags.md 'Friflo.Engine.ECS.Tags')