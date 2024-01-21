#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## UniqueEntity Struct

A [UniqueEntity](UniqueEntity.md 'Friflo.Engine.ECS.UniqueEntity') is used to assign a unique `string` to an entity within an [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore').

```csharp
public struct UniqueEntity :
Friflo.Engine.ECS.IComponent
```

Implements [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')

### Remarks
To find a [UniqueEntity](UniqueEntity.md 'Friflo.Engine.ECS.UniqueEntity') within an [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') use [GetUniqueEntity(string)](EntityStoreBase.GetUniqueEntity(string).md 'Friflo.Engine.ECS.EntityStoreBase.GetUniqueEntity(string)').<br/>
It basically acts as a singleton within an [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore').

| Constructors | |
| :--- | :--- |
| [UniqueEntity(string)](UniqueEntity.UniqueEntity(string).md 'Friflo.Engine.ECS.UniqueEntity.UniqueEntity(string)') | |

| Fields | |
| :--- | :--- |
| [uid](UniqueEntity.uid.md 'Friflo.Engine.ECS.UniqueEntity.uid') | Unique string identifier assigned to specific [Entity](Entity.md 'Friflo.Engine.ECS.Entity') |

| Methods | |
| :--- | :--- |
| [ToString()](UniqueEntity.ToString().md 'Friflo.Engine.ECS.UniqueEntity.ToString()') | |
