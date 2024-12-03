#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[IndexExtensions](IndexExtensions.md 'Friflo.Engine.ECS.IndexExtensions')

## IndexExtensions.GetEntitiesWithComponentValue<TComponent,TValue>(this EntityStore, TValue) Method

Obsolete: Use [this[TValue]](ComponentIndex_TIndexedComponent,TValue_.this[TValue].md 'Friflo.Engine.ECS.ComponentIndex<TIndexedComponent,TValue>.this[TValue]')<br/>
Return the entities with the passed component value.<br/>
Executes in O(1) with default index.

```csharp
public static Friflo.Engine.ECS.Entities GetEntitiesWithComponentValue<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore store, TValue value)
    where TComponent : struct, Friflo.Engine.ECS.IIndexedComponent<TValue>, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.IndexExtensions.GetEntitiesWithComponentValue_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore,TValue).TComponent'></a>

`TComponent`

<a name='Friflo.Engine.ECS.IndexExtensions.GetEntitiesWithComponentValue_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore,TValue).TValue'></a>

`TValue`
#### Parameters

<a name='Friflo.Engine.ECS.IndexExtensions.GetEntitiesWithComponentValue_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore,TValue).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

<a name='Friflo.Engine.ECS.IndexExtensions.GetEntitiesWithComponentValue_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore,TValue).value'></a>

`value` [TValue](IndexExtensions.GetEntitiesWithComponentValue_TComponent,TValue_(thisEntityStore,TValue).md#Friflo.Engine.ECS.IndexExtensions.GetEntitiesWithComponentValue_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore,TValue).TValue 'Friflo.Engine.ECS.IndexExtensions.GetEntitiesWithComponentValue<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore, TValue).TValue')

#### Returns
[Entities](Entities.md 'Friflo.Engine.ECS.Entities')