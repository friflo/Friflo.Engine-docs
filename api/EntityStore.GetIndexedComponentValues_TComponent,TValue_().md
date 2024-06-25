#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

## EntityStore.GetIndexedComponentValues<TComponent,TValue>() Method

Returns a collection of all indexed component values of the passed [TComponent](EntityStore.GetIndexedComponentValues_TComponent,TValue_().md#Friflo.Engine.ECS.EntityStore.GetIndexedComponentValues_TComponent,TValue_().TComponent 'Friflo.Engine.ECS.EntityStore.GetIndexedComponentValues<TComponent,TValue>().TComponent') type.<br/>
Executes in O(1). Each value in the returned list is unique. See remarks for additional infos.

```csharp
public System.Collections.Generic.IReadOnlyCollection<TValue> GetIndexedComponentValues<TComponent,TValue>()
    where TComponent : struct, Friflo.Engine.ECS.IIndexedComponent<TValue>, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityStore.GetIndexedComponentValues_TComponent,TValue_().TComponent'></a>

`TComponent`

<a name='Friflo.Engine.ECS.EntityStore.GetIndexedComponentValues_TComponent,TValue_().TValue'></a>

`TValue`

#### Returns
[System.Collections.Generic.IReadOnlyCollection&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')[TValue](EntityStore.GetIndexedComponentValues_TComponent,TValue_().md#Friflo.Engine.ECS.EntityStore.GetIndexedComponentValues_TComponent,TValue_().TValue 'Friflo.Engine.ECS.EntityStore.GetIndexedComponentValues<TComponent,TValue>().TValue')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')

### Remarks
- The collection changes when indexed component values are updated, removed or added.
- To get the entities having a specific component value use [GetEntitiesWithComponentValue&lt;TComponent,TValue&gt;(TValue)](EntityStore.GetEntitiesWithComponentValue_TComponent,TValue_(TValue).md 'Friflo.Engine.ECS.EntityStore.GetEntitiesWithComponentValue<TComponent,TValue>(TValue)').
- If [TValue](EntityStore.GetIndexedComponentValues_TComponent,TValue_().md#Friflo.Engine.ECS.EntityStore.GetIndexedComponentValues_TComponent,TValue_().TValue 'Friflo.Engine.ECS.EntityStore.GetIndexedComponentValues<TComponent,TValue>().TValue') is a class all collection values are not null.<br/>
  Use [GetEntitiesWithComponentValue&lt;TComponent,TValue&gt;(TValue)](EntityStore.GetEntitiesWithComponentValue_TComponent,TValue_(TValue).md 'Friflo.Engine.ECS.EntityStore.GetEntitiesWithComponentValue<TComponent,TValue>(TValue)') to check if null is referenced.