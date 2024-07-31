#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## EntityData Struct

An [EntityData](EntityData.md 'Friflo.Engine.ECS.EntityData') is used to optimize access of entity components and tags.<br/>
An instance can be returned by [Data](Entity.Data.md 'Friflo.Engine.ECS.Entity.Data').

```csharp
public readonly ref struct EntityData
```

### Remarks
It should be used if reading or updating multiple components of the same entity to optimize component access.

| Fields | |
| :--- | :--- |
| [Id](EntityData.Id.md 'Friflo.Engine.ECS.EntityData.Id') | [Entity](Entity.md 'Friflo.Engine.ECS.Entity') id |

| Properties | |
| :--- | :--- |
| [Archetype](EntityData.Archetype.md 'Friflo.Engine.ECS.EntityData.Archetype') | Returns the archetype the entity belongs to. |
| [Components](EntityData.Components.md 'Friflo.Engine.ECS.EntityData.Components') | Return the [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')'s added to the entity. |
| [IsNull](EntityData.IsNull.md 'Friflo.Engine.ECS.EntityData.IsNull') | Returns true is the entity is deleted. |
| [Tags](EntityData.Tags.md 'Friflo.Engine.ECS.EntityData.Tags') | Return the [Tags](Tags.md 'Friflo.Engine.ECS.Tags') added to an entity. |

| Methods | |
| :--- | :--- |
| [Get&lt;T&gt;()](EntityData.Get_T_().md 'Friflo.Engine.ECS.EntityData.Get<T>()') | Return the component of the given type as a reference. |
| [Has&lt;T&gt;()](EntityData.Has_T_().md 'Friflo.Engine.ECS.EntityData.Has<T>()') | Returns true if the entity contains a component of the specified type. |
| [ToString()](EntityData.ToString().md 'Friflo.Engine.ECS.EntityData.ToString()') | |
| [TryGet&lt;T&gt;(T)](EntityData.TryGet_T_(T).md 'Friflo.Engine.ECS.EntityData.TryGet<T>(T)') | Gets the component of the specififed type.<br/> Returns true if the entity contains a component of specified type. Otherwise false. |
