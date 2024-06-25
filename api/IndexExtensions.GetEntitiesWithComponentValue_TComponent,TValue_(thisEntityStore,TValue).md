#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Index](Friflo.Engine.ECS.Index.md 'Friflo.Engine.ECS.Index').[IndexExtensions](IndexExtensions.md 'Friflo.Engine.ECS.Index.IndexExtensions')

## IndexExtensions.GetEntitiesWithComponentValue<TComponent,TValue>(this EntityStore, TValue) Method

Return the entities with the passed component value.<br/>
Executes in O(1) with default index.

```csharp
public static Friflo.Engine.ECS.Entities GetEntitiesWithComponentValue<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore store, TValue value)
    where TComponent : struct, Friflo.Engine.ECS.Index.IIndexedComponent<TValue>, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Index.IndexExtensions.GetEntitiesWithComponentValue_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore,TValue).TComponent'></a>

`TComponent`

<a name='Friflo.Engine.ECS.Index.IndexExtensions.GetEntitiesWithComponentValue_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore,TValue).TValue'></a>

`TValue`
#### Parameters

<a name='Friflo.Engine.ECS.Index.IndexExtensions.GetEntitiesWithComponentValue_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore,TValue).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

<a name='Friflo.Engine.ECS.Index.IndexExtensions.GetEntitiesWithComponentValue_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore,TValue).value'></a>

`value` [TValue](IndexExtensions.GetEntitiesWithComponentValue_TComponent,TValue_(thisEntityStore,TValue).md#Friflo.Engine.ECS.Index.IndexExtensions.GetEntitiesWithComponentValue_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore,TValue).TValue 'Friflo.Engine.ECS.Index.IndexExtensions.GetEntitiesWithComponentValue<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore, TValue).TValue')

#### Returns
[Entities](Entities.md 'Friflo.Engine.ECS.Entities')