#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

## EntityStore.GetEntitiesWithComponentValue<TComponent,TValue>(TValue) Method

Return the entities with the passed component value.<br/>
Executes in O(1) with default index.

```csharp
public Friflo.Engine.ECS.Entities GetEntitiesWithComponentValue<TComponent,TValue>(TValue value)
    where TComponent : struct, Friflo.Engine.ECS.IIndexedComponent<TValue>, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityStore.GetEntitiesWithComponentValue_TComponent,TValue_(TValue).TComponent'></a>

`TComponent`

<a name='Friflo.Engine.ECS.EntityStore.GetEntitiesWithComponentValue_TComponent,TValue_(TValue).TValue'></a>

`TValue`
#### Parameters

<a name='Friflo.Engine.ECS.EntityStore.GetEntitiesWithComponentValue_TComponent,TValue_(TValue).value'></a>

`value` [TValue](EntityStore.GetEntitiesWithComponentValue_TComponent,TValue_(TValue).md#Friflo.Engine.ECS.EntityStore.GetEntitiesWithComponentValue_TComponent,TValue_(TValue).TValue 'Friflo.Engine.ECS.EntityStore.GetEntitiesWithComponentValue<TComponent,TValue>(TValue).TValue')

#### Returns
[Entities](Entities.md 'Friflo.Engine.ECS.Entities')