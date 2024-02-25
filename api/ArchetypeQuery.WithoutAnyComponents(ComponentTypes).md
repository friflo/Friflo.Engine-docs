#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery')

## ArchetypeQuery.WithoutAnyComponents(ComponentTypes) Method

Entities having any of the passed [componentTypes](ArchetypeQuery.WithoutAnyComponents(ComponentTypes).md#Friflo.Engine.ECS.ArchetypeQuery.WithoutAnyComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes 'Friflo.Engine.ECS.ArchetypeQuery.WithoutAnyComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes') are excluded from query result.

```csharp
public Friflo.Engine.ECS.ArchetypeQuery WithoutAnyComponents(in Friflo.Engine.ECS.ComponentTypes componentTypes);
```
#### Parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery.WithoutAnyComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes'></a>

`componentTypes` [ComponentTypes](ComponentTypes.md 'Friflo.Engine.ECS.ComponentTypes')

Use `ComponentTypes.Get<>()` to set the parameter.

#### Returns
[ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery')