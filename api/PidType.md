#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS')

## PidType Enum

Specify the way how an [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore') generates entity [Pid](Entity.Pid.md#'Friflo.Engine.ECS.Entity.Pid')'s.

```csharp
public enum PidType
```
### Fields

<a name='Friflo.Engine.ECS.PidType.RandomPids'></a>

`RandomPids` 1

Map random [Pid](Entity.Pid.md#'Friflo.Engine.ECS.Entity.Pid')'s to [Id](Entity.Id.md#'Friflo.Engine.ECS.Entity.Id')'s used within the engine at runtime.<br/>
This method is intended to be used to store entities of an [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore') in JSON files or in a database.

<a name='Friflo.Engine.ECS.PidType.UsePidAsId'></a>

`UsePidAsId` 0

Used to simplify testing as the pid and id of an entity are equal.<br/>
It also increases performance in case ids are consecutively.<br/>
This method is <b>not</b> intended to be used to store entities of an [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore')
in JSON files or in a database.<br/>

### Remarks
Disadvantages:<br/>
- Big gaps between ids are wasted memory.<br/>
- When add entities in a database id clashes with entities added by other users are very likely.<br/>
- High probability of merge conflicts caused by id clashes by adding the same entity ids by multiple users.