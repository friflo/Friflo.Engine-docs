#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStoreBase](EntityStoreBase.md 'Friflo.Engine.ECS.EntityStoreBase')

## EntityStoreBase.Query<T1,T2,T3>(Signature<T1,T2,T3>) Method

Create a reusable [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') for given component [signature](EntityStoreBase.Query_T1,T2,T3_(Signature_T1,T2,T3_).md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3_(Friflo.Engine.ECS.Signature_T1,T2,T3_).signature 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3>(Friflo.Engine.ECS.Signature<T1,T2,T3>).signature').

```csharp
public Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3> Query<T1,T2,T3>(in Friflo.Engine.ECS.Signature<T1,T2,T3> signature)
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3_(Friflo.Engine.ECS.Signature_T1,T2,T3_).T1'></a>

`T1`

<a name='Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3_(Friflo.Engine.ECS.Signature_T1,T2,T3_).T2'></a>

`T2`

<a name='Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3_(Friflo.Engine.ECS.Signature_T1,T2,T3_).T3'></a>

`T3`
#### Parameters

<a name='Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3_(Friflo.Engine.ECS.Signature_T1,T2,T3_).signature'></a>

`signature` [Friflo.Engine.ECS.Signature&lt;](Signature_T1,T2,T3_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3>')[T1](EntityStoreBase.Query_T1,T2,T3_(Signature_T1,T2,T3_).md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3_(Friflo.Engine.ECS.Signature_T1,T2,T3_).T1 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3>(Friflo.Engine.ECS.Signature<T1,T2,T3>).T1')[,](Signature_T1,T2,T3_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3>')[T2](EntityStoreBase.Query_T1,T2,T3_(Signature_T1,T2,T3_).md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3_(Friflo.Engine.ECS.Signature_T1,T2,T3_).T2 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3>(Friflo.Engine.ECS.Signature<T1,T2,T3>).T2')[,](Signature_T1,T2,T3_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3>')[T3](EntityStoreBase.Query_T1,T2,T3_(Signature_T1,T2,T3_).md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3_(Friflo.Engine.ECS.Signature_T1,T2,T3_).T3 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3>(Friflo.Engine.ECS.Signature<T1,T2,T3>).T3')[&gt;](Signature_T1,T2,T3_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3>')

#### Returns
[Friflo.Engine.ECS.ArchetypeQuery&lt;](ArchetypeQuery_T1,T2,T3_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>')[T1](EntityStoreBase.Query_T1,T2,T3_(Signature_T1,T2,T3_).md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3_(Friflo.Engine.ECS.Signature_T1,T2,T3_).T1 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3>(Friflo.Engine.ECS.Signature<T1,T2,T3>).T1')[,](ArchetypeQuery_T1,T2,T3_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>')[T2](EntityStoreBase.Query_T1,T2,T3_(Signature_T1,T2,T3_).md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3_(Friflo.Engine.ECS.Signature_T1,T2,T3_).T2 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3>(Friflo.Engine.ECS.Signature<T1,T2,T3>).T2')[,](ArchetypeQuery_T1,T2,T3_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>')[T3](EntityStoreBase.Query_T1,T2,T3_(Signature_T1,T2,T3_).md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3_(Friflo.Engine.ECS.Signature_T1,T2,T3_).T3 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3>(Friflo.Engine.ECS.Signature<T1,T2,T3>).T3')[&gt;](ArchetypeQuery_T1,T2,T3_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>')