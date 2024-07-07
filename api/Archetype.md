#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## Archetype Class

An [Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype') store entities with a specific set of [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') and [ITag](ITag.md 'Friflo.Engine.ECS.ITag') types.<br/>
See <a href="https://github.com/friflo/Friflo.Json.Fliox/wiki/Examples-~-General#archetype">Example.</a>

```csharp
public sealed class Archetype
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; Archetype

### Remarks
E.g. all entities with a [Position](Position.md 'Friflo.Engine.ECS.Position') and [Rotation](Rotation.md 'Friflo.Engine.ECS.Rotation') component are store in the same archetype.<br/>
In case of removing one of these components or adding a new one from / to an [Entity](Entity.md 'Friflo.Engine.ECS.Entity') the entity is moved to a different archetype.<br/><br/>
This is the basic pattern for an archetype base ECS. This approach enables efficient entity / component queries.<br/>
A query result is simply the union of all archetypes having the requested components.<br/><br/>
Queries can be created via generic [EntityStoreBase](EntityStoreBase.md 'Friflo.Engine.ECS.EntityStoreBase').`Query()` methods.<br/>

| Properties | |
| :--- | :--- |
| [Capacity](Archetype.Capacity.md 'Friflo.Engine.ECS.Archetype.Capacity') | The current capacity reserved to store entity components. |
| [ComponentCount](Archetype.ComponentCount.md 'Friflo.Engine.ECS.Archetype.ComponentCount') | Number of [ComponentTypes](Archetype.ComponentTypes.md 'Friflo.Engine.ECS.Archetype.ComponentTypes') managed by the archetype. |
| [ComponentTypes](Archetype.ComponentTypes.md 'Friflo.Engine.ECS.Archetype.ComponentTypes') | The [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') types managed by the archetype. |
| [Count](Archetype.Count.md 'Friflo.Engine.ECS.Archetype.Count') | Number of entities / components stored in the [Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype') |
| [Entities](Archetype.Entities.md 'Friflo.Engine.ECS.Archetype.Entities') | Return all [Entity](Entity.md 'Friflo.Engine.ECS.Entity')'s stored in the [Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype'). |
| [EntityCount](Archetype.EntityCount.md 'Friflo.Engine.ECS.Archetype.EntityCount') | Obsolete. Renamed to [Count](Archetype.Count.md 'Friflo.Engine.ECS.Archetype.Count'). |
| [EntityIds](Archetype.EntityIds.md 'Friflo.Engine.ECS.Archetype.EntityIds') | Return the entity ids stored in the archetype. |
| [Name](Archetype.Name.md 'Friflo.Engine.ECS.Archetype.Name') | |
| [Store](Archetype.Store.md 'Friflo.Engine.ECS.Archetype.Store') | The [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') owning the archetype. |
| [Tags](Archetype.Tags.md 'Friflo.Engine.ECS.Archetype.Tags') | The [ITag](ITag.md 'Friflo.Engine.ECS.ITag') types managed by the archetype. |

| Methods | |
| :--- | :--- |
| [Components&lt;TComponent&gt;()](Archetype.Components_TComponent_().md 'Friflo.Engine.ECS.Archetype.Components<TComponent>()') | Return the components of the specified [TComponent](Archetype.Components_TComponent_().md#Friflo.Engine.ECS.Archetype.Components_TComponent_().TComponent 'Friflo.Engine.ECS.Archetype.Components<TComponent>().TComponent') type stored in the archetype. |
| [CreateEntities(int)](Archetype.CreateEntities(int).md 'Friflo.Engine.ECS.Archetype.CreateEntities(int)') | |
| [CreateEntity()](Archetype.CreateEntity().md 'Friflo.Engine.ECS.Archetype.CreateEntity()') | Create an [Entity](Entity.md 'Friflo.Engine.ECS.Entity') with the [ComponentTypes](Archetype.ComponentTypes.md 'Friflo.Engine.ECS.Archetype.ComponentTypes') and [Tags](Archetype.Tags.md 'Friflo.Engine.ECS.Archetype.Tags') managed by the archetype. |
| [CreateEntity(int)](Archetype.CreateEntity(int).md 'Friflo.Engine.ECS.Archetype.CreateEntity(int)') | |
| [EnsureCapacity(int)](Archetype.EnsureCapacity(int).md 'Friflo.Engine.ECS.Archetype.EnsureCapacity(int)') | Allocates memory for entity components in the archetype to enable adding entity components without reallocation. |
| [ToString()](Archetype.ToString().md 'Friflo.Engine.ECS.Archetype.ToString()') | |
