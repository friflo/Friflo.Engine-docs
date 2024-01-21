#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Signature](Signature.md 'Friflo.Engine.ECS.Signature')

## Signature.Get<T1,T2,T3>() Method

Returns a [Signature&lt;T1,T2,T3&gt;](Signature_T1,T2,T3_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3>') containing the given component types.<br/>[Signature&lt;T1,T2,T3&gt;](Signature_T1,T2,T3_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3>') features:
- Get the [Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype') of an [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') using [GetArchetype&lt;T1,T2,T3&gt;(Signature&lt;T1,T2,T3&gt;, Tags)](EntityStoreBase.GetArchetype_T1,T2,T3_(Signature_T1,T2,T3_,Tags).md 'Friflo.Engine.ECS.EntityStoreBase.GetArchetype<T1,T2,T3>(Friflo.Engine.ECS.Signature<T1,T2,T3>, Friflo.Engine.ECS.Tags)').
- Create a query to process all entities containing the given component types [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore').Query() methods.

```csharp
public static Friflo.Engine.ECS.Signature<T1,T2,T3> Get<T1,T2,T3>()
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Signature.Get_T1,T2,T3_().T1'></a>

`T1`

<a name='Friflo.Engine.ECS.Signature.Get_T1,T2,T3_().T2'></a>

`T2`

<a name='Friflo.Engine.ECS.Signature.Get_T1,T2,T3_().T3'></a>

`T3`

#### Returns
[Friflo.Engine.ECS.Signature&lt;](Signature_T1,T2,T3_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3>')[T1](Signature.Get_T1,T2,T3_().md#Friflo.Engine.ECS.Signature.Get_T1,T2,T3_().T1 'Friflo.Engine.ECS.Signature.Get<T1,T2,T3>().T1')[,](Signature_T1,T2,T3_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3>')[T2](Signature.Get_T1,T2,T3_().md#Friflo.Engine.ECS.Signature.Get_T1,T2,T3_().T2 'Friflo.Engine.ECS.Signature.Get<T1,T2,T3>().T2')[,](Signature_T1,T2,T3_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3>')[T3](Signature.Get_T1,T2,T3_().md#Friflo.Engine.ECS.Signature.Get_T1,T2,T3_().T3 'Friflo.Engine.ECS.Signature.Get<T1,T2,T3>().T3')[&gt;](Signature_T1,T2,T3_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3>')