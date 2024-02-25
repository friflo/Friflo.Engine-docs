#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS')

## JobExecution Enum

Specify the way how [ChunkEntities](ChunkEntities.md#'Friflo.Engine.ECS.ChunkEntities') are provided by either a `foreach` loop,
[Run()](QueryJob.Run().md#'Friflo.Engine.ECS.QueryJob.Run()') or [RunParallel()](QueryJob.RunParallel().md#'Friflo.Engine.ECS.QueryJob.RunParallel()').

```csharp
public enum JobExecution : System.Byte
```
### Fields

<a name='Friflo.Engine.ECS.JobExecution.Parallel'></a>

`Parallel` 1

[ChunkEntities](ChunkEntities.md#'Friflo.Engine.ECS.ChunkEntities') are provided by a [RunParallel()](QueryJob.RunParallel().md#'Friflo.Engine.ECS.QueryJob.RunParallel()').

<a name='Friflo.Engine.ECS.JobExecution.Sequential'></a>

`Sequential` 0

[ChunkEntities](ChunkEntities.md#'Friflo.Engine.ECS.ChunkEntities') are provided by a `foreach` loop or [Run()](QueryJob.Run().md#'Friflo.Engine.ECS.QueryJob.Run()').