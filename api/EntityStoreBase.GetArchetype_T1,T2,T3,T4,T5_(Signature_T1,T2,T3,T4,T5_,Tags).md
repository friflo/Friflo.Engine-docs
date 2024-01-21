#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStoreBase](EntityStoreBase.md 'Friflo.Engine.ECS.EntityStoreBase')

## EntityStoreBase.GetArchetype<T1,T2,T3,T4,T5>(Signature<T1,T2,T3,T4,T5>, Tags) Method

```csharp
public Friflo.Engine.ECS.Archetype GetArchetype<T1,T2,T3,T4,T5>(in Friflo.Engine.ECS.Signature<T1,T2,T3,T4,T5> signature, in Friflo.Engine.ECS.Tags tags=default(Friflo.Engine.ECS.Tags))
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T4 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T5 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityStoreBase.GetArchetype_T1,T2,T3,T4,T5_(Friflo.Engine.ECS.Signature_T1,T2,T3,T4,T5_,Friflo.Engine.ECS.Tags).T1'></a>

`T1`

<a name='Friflo.Engine.ECS.EntityStoreBase.GetArchetype_T1,T2,T3,T4,T5_(Friflo.Engine.ECS.Signature_T1,T2,T3,T4,T5_,Friflo.Engine.ECS.Tags).T2'></a>

`T2`

<a name='Friflo.Engine.ECS.EntityStoreBase.GetArchetype_T1,T2,T3,T4,T5_(Friflo.Engine.ECS.Signature_T1,T2,T3,T4,T5_,Friflo.Engine.ECS.Tags).T3'></a>

`T3`

<a name='Friflo.Engine.ECS.EntityStoreBase.GetArchetype_T1,T2,T3,T4,T5_(Friflo.Engine.ECS.Signature_T1,T2,T3,T4,T5_,Friflo.Engine.ECS.Tags).T4'></a>

`T4`

<a name='Friflo.Engine.ECS.EntityStoreBase.GetArchetype_T1,T2,T3,T4,T5_(Friflo.Engine.ECS.Signature_T1,T2,T3,T4,T5_,Friflo.Engine.ECS.Tags).T5'></a>

`T5`
#### Parameters

<a name='Friflo.Engine.ECS.EntityStoreBase.GetArchetype_T1,T2,T3,T4,T5_(Friflo.Engine.ECS.Signature_T1,T2,T3,T4,T5_,Friflo.Engine.ECS.Tags).signature'></a>

`signature` [Friflo.Engine.ECS.Signature&lt;](Signature_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3,T4,T5>')[T1](EntityStoreBase.GetArchetype_T1,T2,T3,T4,T5_(Signature_T1,T2,T3,T4,T5_,Tags).md#Friflo.Engine.ECS.EntityStoreBase.GetArchetype_T1,T2,T3,T4,T5_(Friflo.Engine.ECS.Signature_T1,T2,T3,T4,T5_,Friflo.Engine.ECS.Tags).T1 'Friflo.Engine.ECS.EntityStoreBase.GetArchetype<T1,T2,T3,T4,T5>(Friflo.Engine.ECS.Signature<T1,T2,T3,T4,T5>, Friflo.Engine.ECS.Tags).T1')[,](Signature_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3,T4,T5>')[T2](EntityStoreBase.GetArchetype_T1,T2,T3,T4,T5_(Signature_T1,T2,T3,T4,T5_,Tags).md#Friflo.Engine.ECS.EntityStoreBase.GetArchetype_T1,T2,T3,T4,T5_(Friflo.Engine.ECS.Signature_T1,T2,T3,T4,T5_,Friflo.Engine.ECS.Tags).T2 'Friflo.Engine.ECS.EntityStoreBase.GetArchetype<T1,T2,T3,T4,T5>(Friflo.Engine.ECS.Signature<T1,T2,T3,T4,T5>, Friflo.Engine.ECS.Tags).T2')[,](Signature_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3,T4,T5>')[T3](EntityStoreBase.GetArchetype_T1,T2,T3,T4,T5_(Signature_T1,T2,T3,T4,T5_,Tags).md#Friflo.Engine.ECS.EntityStoreBase.GetArchetype_T1,T2,T3,T4,T5_(Friflo.Engine.ECS.Signature_T1,T2,T3,T4,T5_,Friflo.Engine.ECS.Tags).T3 'Friflo.Engine.ECS.EntityStoreBase.GetArchetype<T1,T2,T3,T4,T5>(Friflo.Engine.ECS.Signature<T1,T2,T3,T4,T5>, Friflo.Engine.ECS.Tags).T3')[,](Signature_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3,T4,T5>')[T4](EntityStoreBase.GetArchetype_T1,T2,T3,T4,T5_(Signature_T1,T2,T3,T4,T5_,Tags).md#Friflo.Engine.ECS.EntityStoreBase.GetArchetype_T1,T2,T3,T4,T5_(Friflo.Engine.ECS.Signature_T1,T2,T3,T4,T5_,Friflo.Engine.ECS.Tags).T4 'Friflo.Engine.ECS.EntityStoreBase.GetArchetype<T1,T2,T3,T4,T5>(Friflo.Engine.ECS.Signature<T1,T2,T3,T4,T5>, Friflo.Engine.ECS.Tags).T4')[,](Signature_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3,T4,T5>')[T5](EntityStoreBase.GetArchetype_T1,T2,T3,T4,T5_(Signature_T1,T2,T3,T4,T5_,Tags).md#Friflo.Engine.ECS.EntityStoreBase.GetArchetype_T1,T2,T3,T4,T5_(Friflo.Engine.ECS.Signature_T1,T2,T3,T4,T5_,Friflo.Engine.ECS.Tags).T5 'Friflo.Engine.ECS.EntityStoreBase.GetArchetype<T1,T2,T3,T4,T5>(Friflo.Engine.ECS.Signature<T1,T2,T3,T4,T5>, Friflo.Engine.ECS.Tags).T5')[&gt;](Signature_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3,T4,T5>')

<a name='Friflo.Engine.ECS.EntityStoreBase.GetArchetype_T1,T2,T3,T4,T5_(Friflo.Engine.ECS.Signature_T1,T2,T3,T4,T5_,Friflo.Engine.ECS.Tags).tags'></a>

`tags` [Tags](Tags.md 'Friflo.Engine.ECS.Tags')

#### Returns
[Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype')