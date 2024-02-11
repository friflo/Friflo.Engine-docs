#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStoreBase](EntityStoreBase.md 'Friflo.Engine.ECS.EntityStoreBase')

## EntityStoreBase.Query<T1,T2>(Signature<T1,T2>) Method

Create a reusable [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') for given component [signature](EntityStoreBase.Query_T1,T2_(Signature_T1,T2_).md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2_(Friflo.Engine.ECS.Signature_T1,T2_).signature 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2>(Friflo.Engine.ECS.Signature<T1,T2>).signature').

```csharp
public Friflo.Engine.ECS.ArchetypeQuery<T1,T2> Query<T1,T2>(in Friflo.Engine.ECS.Signature<T1,T2> signature)
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2_(Friflo.Engine.ECS.Signature_T1,T2_).T1'></a>

`T1`

<a name='Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2_(Friflo.Engine.ECS.Signature_T1,T2_).T2'></a>

`T2`
#### Parameters

<a name='Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2_(Friflo.Engine.ECS.Signature_T1,T2_).signature'></a>

`signature` [Friflo.Engine.ECS.Signature&lt;](Signature_T1,T2_.md 'Friflo.Engine.ECS.Signature<T1,T2>')[T1](EntityStoreBase.Query_T1,T2_(Signature_T1,T2_).md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2_(Friflo.Engine.ECS.Signature_T1,T2_).T1 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2>(Friflo.Engine.ECS.Signature<T1,T2>).T1')[,](Signature_T1,T2_.md 'Friflo.Engine.ECS.Signature<T1,T2>')[T2](EntityStoreBase.Query_T1,T2_(Signature_T1,T2_).md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2_(Friflo.Engine.ECS.Signature_T1,T2_).T2 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2>(Friflo.Engine.ECS.Signature<T1,T2>).T2')[&gt;](Signature_T1,T2_.md 'Friflo.Engine.ECS.Signature<T1,T2>')

#### Returns
[Friflo.Engine.ECS.ArchetypeQuery&lt;](ArchetypeQuery_T1,T2_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>')[T1](EntityStoreBase.Query_T1,T2_(Signature_T1,T2_).md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2_(Friflo.Engine.ECS.Signature_T1,T2_).T1 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2>(Friflo.Engine.ECS.Signature<T1,T2>).T1')[,](ArchetypeQuery_T1,T2_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>')[T2](EntityStoreBase.Query_T1,T2_(Signature_T1,T2_).md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2_(Friflo.Engine.ECS.Signature_T1,T2_).T2 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2>(Friflo.Engine.ECS.Signature<T1,T2>).T2')[&gt;](ArchetypeQuery_T1,T2_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>')