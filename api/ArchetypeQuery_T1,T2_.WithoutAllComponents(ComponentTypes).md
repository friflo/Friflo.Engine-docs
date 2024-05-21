#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[ArchetypeQuery&lt;T1,T2&gt;](ArchetypeQuery_T1,T2_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>')

## ArchetypeQuery<T1,T2>.WithoutAllComponents(ComponentTypes) Method

Entities having all passed [componentTypes](ArchetypeQuery_T1,T2_.WithoutAllComponents(ComponentTypes).md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2_.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes') are excluded from query result.

```csharp
public Friflo.Engine.ECS.ArchetypeQuery<T1,T2> WithoutAllComponents(in Friflo.Engine.ECS.ComponentTypes componentTypes);
```
#### Parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2_.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes'></a>

`componentTypes` [ComponentTypes](ComponentTypes.md 'Friflo.Engine.ECS.ComponentTypes')

Use `ComponentTypes.Get<>()` to set the parameter.

#### Returns
[Friflo.Engine.ECS.ArchetypeQuery&lt;](ArchetypeQuery_T1,T2_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>')[T1](ArchetypeQuery_T1,T2_.md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2_.T1 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>.T1')[,](ArchetypeQuery_T1,T2_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>')[T2](ArchetypeQuery_T1,T2_.md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2_.T2 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>.T2')[&gt;](ArchetypeQuery_T1,T2_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>')