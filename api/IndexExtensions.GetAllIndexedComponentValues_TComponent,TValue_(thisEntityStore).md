#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[IndexExtensions](IndexExtensions.md 'Friflo.Engine.ECS.IndexExtensions')

## IndexExtensions.GetAllIndexedComponentValues<TComponent,TValue>(this EntityStore) Method

Obsolete: Use [Values](ComponentIndex_TIndexedComponent,TValue_.Values.md 'Friflo.Engine.ECS.ComponentIndex<TIndexedComponent,TValue>.Values')<br/>
Returns all indexed component values of the passed [TComponent](IndexExtensions.GetAllIndexedComponentValues_TComponent,TValue_(thisEntityStore).md#Friflo.Engine.ECS.IndexExtensions.GetAllIndexedComponentValues_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore).TComponent 'Friflo.Engine.ECS.IndexExtensions.GetAllIndexedComponentValues<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore).TComponent') type.<br/>
Executes in O(1). Each value in the returned list is unique. See remarks for additional infos.

```csharp
public static System.Collections.Generic.IReadOnlyCollection<TValue> GetAllIndexedComponentValues<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore store)
    where TComponent : struct, Friflo.Engine.ECS.IIndexedComponent<TValue>, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.IndexExtensions.GetAllIndexedComponentValues_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore).TComponent'></a>

`TComponent`

<a name='Friflo.Engine.ECS.IndexExtensions.GetAllIndexedComponentValues_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore).TValue'></a>

`TValue`
#### Parameters

<a name='Friflo.Engine.ECS.IndexExtensions.GetAllIndexedComponentValues_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

#### Returns
[System.Collections.Generic.IReadOnlyCollection&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')[TValue](IndexExtensions.GetAllIndexedComponentValues_TComponent,TValue_(thisEntityStore).md#Friflo.Engine.ECS.IndexExtensions.GetAllIndexedComponentValues_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore).TValue 'Friflo.Engine.ECS.IndexExtensions.GetAllIndexedComponentValues<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore).TValue')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')

### Remarks
- The returned collection changes when indexed component values are updated, removed or added.
- To get the entities having a specific component value use [this[TValue]](ComponentIndex_TIndexedComponent,TValue_.this[TValue].md 'Friflo.Engine.ECS.ComponentIndex<TIndexedComponent,TValue>.this[TValue]').
- If [TValue](IndexExtensions.GetAllIndexedComponentValues_TComponent,TValue_(thisEntityStore).md#Friflo.Engine.ECS.IndexExtensions.GetAllIndexedComponentValues_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore).TValue 'Friflo.Engine.ECS.IndexExtensions.GetAllIndexedComponentValues<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore).TValue') is a class all collection values are not null.<br/>
  Use [this[TValue]](ComponentIndex_TIndexedComponent,TValue_.this[TValue].md 'Friflo.Engine.ECS.ComponentIndex<TIndexedComponent,TValue>.this[TValue]') to check if null is referenced.