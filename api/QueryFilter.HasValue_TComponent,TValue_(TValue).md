#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[QueryFilter](QueryFilter.md 'Friflo.Engine.ECS.QueryFilter')

## QueryFilter.HasValue<TComponent,TValue>(TValue) Method

Include entities having a component with the specified value.

```csharp
public Friflo.Engine.ECS.QueryFilter HasValue<TComponent,TValue>(TValue value)
    where TComponent : struct, Friflo.Engine.ECS.Index.IIndexedComponent<TValue>, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.QueryFilter.HasValue_TComponent,TValue_(TValue).TComponent'></a>

`TComponent`

<a name='Friflo.Engine.ECS.QueryFilter.HasValue_TComponent,TValue_(TValue).TValue'></a>

`TValue`
#### Parameters

<a name='Friflo.Engine.ECS.QueryFilter.HasValue_TComponent,TValue_(TValue).value'></a>

`value` [TValue](QueryFilter.HasValue_TComponent,TValue_(TValue).md#Friflo.Engine.ECS.QueryFilter.HasValue_TComponent,TValue_(TValue).TValue 'Friflo.Engine.ECS.QueryFilter.HasValue<TComponent,TValue>(TValue).TValue')

#### Returns
[QueryFilter](QueryFilter.md 'Friflo.Engine.ECS.QueryFilter')