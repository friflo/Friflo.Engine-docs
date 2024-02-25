#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[Signature](Signature.md#'Friflo.Engine.ECS.Signature')

## Signature.Get<T1>() Method

Returns a query [Signature&lt;T1&gt;](Signature_T1_.md#'Friflo.Engine.ECS.Signature<T1>') containing the specified component type.<br/>

```csharp
public static Friflo.Engine.ECS.Signature<T1> Get<T1>()
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Signature.Get_T1_().T1'></a>

`T1`

#### Returns
[Friflo.Engine.ECS.Signature&lt;](Signature_T1_.md#'Friflo.Engine.ECS.Signature<T1>')[T1](Signature.Get_T1_().md#Friflo.Engine.ECS.Signature.Get_T1_().T1#'Friflo.Engine.ECS.Signature.Get<T1>().T1')[&gt;](Signature_T1_.md#'Friflo.Engine.ECS.Signature<T1>')

### Remarks
It can be used to query entities with the specified component type with [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore').Query() methods.