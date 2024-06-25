#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[ArchetypeQuery&lt;T1,T2&gt;](ArchetypeQuery_T1,T2_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>')

## ArchetypeQuery<T1,T2>.HasValue<TComponent,TValue>(TValue) Method

Include entities having a component with the specified value.

```csharp
public Friflo.Engine.ECS.ArchetypeQuery<T1,T2> HasValue<TComponent,TValue>(TValue value)
    where TComponent : struct, Friflo.Engine.ECS.IIndexedComponent<TValue>, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2_.HasValue_TComponent,TValue_(TValue).TComponent'></a>

`TComponent`

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2_.HasValue_TComponent,TValue_(TValue).TValue'></a>

`TValue`
#### Parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2_.HasValue_TComponent,TValue_(TValue).value'></a>

`value` [TValue](ArchetypeQuery_T1,T2_.HasValue_TComponent,TValue_(TValue).md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2_.HasValue_TComponent,TValue_(TValue).TValue 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>.HasValue<TComponent,TValue>(TValue).TValue')

#### Returns
[Friflo.Engine.ECS.ArchetypeQuery&lt;](ArchetypeQuery_T1,T2_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>')[T1](ArchetypeQuery_T1,T2_.md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2_.T1 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>.T1')[,](ArchetypeQuery_T1,T2_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>')[T2](ArchetypeQuery_T1,T2_.md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2_.T2 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>.T2')[&gt;](ArchetypeQuery_T1,T2_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>')