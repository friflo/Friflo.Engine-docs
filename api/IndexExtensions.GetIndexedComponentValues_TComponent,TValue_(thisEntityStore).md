#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Index](Friflo.Engine.ECS.Index.md 'Friflo.Engine.ECS.Index').[IndexExtensions](IndexExtensions.md 'Friflo.Engine.ECS.Index.IndexExtensions')

## IndexExtensions.GetIndexedComponentValues<TComponent,TValue>(this EntityStore) Method

Returns a collection of all indexed component values of the passed [TComponent](IndexExtensions.GetIndexedComponentValues_TComponent,TValue_(thisEntityStore).md#Friflo.Engine.ECS.Index.IndexExtensions.GetIndexedComponentValues_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore).TComponent 'Friflo.Engine.ECS.Index.IndexExtensions.GetIndexedComponentValues<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore).TComponent') type.<br/>
Executes in O(1). Each value in the returned list is unique. See remarks for additional infos.

```csharp
public static System.Collections.Generic.IReadOnlyCollection<TValue> GetIndexedComponentValues<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore store)
    where TComponent : struct, Friflo.Engine.ECS.Index.IIndexedComponent<TValue>, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Index.IndexExtensions.GetIndexedComponentValues_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore).TComponent'></a>

`TComponent`

<a name='Friflo.Engine.ECS.Index.IndexExtensions.GetIndexedComponentValues_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore).TValue'></a>

`TValue`
#### Parameters

<a name='Friflo.Engine.ECS.Index.IndexExtensions.GetIndexedComponentValues_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

#### Returns
[System.Collections.Generic.IReadOnlyCollection&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')[TValue](IndexExtensions.GetIndexedComponentValues_TComponent,TValue_(thisEntityStore).md#Friflo.Engine.ECS.Index.IndexExtensions.GetIndexedComponentValues_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore).TValue 'Friflo.Engine.ECS.Index.IndexExtensions.GetIndexedComponentValues<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore).TValue')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')

### Remarks
- The collection changes when indexed component values are updated, removed or added.
- To get the entities having a specific component value use [GetEntitiesWithComponentValue&lt;TComponent,TValue&gt;(this EntityStore, TValue)](IndexExtensions.GetEntitiesWithComponentValue_TComponent,TValue_(thisEntityStore,TValue).md 'Friflo.Engine.ECS.Index.IndexExtensions.GetEntitiesWithComponentValue<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore, TValue)').
- If [TValue](IndexExtensions.GetIndexedComponentValues_TComponent,TValue_(thisEntityStore).md#Friflo.Engine.ECS.Index.IndexExtensions.GetIndexedComponentValues_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore).TValue 'Friflo.Engine.ECS.Index.IndexExtensions.GetIndexedComponentValues<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore).TValue') is a class all collection values are not null.<br/>
  Use [GetEntitiesWithComponentValue&lt;TComponent,TValue&gt;(this EntityStore, TValue)](IndexExtensions.GetEntitiesWithComponentValue_TComponent,TValue_(thisEntityStore,TValue).md 'Friflo.Engine.ECS.Index.IndexExtensions.GetEntitiesWithComponentValue<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore, TValue)') to check if null is referenced.