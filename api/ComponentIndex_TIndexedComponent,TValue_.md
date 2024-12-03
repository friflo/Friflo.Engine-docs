#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ComponentIndex<TIndexedComponent,TValue> Struct

The index for [IIndexedComponent&lt;TValue&gt;](IIndexedComponent_TValue_.md 'Friflo.Engine.ECS.IIndexedComponent<TValue>') struct's to search entities with a specific component value in O(1).<br/>
An instance is returned via [ComponentIndex&lt;TIndexedComponent,TValue&gt;(this EntityStore)](IndexExtensions.ComponentIndex_TIndexedComponent,TValue_(thisEntityStore).md 'Friflo.Engine.ECS.IndexExtensions.ComponentIndex<TIndexedComponent,TValue>(this Friflo.Engine.ECS.EntityStore)').

```csharp
public readonly struct ComponentIndex<TIndexedComponent,TValue>
    where TIndexedComponent : struct, Friflo.Engine.ECS.IIndexedComponent<TValue>, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.ComponentIndex_TIndexedComponent,TValue_.TIndexedComponent'></a>

`TIndexedComponent`

<a name='Friflo.Engine.ECS.ComponentIndex_TIndexedComponent,TValue_.TValue'></a>

`TValue`

| Properties | |
| :--- | :--- |
| [this[TValue]](ComponentIndex_TIndexedComponent,TValue_.this[TValue].md 'Friflo.Engine.ECS.ComponentIndex<TIndexedComponent,TValue>.this[TValue]') | Return the entities having a component with the passed component value.<br/> Executes in O(1) with default index. |
| [Values](ComponentIndex_TIndexedComponent,TValue_.Values.md 'Friflo.Engine.ECS.ComponentIndex<TIndexedComponent,TValue>.Values') | Returns all indexed component values of the passed [TIndexedComponent](ComponentIndex_TIndexedComponent,TValue_.md#Friflo.Engine.ECS.ComponentIndex_TIndexedComponent,TValue_.TIndexedComponent 'Friflo.Engine.ECS.ComponentIndex<TIndexedComponent,TValue>.TIndexedComponent') type.<br/> Executes in O(1). Each value in the returned list is unique. See remarks for additional infos. |

| Methods | |
| :--- | :--- |
| [ToString()](ComponentIndex_TIndexedComponent,TValue_.ToString().md 'Friflo.Engine.ECS.ComponentIndex<TIndexedComponent,TValue>.ToString()') | |
