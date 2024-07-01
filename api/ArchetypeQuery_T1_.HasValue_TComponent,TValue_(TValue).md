#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[ArchetypeQuery&lt;T1&gt;](ArchetypeQuery_T1_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1>')

## ArchetypeQuery<T1>.HasValue<TComponent,TValue>(TValue) Method

Include entities having a component with the specified value.<br/>
Executes in O(1).

```csharp
public Friflo.Engine.ECS.ArchetypeQuery<T1> HasValue<TComponent,TValue>(TValue value)
    where TComponent : struct, Friflo.Engine.ECS.IIndexedComponent<TValue>, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1_.HasValue_TComponent,TValue_(TValue).TComponent'></a>

`TComponent`

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1_.HasValue_TComponent,TValue_(TValue).TValue'></a>

`TValue`
#### Parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1_.HasValue_TComponent,TValue_(TValue).value'></a>

`value` [TValue](ArchetypeQuery_T1_.HasValue_TComponent,TValue_(TValue).md#Friflo.Engine.ECS.ArchetypeQuery_T1_.HasValue_TComponent,TValue_(TValue).TValue 'Friflo.Engine.ECS.ArchetypeQuery<T1>.HasValue<TComponent,TValue>(TValue).TValue')

#### Returns
[Friflo.Engine.ECS.ArchetypeQuery&lt;](ArchetypeQuery_T1_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1>')[T1](ArchetypeQuery_T1_.md#Friflo.Engine.ECS.ArchetypeQuery_T1_.T1 'Friflo.Engine.ECS.ArchetypeQuery<T1>.T1')[&gt;](ArchetypeQuery_T1_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1>')