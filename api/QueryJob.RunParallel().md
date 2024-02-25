#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[QueryJob](QueryJob.md#'Friflo.Engine.ECS.QueryJob')

## QueryJob.RunParallel() Method

Execute the query.
            See <a href="https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md#parallel-query-job">Example.</a>.<br/>
            All chunks having at least [MinParallelChunkLength](QueryJob.MinParallelChunkLength.md#'Friflo.Engine.ECS.QueryJob.MinParallelChunkLength') * [ThreadCount](ParallelJobRunner.ThreadCount.md#'Friflo.Engine.ECS.ParallelJobRunner.ThreadCount')
            components are executed [Parallel](JobExecution.md#Friflo.Engine.ECS.JobExecution.Parallel#'Friflo.Engine.ECS.JobExecution.Parallel').

```csharp
public abstract void RunParallel();
```

#### Exceptions

[System.InvalidOperationException](https://docs.microsoft.com/en-us/dotnet/api/System.InvalidOperationException#'System.InvalidOperationException')  
If the [JobRunner](QueryJob.JobRunner.md#'Friflo.Engine.ECS.QueryJob.JobRunner') is not set.

[System.InvalidOperationException](https://docs.microsoft.com/en-us/dotnet/api/System.InvalidOperationException#'System.InvalidOperationException')  
If a nested [RunParallel()](QueryJob.RunParallel().md#'Friflo.Engine.ECS.QueryJob.RunParallel()') is using the same [JobRunner](QueryJob.JobRunner.md#'Friflo.Engine.ECS.QueryJob.JobRunner') as the enclosing job.

### Remarks
Requires an [ParallelJobRunner](ParallelJobRunner.md#'Friflo.Engine.ECS.ParallelJobRunner').<br/>
A runner can be assigned to [JobRunner](QueryJob.JobRunner.md#'Friflo.Engine.ECS.QueryJob.JobRunner') or to the [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore').