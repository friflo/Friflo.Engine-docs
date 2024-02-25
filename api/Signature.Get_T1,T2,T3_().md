#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[Signature](Signature.md#'Friflo.Engine.ECS.Signature')

## Signature.Get<T1,T2,T3>() Method

Returns a query [Signature&lt;T1,T2,T3&gt;](Signature_T1,T2,T3_.md#'Friflo.Engine.ECS.Signature<T1,T2,T3>') containing the specified component types.<br/>

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
[Friflo.Engine.ECS.Signature&lt;](Signature_T1,T2,T3_.md#'Friflo.Engine.ECS.Signature<T1,T2,T3>')[T1](Signature.Get_T1,T2,T3_().md#Friflo.Engine.ECS.Signature.Get_T1,T2,T3_().T1#'Friflo.Engine.ECS.Signature.Get<T1,T2,T3>().T1')[,](Signature_T1,T2,T3_.md#'Friflo.Engine.ECS.Signature<T1,T2,T3>')[T2](Signature.Get_T1,T2,T3_().md#Friflo.Engine.ECS.Signature.Get_T1,T2,T3_().T2#'Friflo.Engine.ECS.Signature.Get<T1,T2,T3>().T2')[,](Signature_T1,T2,T3_.md#'Friflo.Engine.ECS.Signature<T1,T2,T3>')[T3](Signature.Get_T1,T2,T3_().md#Friflo.Engine.ECS.Signature.Get_T1,T2,T3_().T3#'Friflo.Engine.ECS.Signature.Get<T1,T2,T3>().T3')[&gt;](Signature_T1,T2,T3_.md#'Friflo.Engine.ECS.Signature<T1,T2,T3>')

### Remarks
It can be used to query entities with the specified component types with [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore').Query() methods.