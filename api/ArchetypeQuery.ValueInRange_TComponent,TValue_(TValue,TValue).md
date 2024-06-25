#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery')

## ArchetypeQuery.ValueInRange<TComponent,TValue>(TValue, TValue) Method

Include entities having a component value in the specified range.

```csharp
public Friflo.Engine.ECS.ArchetypeQuery ValueInRange<TComponent,TValue>(TValue min, TValue max)
    where TComponent : struct, Friflo.Engine.ECS.IIndexedComponent<TValue>, System.ValueType, System.ValueType
    where TValue : System.IComparable<TValue>;
```
#### Type parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery.ValueInRange_TComponent,TValue_(TValue,TValue).TComponent'></a>

`TComponent`

<a name='Friflo.Engine.ECS.ArchetypeQuery.ValueInRange_TComponent,TValue_(TValue,TValue).TValue'></a>

`TValue`
#### Parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery.ValueInRange_TComponent,TValue_(TValue,TValue).min'></a>

`min` [TValue](ArchetypeQuery.ValueInRange_TComponent,TValue_(TValue,TValue).md#Friflo.Engine.ECS.ArchetypeQuery.ValueInRange_TComponent,TValue_(TValue,TValue).TValue 'Friflo.Engine.ECS.ArchetypeQuery.ValueInRange<TComponent,TValue>(TValue, TValue).TValue')

<a name='Friflo.Engine.ECS.ArchetypeQuery.ValueInRange_TComponent,TValue_(TValue,TValue).max'></a>

`max` [TValue](ArchetypeQuery.ValueInRange_TComponent,TValue_(TValue,TValue).md#Friflo.Engine.ECS.ArchetypeQuery.ValueInRange_TComponent,TValue_(TValue,TValue).TValue 'Friflo.Engine.ECS.ArchetypeQuery.ValueInRange<TComponent,TValue>(TValue, TValue).TValue')

#### Returns
[ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery')