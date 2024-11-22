#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## Signature<T1,T2,T3> Struct

A Signature to create a query using [Query&lt;T1,T2,T3&gt;(Signature&lt;T1,T2,T3&gt;)](EntityStoreBase.Query_T1,T2,T3_(Signature_T1,T2,T3_).md 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3>(Friflo.Engine.ECS.Signature<T1,T2,T3>)') with three components.

```csharp
public readonly struct Signature<T1,T2,T3>
    where T1 : struct, System.ValueType, System.ValueType
    where T2 : struct, System.ValueType, System.ValueType
    where T3 : struct, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.Signature_T1,T2,T3_.T1'></a>

`T1`

<a name='Friflo.Engine.ECS.Signature_T1,T2,T3_.T2'></a>

`T2`

<a name='Friflo.Engine.ECS.Signature_T1,T2,T3_.T3'></a>

`T3`

| Properties | |
| :--- | :--- |
| [ComponentCount](Signature_T1,T2,T3_.ComponentCount.md 'Friflo.Engine.ECS.Signature<T1,T2,T3>.ComponentCount') | Gets the number component types of the query signature. |
| [ComponentTypes](Signature_T1,T2,T3_.ComponentTypes.md 'Friflo.Engine.ECS.Signature<T1,T2,T3>.ComponentTypes') | Return the component types of the query signature. |

| Methods | |
| :--- | :--- |
| [ToString()](Signature_T1,T2,T3_.ToString().md 'Friflo.Engine.ECS.Signature<T1,T2,T3>.ToString()') | |
