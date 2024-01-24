#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Signature](Signature.md 'Friflo.Engine.ECS.Signature')

## Signature.Get<T1,T2,T3,T4>() Method

Returns a query [Signature&lt;T1,T2,T3,T4&gt;](Signature_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3,T4>') containing the given component types.<br/>

```csharp
public static Friflo.Engine.ECS.Signature<T1,T2,T3,T4> Get<T1,T2,T3,T4>()
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T4 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Signature.Get_T1,T2,T3,T4_().T1'></a>

`T1`

<a name='Friflo.Engine.ECS.Signature.Get_T1,T2,T3,T4_().T2'></a>

`T2`

<a name='Friflo.Engine.ECS.Signature.Get_T1,T2,T3,T4_().T3'></a>

`T3`

<a name='Friflo.Engine.ECS.Signature.Get_T1,T2,T3,T4_().T4'></a>

`T4`

#### Returns
[Friflo.Engine.ECS.Signature&lt;](Signature_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3,T4>')[T1](Signature.Get_T1,T2,T3,T4_().md#Friflo.Engine.ECS.Signature.Get_T1,T2,T3,T4_().T1 'Friflo.Engine.ECS.Signature.Get<T1,T2,T3,T4>().T1')[,](Signature_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3,T4>')[T2](Signature.Get_T1,T2,T3,T4_().md#Friflo.Engine.ECS.Signature.Get_T1,T2,T3,T4_().T2 'Friflo.Engine.ECS.Signature.Get<T1,T2,T3,T4>().T2')[,](Signature_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3,T4>')[T3](Signature.Get_T1,T2,T3,T4_().md#Friflo.Engine.ECS.Signature.Get_T1,T2,T3,T4_().T3 'Friflo.Engine.ECS.Signature.Get<T1,T2,T3,T4>().T3')[,](Signature_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3,T4>')[T4](Signature.Get_T1,T2,T3,T4_().md#Friflo.Engine.ECS.Signature.Get_T1,T2,T3,T4_().T4 'Friflo.Engine.ECS.Signature.Get<T1,T2,T3,T4>().T4')[&gt;](Signature_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3,T4>')

### Remarks
It can be used to query entities with the given component types with [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore').Query() methods.