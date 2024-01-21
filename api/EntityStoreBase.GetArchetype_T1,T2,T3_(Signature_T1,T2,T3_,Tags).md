#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStoreBase](EntityStoreBase.md 'Friflo.Engine.ECS.EntityStoreBase')

## EntityStoreBase.GetArchetype<T1,T2,T3>(Signature<T1,T2,T3>, Tags) Method

```csharp
public Friflo.Engine.ECS.Archetype GetArchetype<T1,T2,T3>(in Friflo.Engine.ECS.Signature<T1,T2,T3> signature, in Friflo.Engine.ECS.Tags tags=default(Friflo.Engine.ECS.Tags))
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityStoreBase.GetArchetype_T1,T2,T3_(Friflo.Engine.ECS.Signature_T1,T2,T3_,Friflo.Engine.ECS.Tags).T1'></a>

`T1`

<a name='Friflo.Engine.ECS.EntityStoreBase.GetArchetype_T1,T2,T3_(Friflo.Engine.ECS.Signature_T1,T2,T3_,Friflo.Engine.ECS.Tags).T2'></a>

`T2`

<a name='Friflo.Engine.ECS.EntityStoreBase.GetArchetype_T1,T2,T3_(Friflo.Engine.ECS.Signature_T1,T2,T3_,Friflo.Engine.ECS.Tags).T3'></a>

`T3`
#### Parameters

<a name='Friflo.Engine.ECS.EntityStoreBase.GetArchetype_T1,T2,T3_(Friflo.Engine.ECS.Signature_T1,T2,T3_,Friflo.Engine.ECS.Tags).signature'></a>

`signature` [Friflo.Engine.ECS.Signature&lt;](Signature_T1,T2,T3_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3>')[T1](EntityStoreBase.GetArchetype_T1,T2,T3_(Signature_T1,T2,T3_,Tags).md#Friflo.Engine.ECS.EntityStoreBase.GetArchetype_T1,T2,T3_(Friflo.Engine.ECS.Signature_T1,T2,T3_,Friflo.Engine.ECS.Tags).T1 'Friflo.Engine.ECS.EntityStoreBase.GetArchetype<T1,T2,T3>(Friflo.Engine.ECS.Signature<T1,T2,T3>, Friflo.Engine.ECS.Tags).T1')[,](Signature_T1,T2,T3_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3>')[T2](EntityStoreBase.GetArchetype_T1,T2,T3_(Signature_T1,T2,T3_,Tags).md#Friflo.Engine.ECS.EntityStoreBase.GetArchetype_T1,T2,T3_(Friflo.Engine.ECS.Signature_T1,T2,T3_,Friflo.Engine.ECS.Tags).T2 'Friflo.Engine.ECS.EntityStoreBase.GetArchetype<T1,T2,T3>(Friflo.Engine.ECS.Signature<T1,T2,T3>, Friflo.Engine.ECS.Tags).T2')[,](Signature_T1,T2,T3_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3>')[T3](EntityStoreBase.GetArchetype_T1,T2,T3_(Signature_T1,T2,T3_,Tags).md#Friflo.Engine.ECS.EntityStoreBase.GetArchetype_T1,T2,T3_(Friflo.Engine.ECS.Signature_T1,T2,T3_,Friflo.Engine.ECS.Tags).T3 'Friflo.Engine.ECS.EntityStoreBase.GetArchetype<T1,T2,T3>(Friflo.Engine.ECS.Signature<T1,T2,T3>, Friflo.Engine.ECS.Tags).T3')[&gt;](Signature_T1,T2,T3_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3>')

<a name='Friflo.Engine.ECS.EntityStoreBase.GetArchetype_T1,T2,T3_(Friflo.Engine.ECS.Signature_T1,T2,T3_,Friflo.Engine.ECS.Tags).tags'></a>

`tags` [Tags](Tags.md 'Friflo.Engine.ECS.Tags')

#### Returns
[Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype')