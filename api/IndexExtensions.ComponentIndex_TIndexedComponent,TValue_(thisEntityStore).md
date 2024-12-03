#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[IndexExtensions](IndexExtensions.md 'Friflo.Engine.ECS.IndexExtensions')

## IndexExtensions.ComponentIndex<TIndexedComponent,TValue>(this EntityStore) Method

Returns the index for indexed components to search entities with a specific component value in O(1).<br/>
Executes in O(1).

```csharp
public static Friflo.Engine.ECS.ComponentIndex<TIndexedComponent,TValue> ComponentIndex<TIndexedComponent,TValue>(this Friflo.Engine.ECS.EntityStore store)
    where TIndexedComponent : struct, Friflo.Engine.ECS.IIndexedComponent<TValue>, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.IndexExtensions.ComponentIndex_TIndexedComponent,TValue_(thisFriflo.Engine.ECS.EntityStore).TIndexedComponent'></a>

`TIndexedComponent`

<a name='Friflo.Engine.ECS.IndexExtensions.ComponentIndex_TIndexedComponent,TValue_(thisFriflo.Engine.ECS.EntityStore).TValue'></a>

`TValue`
#### Parameters

<a name='Friflo.Engine.ECS.IndexExtensions.ComponentIndex_TIndexedComponent,TValue_(thisFriflo.Engine.ECS.EntityStore).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

#### Returns
[Friflo.Engine.ECS.ComponentIndex&lt;](ComponentIndex_TIndexedComponent,TValue_.md 'Friflo.Engine.ECS.ComponentIndex<TIndexedComponent,TValue>')[TIndexedComponent](IndexExtensions.ComponentIndex_TIndexedComponent,TValue_(thisEntityStore).md#Friflo.Engine.ECS.IndexExtensions.ComponentIndex_TIndexedComponent,TValue_(thisFriflo.Engine.ECS.EntityStore).TIndexedComponent 'Friflo.Engine.ECS.IndexExtensions.ComponentIndex<TIndexedComponent,TValue>(this Friflo.Engine.ECS.EntityStore).TIndexedComponent')[,](ComponentIndex_TIndexedComponent,TValue_.md 'Friflo.Engine.ECS.ComponentIndex<TIndexedComponent,TValue>')[TValue](IndexExtensions.ComponentIndex_TIndexedComponent,TValue_(thisEntityStore).md#Friflo.Engine.ECS.IndexExtensions.ComponentIndex_TIndexedComponent,TValue_(thisFriflo.Engine.ECS.EntityStore).TValue 'Friflo.Engine.ECS.IndexExtensions.ComponentIndex<TIndexedComponent,TValue>(this Friflo.Engine.ECS.EntityStore).TValue')[&gt;](ComponentIndex_TIndexedComponent,TValue_.md 'Friflo.Engine.ECS.ComponentIndex<TIndexedComponent,TValue>')