#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## IIndexedComponent<TValue> Interface

Is used to define a component type having a single indexed field / property.

```csharp
public interface IIndexedComponent<out TValue> :
Friflo.Engine.ECS.IComponent
```
#### Type parameters

<a name='Friflo.Engine.ECS.IIndexedComponent_TValue_.TValue'></a>

`TValue`

Derived  
&#8627; [ILinkComponent](ILinkComponent.md 'Friflo.Engine.ECS.ILinkComponent')

Implements [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')

### Remarks
This component type enables:
- Return all entities with a component field of a specific value. <br/>
  See [GetEntitiesWithComponentValue&lt;TComponent,TValue&gt;(TValue)](EntityStore.GetEntitiesWithComponentValue_TComponent,TValue_(TValue).md 'Friflo.Engine.ECS.EntityStore.GetEntitiesWithComponentValue<TComponent,TValue>(TValue)').
- Return a collection of all unique component values.<br/>
  See [GetIndexedComponentValues&lt;TComponent,TValue&gt;()](EntityStore.GetIndexedComponentValues_TComponent,TValue_().md 'Friflo.Engine.ECS.EntityStore.GetIndexedComponentValues<TComponent,TValue>()').
- Filter entities in a query having a specific component value.<br/>
  See [HasValue&lt;TComponent,TValue&gt;(TValue)](ArchetypeQuery.HasValue_TComponent,TValue_(TValue).md 'Friflo.Engine.ECS.ArchetypeQuery.HasValue<TComponent,TValue>(TValue)').
- Filter entities in a query with a component value in a specific range.<br/>
  See [ValueInRange&lt;TComponent,TValue&gt;(TValue, TValue)](ArchetypeQuery.ValueInRange_TComponent,TValue_(TValue,TValue).md 'Friflo.Engine.ECS.ArchetypeQuery.ValueInRange<TComponent,TValue>(TValue, TValue)').

| Methods | |
| :--- | :--- |
| [GetIndexedValue()](IIndexedComponent_TValue_.GetIndexedValue().md 'Friflo.Engine.ECS.IIndexedComponent<TValue>.GetIndexedValue()') | |
