#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[ArchetypeQuery&lt;T1,T2,T3,T4,T5&gt;](ArchetypeQuery_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>')

## ArchetypeQuery<T1,T2,T3,T4,T5>.ValueInRange<TComponent,TValue>(TValue, TValue) Method

Include entities having a component value in the specified range.

```csharp
public Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5> ValueInRange<TComponent,TValue>(TValue min, TValue max)
    where TComponent : struct, Friflo.Engine.ECS.Index.IIndexedComponent<TValue>, System.ValueType, System.ValueType
    where TValue : System.IComparable<TValue>;
```
#### Type parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3,T4,T5_.ValueInRange_TComponent,TValue_(TValue,TValue).TComponent'></a>

`TComponent`

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3,T4,T5_.ValueInRange_TComponent,TValue_(TValue,TValue).TValue'></a>

`TValue`
#### Parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3,T4,T5_.ValueInRange_TComponent,TValue_(TValue,TValue).min'></a>

`min` [TValue](ArchetypeQuery_T1,T2,T3,T4,T5_.ValueInRange_TComponent,TValue_(TValue,TValue).md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3,T4,T5_.ValueInRange_TComponent,TValue_(TValue,TValue).TValue 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>.ValueInRange<TComponent,TValue>(TValue, TValue).TValue')

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3,T4,T5_.ValueInRange_TComponent,TValue_(TValue,TValue).max'></a>

`max` [TValue](ArchetypeQuery_T1,T2,T3,T4,T5_.ValueInRange_TComponent,TValue_(TValue,TValue).md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3,T4,T5_.ValueInRange_TComponent,TValue_(TValue,TValue).TValue 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>.ValueInRange<TComponent,TValue>(TValue, TValue).TValue')

#### Returns
[Friflo.Engine.ECS.ArchetypeQuery&lt;](ArchetypeQuery_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>')[T1](ArchetypeQuery_T1,T2,T3,T4,T5_.md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3,T4,T5_.T1 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>.T1')[,](ArchetypeQuery_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>')[T2](ArchetypeQuery_T1,T2,T3,T4,T5_.md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3,T4,T5_.T2 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>.T2')[,](ArchetypeQuery_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>')[T3](ArchetypeQuery_T1,T2,T3,T4,T5_.md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3,T4,T5_.T3 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>.T3')[,](ArchetypeQuery_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>')[T4](ArchetypeQuery_T1,T2,T3,T4,T5_.md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3,T4,T5_.T4 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>.T4')[,](ArchetypeQuery_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>')[T5](ArchetypeQuery_T1,T2,T3,T4,T5_.md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3,T4,T5_.T5 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>.T5')[&gt;](ArchetypeQuery_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>')