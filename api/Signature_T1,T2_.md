#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## Signature<T1,T2> Struct

A Signature to create a query using [Query&lt;T1,T2&gt;(Signature&lt;T1,T2&gt;)](EntityStoreBase.Query_T1,T2_(Signature_T1,T2_).md 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2>(Friflo.Engine.ECS.Signature<T1,T2>)') with two components.

```csharp
public readonly struct Signature<T1,T2>
    where T1 : struct, System.ValueType, System.ValueType
    where T2 : struct, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.Signature_T1,T2_.T1'></a>

`T1`

<a name='Friflo.Engine.ECS.Signature_T1,T2_.T2'></a>

`T2`

| Properties | |
| :--- | :--- |
| [ComponentCount](Signature_T1,T2_.ComponentCount.md 'Friflo.Engine.ECS.Signature<T1,T2>.ComponentCount') | Gets the number component types of the query signature. |
| [ComponentTypes](Signature_T1,T2_.ComponentTypes.md 'Friflo.Engine.ECS.Signature<T1,T2>.ComponentTypes') | Return the component types of the query signature. |

| Methods | |
| :--- | :--- |
| [ToString()](Signature_T1,T2_.ToString().md 'Friflo.Engine.ECS.Signature<T1,T2>.ToString()') | |
