#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[ComponentIndex&lt;TIndexedComponent,TValue&gt;](ComponentIndex_TIndexedComponent,TValue_.md 'Friflo.Engine.ECS.ComponentIndex<TIndexedComponent,TValue>')

## ComponentIndex<TIndexedComponent,TValue>.Values Property

Returns all indexed component values of the passed [TIndexedComponent](ComponentIndex_TIndexedComponent,TValue_.md#Friflo.Engine.ECS.ComponentIndex_TIndexedComponent,TValue_.TIndexedComponent 'Friflo.Engine.ECS.ComponentIndex<TIndexedComponent,TValue>.TIndexedComponent') type.<br/>
Executes in O(1). Each value in the returned list is unique. See remarks for additional infos.

```csharp
public System.Collections.Generic.IReadOnlyCollection<TValue> Values { get; }
```

#### Property Value
[System.Collections.Generic.IReadOnlyCollection&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')[TValue](ComponentIndex_TIndexedComponent,TValue_.md#Friflo.Engine.ECS.ComponentIndex_TIndexedComponent,TValue_.TValue 'Friflo.Engine.ECS.ComponentIndex<TIndexedComponent,TValue>.TValue')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')

### Remarks
- The returned collection changes when indexed component values are updated, removed or added.
- To get the entities having a specific component value use [this[TValue]](ComponentIndex_TIndexedComponent,TValue_.this[TValue].md 'Friflo.Engine.ECS.ComponentIndex<TIndexedComponent,TValue>.this[TValue]').
- If [TValue](ComponentIndex_TIndexedComponent,TValue_.md#Friflo.Engine.ECS.ComponentIndex_TIndexedComponent,TValue_.TValue 'Friflo.Engine.ECS.ComponentIndex<TIndexedComponent,TValue>.TValue') is a class all collection values are not null.<br/>
  Use [this[TValue]](ComponentIndex_TIndexedComponent,TValue_.this[TValue].md 'Friflo.Engine.ECS.ComponentIndex<TIndexedComponent,TValue>.this[TValue]') to check if null is indexed.