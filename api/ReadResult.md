#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Serialize](Friflo.Engine.ECS.Serialize.md 'Friflo.Engine.ECS.Serialize')

## ReadResult Struct

Contains the aggregated result when reading entities with an [EntitySerializer](EntitySerializer.md 'Friflo.Engine.ECS.Serialize.EntitySerializer').

```csharp
public readonly struct ReadResult
```

| Fields | |
| :--- | :--- |
| [entityCount](ReadResult.entityCount.md 'Friflo.Engine.ECS.Serialize.ReadResult.entityCount') | Number of entities returned by an [EntitySerializer](EntitySerializer.md 'Friflo.Engine.ECS.Serialize.EntitySerializer')`Read` method. |
| [error](ReadResult.error.md 'Friflo.Engine.ECS.Serialize.ReadResult.error') | null - if reading entities was successful.<br/> Otherwise the error of an [EntitySerializer](EntitySerializer.md 'Friflo.Engine.ECS.Serialize.EntitySerializer')`Read` method call. |

| Methods | |
| :--- | :--- |
| [ToString()](ReadResult.ToString().md 'Friflo.Engine.ECS.Serialize.ReadResult.ToString()') | |
