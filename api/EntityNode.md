#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS')

## EntityNode Struct

Used by the [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore') to store [Entity](Entity.md#'Friflo.Engine.ECS.Entity') components, scripts, tags and child entities
internally as an array of nodes.

```csharp
public struct EntityNode
```

### Remarks
[EntityNode](EntityNode.md#'Friflo.Engine.ECS.EntityNode')'s enable organizing entities in a tree graph structure.<br/>
            The tree graph is stored in an [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore') starting with a single [StoreRoot](EntityStore.StoreRoot.md#'Friflo.Engine.ECS.EntityStore.StoreRoot') entity.<br/><br/>
            It provide the properties listed below
            
- [Id](EntityNode.Id.md#'Friflo.Engine.ECS.EntityNode.Id') to identify an entity in its [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore')
- [Pid](EntityNode.Pid.md#'Friflo.Engine.ECS.EntityNode.Pid') used to store entities in a database
- [Entity](Entity.md#'Friflo.Engine.ECS.Entity') to access the [Entity](Entity.md#'Friflo.Engine.ECS.Entity') attached to a node
- [ParentId](EntityNode.ParentId.md#'Friflo.Engine.ECS.EntityNode.ParentId') and [ChildIds](EntityNode.ChildIds.md#'Friflo.Engine.ECS.EntityNode.ChildIds') to get the direct related nodes<b>
  <see cref="P:Friflo.Engine.ECS.EntityNode.Id"/>
</b><br/>
            The entity id change when performing an [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore') id cleanup.<br/>
            The clean remove unused ids and ensure that entities with the same [Archetype](EntityNode.Archetype.md#'Friflo.Engine.ECS.EntityNode.Archetype') have consecutive ids.<br/><br/><b>
  <see cref="P:Friflo.Engine.ECS.EntityNode.Pid"/>
</b><br/>
            When creating a new entity in the [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore') it generates a random [Pid](EntityNode.Pid.md#'Friflo.Engine.ECS.EntityNode.Pid')
            using [Friflo.Engine.ECS.EntityStore.GenerateRandomPidForId(System.Int32)](https://docs.microsoft.com/en-us/dotnet/api/Friflo.Engine.ECS.EntityStore.GenerateRandomPidForId#Friflo_Engine_ECS_EntityStore_GenerateRandomPidForId_System_Int32_#'Friflo.Engine.ECS.EntityStore.GenerateRandomPidForId(System.Int32)').<br/>
            Using random pids avoid merge conflicts when multiples users make changes to the same [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore') file / database.<br/>
            The probability generating the same pid by two different users is:
            

```csharp
p = 1 - exp(-r^2 / (2 * N))
r:  number of new entities added by a user to an existing [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore') (not the number of all entities)
N:  number of possible values = int.MaxValue = 2147483647
```
            See: https://en.wikipedia.org/wiki/Birthday_problem

| Properties | |
| :--- | :--- |
| [Archetype](EntityNode.Archetype.md#'Friflo.Engine.ECS.EntityNode.Archetype') | The [Archetype](Archetype.md#'Friflo.Engine.ECS.Archetype') the entity node is stored. |
| [ChildCount](EntityNode.ChildCount.md#'Friflo.Engine.ECS.EntityNode.ChildCount') | Number of child entities. |
| [ChildIds](EntityNode.ChildIds.md#'Friflo.Engine.ECS.EntityNode.ChildIds') | The child entities of an entity as an array of ids. |
| [Flags](EntityNode.Flags.md#'Friflo.Engine.ECS.EntityNode.Flags') | Internally used flags assigned to the entity. |
| [Id](EntityNode.Id.md#'Friflo.Engine.ECS.EntityNode.Id') | The unique entity id. |
| [ParentId](EntityNode.ParentId.md#'Friflo.Engine.ECS.EntityNode.ParentId') | The parent id of the entity. 0 - if the entity has no parent. |
| [Pid](EntityNode.Pid.md#'Friflo.Engine.ECS.EntityNode.Pid') | Permanent unique pid used for persistence of an entity in a database |

| Methods | |
| :--- | :--- |
| [ToString()](EntityNode.ToString().md#'Friflo.Engine.ECS.EntityNode.ToString()') | |
