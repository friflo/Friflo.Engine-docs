#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS')

## Signature Class

A [Signature](Signature.md#'Friflo.Engine.ECS.Signature') specify the [IComponent](IComponent.md#'Friflo.Engine.ECS.IComponent') types used to query entity components<br/>
using the [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore').Query([Signature](Signature.md#'Friflo.Engine.ECS.Signature')) methods.

```csharp
public static class Signature
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object#'System.Object') &#129106; Signature

### Remarks
In contrast to [ComponentTypes](ComponentTypes.md#'Friflo.Engine.ECS.ComponentTypes') the order of [IComponent](IComponent.md#'Friflo.Engine.ECS.IComponent')'s stored in a signature is
relevant for queries.<br/>
The maximum number of [IComponent](IComponent.md#'Friflo.Engine.ECS.IComponent')'s stored in a signature is currently 5.<br/>

| Methods | |
| :--- | :--- |
| [Get&lt;T1,T2,T3,T4,T5&gt;()](Signature.Get_T1,T2,T3,T4,T5_().md#'Friflo.Engine.ECS.Signature.Get<T1,T2,T3,T4,T5>()') | Returns a query [Signature&lt;T1,T2,T3,T4,T5&gt;](Signature_T1,T2,T3,T4,T5_.md#'Friflo.Engine.ECS.Signature<T1,T2,T3,T4,T5>') containing the specified component types.<br/> |
| [Get&lt;T1,T2,T3,T4&gt;()](Signature.Get_T1,T2,T3,T4_().md#'Friflo.Engine.ECS.Signature.Get<T1,T2,T3,T4>()') | Returns a query [Signature&lt;T1,T2,T3,T4&gt;](Signature_T1,T2,T3,T4_.md#'Friflo.Engine.ECS.Signature<T1,T2,T3,T4>') containing the specified component types.<br/> |
| [Get&lt;T1,T2,T3&gt;()](Signature.Get_T1,T2,T3_().md#'Friflo.Engine.ECS.Signature.Get<T1,T2,T3>()') | Returns a query [Signature&lt;T1,T2,T3&gt;](Signature_T1,T2,T3_.md#'Friflo.Engine.ECS.Signature<T1,T2,T3>') containing the specified component types.<br/> |
| [Get&lt;T1,T2&gt;()](Signature.Get_T1,T2_().md#'Friflo.Engine.ECS.Signature.Get<T1,T2>()') | Returns a query [Signature&lt;T1,T2&gt;](Signature_T1,T2_.md#'Friflo.Engine.ECS.Signature<T1,T2>') containing the specified component types.<br/> |
| [Get&lt;T1&gt;()](Signature.Get_T1_().md#'Friflo.Engine.ECS.Signature.Get<T1>()') | Returns a query [Signature&lt;T1&gt;](Signature_T1_.md#'Friflo.Engine.ECS.Signature<T1>') containing the specified component type.<br/> |
