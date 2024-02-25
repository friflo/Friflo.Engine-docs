#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[QueryJob&lt;T1,T2&gt;](QueryJob_T1,T2_.md#'Friflo.Engine.ECS.QueryJob<T1,T2>')

## QueryJob<T1,T2>.RunParallel() Method

Execute the query.
            See <a href="https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md#parallel-query-job">Example.</a>.<br/>
            All chunks having at least [MinParallelChunkLength](QueryJob.MinParallelChunkLength.md#'Friflo.Engine.ECS.QueryJob.MinParallelChunkLength') * [ThreadCount](ParallelJobRunner.ThreadCount.md#'Friflo.Engine.ECS.ParallelJobRunner.ThreadCount')
            components are executed [Parallel](JobExecution.md#Friflo.Engine.ECS.JobExecution.Parallel#'Friflo.Engine.ECS.JobExecution.Parallel').

```csharp
public override void RunParallel();
```