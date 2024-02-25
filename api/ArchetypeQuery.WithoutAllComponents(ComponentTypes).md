#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[ArchetypeQuery](ArchetypeQuery.md#'Friflo.Engine.ECS.ArchetypeQuery')

## ArchetypeQuery.WithoutAllComponents(ComponentTypes) Method

Entities having all passed [componentTypes](ArchetypeQuery.WithoutAllComponents(ComponentTypes).md#Friflo.Engine.ECS.ArchetypeQuery.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes#'Friflo.Engine.ECS.ArchetypeQuery.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes') are excluded from query result.

```csharp
public Friflo.Engine.ECS.ArchetypeQuery WithoutAllComponents(in Friflo.Engine.ECS.ComponentTypes componentTypes);
```
#### Parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes'></a>

`componentTypes` [ComponentTypes](ComponentTypes.md#'Friflo.Engine.ECS.ComponentTypes')

Use `ComponentTypes.Get<>()` to set the parameter.

#### Returns
[ArchetypeQuery](ArchetypeQuery.md#'Friflo.Engine.ECS.ArchetypeQuery')