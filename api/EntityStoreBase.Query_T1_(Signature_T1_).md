#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[EntityStoreBase](EntityStoreBase.md#'Friflo.Engine.ECS.EntityStoreBase')

## EntityStoreBase.Query<T1>(Signature<T1>) Method

Create a reusable [ArchetypeQuery](ArchetypeQuery.md#'Friflo.Engine.ECS.ArchetypeQuery') for given component [signature](EntityStoreBase.Query_T1_(Signature_T1_).md#Friflo.Engine.ECS.EntityStoreBase.Query_T1_(Friflo.Engine.ECS.Signature_T1_).signature#'Friflo.Engine.ECS.EntityStoreBase.Query<T1>(Friflo.Engine.ECS.Signature<T1>).signature').

```csharp
public Friflo.Engine.ECS.ArchetypeQuery<T1> Query<T1>(in Friflo.Engine.ECS.Signature<T1> signature)
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityStoreBase.Query_T1_(Friflo.Engine.ECS.Signature_T1_).T1'></a>

`T1`
#### Parameters

<a name='Friflo.Engine.ECS.EntityStoreBase.Query_T1_(Friflo.Engine.ECS.Signature_T1_).signature'></a>

`signature` [Friflo.Engine.ECS.Signature&lt;](Signature_T1_.md#'Friflo.Engine.ECS.Signature<T1>')[T1](EntityStoreBase.Query_T1_(Signature_T1_).md#Friflo.Engine.ECS.EntityStoreBase.Query_T1_(Friflo.Engine.ECS.Signature_T1_).T1#'Friflo.Engine.ECS.EntityStoreBase.Query<T1>(Friflo.Engine.ECS.Signature<T1>).T1')[&gt;](Signature_T1_.md#'Friflo.Engine.ECS.Signature<T1>')

#### Returns
[Friflo.Engine.ECS.ArchetypeQuery&lt;](ArchetypeQuery_T1_.md#'Friflo.Engine.ECS.ArchetypeQuery<T1>')[T1](EntityStoreBase.Query_T1_(Signature_T1_).md#Friflo.Engine.ECS.EntityStoreBase.Query_T1_(Friflo.Engine.ECS.Signature_T1_).T1#'Friflo.Engine.ECS.EntityStoreBase.Query<T1>(Friflo.Engine.ECS.Signature<T1>).T1')[&gt;](ArchetypeQuery_T1_.md#'Friflo.Engine.ECS.ArchetypeQuery<T1>')