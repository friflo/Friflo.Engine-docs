#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Index](Friflo.Engine.ECS.Index.md 'Friflo.Engine.ECS.Index')

## RangeIndex<TIndexedComponent,TValue> Class

A component index optimized to execute range queries in O(log N) at the cost of index updates in O(log N).<br/>
The default index executes in O(1) when adding, removing or updating indexed component values.

```csharp
public sealed class RangeIndex<TIndexedComponent,TValue> : Friflo.Engine.ECS.Index.GenericComponentIndex<TValue>
    where TIndexedComponent : struct, Friflo.Engine.ECS.IIndexedComponent<TValue>, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.Index.RangeIndex_TIndexedComponent,TValue_.TIndexedComponent'></a>

`TIndexedComponent`

<a name='Friflo.Engine.ECS.Index.RangeIndex_TIndexedComponent,TValue_.TValue'></a>

`TValue`

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; [AbstractComponentIndex](AbstractComponentIndex.md 'Friflo.Engine.ECS.Index.AbstractComponentIndex') &#129106; [Friflo.Engine.ECS.Index.GenericComponentIndex&lt;](GenericComponentIndex_TValue_.md 'Friflo.Engine.ECS.Index.GenericComponentIndex<TValue>')[TValue](RangeIndex_TIndexedComponent,TValue_.md#Friflo.Engine.ECS.Index.RangeIndex_TIndexedComponent,TValue_.TValue 'Friflo.Engine.ECS.Index.RangeIndex<TIndexedComponent,TValue>.TValue')[&gt;](GenericComponentIndex_TValue_.md 'Friflo.Engine.ECS.Index.GenericComponentIndex<TValue>') &#129106; RangeIndex<TIndexedComponent,TValue>