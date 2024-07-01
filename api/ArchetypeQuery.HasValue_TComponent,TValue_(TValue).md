#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery')

## ArchetypeQuery.HasValue<TComponent,TValue>(TValue) Method

Include entities having a component with the specified value.<br/>
Executes in O(1).

```csharp
public Friflo.Engine.ECS.ArchetypeQuery HasValue<TComponent,TValue>(TValue value)
    where TComponent : struct, Friflo.Engine.ECS.IIndexedComponent<TValue>, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery.HasValue_TComponent,TValue_(TValue).TComponent'></a>

`TComponent`

<a name='Friflo.Engine.ECS.ArchetypeQuery.HasValue_TComponent,TValue_(TValue).TValue'></a>

`TValue`
#### Parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery.HasValue_TComponent,TValue_(TValue).value'></a>

`value` [TValue](ArchetypeQuery.HasValue_TComponent,TValue_(TValue).md#Friflo.Engine.ECS.ArchetypeQuery.HasValue_TComponent,TValue_(TValue).TValue 'Friflo.Engine.ECS.ArchetypeQuery.HasValue<TComponent,TValue>(TValue).TValue')

#### Returns
[ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery')