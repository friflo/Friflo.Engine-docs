#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## EntityNode Struct

Used by the [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') to store [Entity](Entity.md 'Friflo.Engine.ECS.Entity') components, scripts, tags and child entities
internally as an array of nodes.

```csharp
public struct EntityNode
```

### Remarks
[EntityNode](EntityNode.md 'Friflo.Engine.ECS.EntityNode')'s enable organizing entities in a tree graph structure.<br/>
            The tree graph is stored in a [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') starting with a single [StoreRoot](EntityStore.StoreRoot.md 'Friflo.Engine.ECS.EntityStore.StoreRoot') entity.<br/><br/>
            When creating a new entity in an [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') instantiated with [RandomPids](PidType.md#Friflo.Engine.ECS.PidType.RandomPids 'Friflo.Engine.ECS.PidType.RandomPids')
            it generates a unique random pid assigned to the entity.<br/>
            Using random pids avoid merge conflicts when multiples users make changes to the same [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') file / database.<br/>
            The probability generating the same pid by two different users is:
            

```csharp
p = 1 - exp(-r^2 / (2 * N))
r:  number of new entities added by a user to an existing [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') (not the number of all entities)
N:  number of possible values = int.MaxValue = 2147483647
```
            See: https://en.wikipedia.org/wiki/Birthday_problem

| Properties | |
| :--- | :--- |
| [Archetype](EntityNode.Archetype.md 'Friflo.Engine.ECS.EntityNode.Archetype') | The [Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype') storing the entity. |
| [Flags](EntityNode.Flags.md 'Friflo.Engine.ECS.EntityNode.Flags') | Internally used flags assigned to the entity. |

| Methods | |
| :--- | :--- |
| [ToString()](EntityNode.ToString().md 'Friflo.Engine.ECS.EntityNode.ToString()') | |
