#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Index](Friflo.Engine.ECS.Index.md 'Friflo.Engine.ECS.Index')

## RangeIndex<TValue> Class

A component index optimized to execute range queries in O(log N) at the cost of index updates in O(log N).<br/>
The default index executed index updates in O(1):

```csharp
public sealed class RangeIndex<TValue> : Friflo.Engine.ECS.Index.ComponentIndex<TValue>
```
#### Type parameters

<a name='Friflo.Engine.ECS.Index.RangeIndex_TValue_.TValue'></a>

`TValue`

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; [ComponentIndex](ComponentIndex.md 'Friflo.Engine.ECS.Index.ComponentIndex') &#129106; [Friflo.Engine.ECS.Index.ComponentIndex&lt;](ComponentIndex_TValue_.md 'Friflo.Engine.ECS.Index.ComponentIndex<TValue>')[TValue](RangeIndex_TValue_.md#Friflo.Engine.ECS.Index.RangeIndex_TValue_.TValue 'Friflo.Engine.ECS.Index.RangeIndex<TValue>.TValue')[&gt;](ComponentIndex_TValue_.md 'Friflo.Engine.ECS.Index.ComponentIndex<TValue>') &#129106; RangeIndex<TValue>