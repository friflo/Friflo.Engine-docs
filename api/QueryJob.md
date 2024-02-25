#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS')

## QueryJob Class

A [QueryJob](QueryJob.md#'Friflo.Engine.ECS.QueryJob') enables [Parallel](JobExecution.md#Friflo.Engine.ECS.JobExecution.Parallel#'Friflo.Engine.ECS.JobExecution.Parallel') query execution using multiple threads
to reduce execution time of large queries.<br/>
They are created by the `ArchetypeQuery.ForEach()` methods.

```csharp
public abstract class QueryJob
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object#'System.Object') &#129106; QueryJob

Derived  
&#8627; [QueryJob&lt;T1,T2,T3,T4,T5&gt;](QueryJob_T1,T2,T3,T4,T5_.md#'Friflo.Engine.ECS.QueryJob<T1,T2,T3,T4,T5>')  
&#8627; [QueryJob&lt;T1,T2,T3,T4&gt;](QueryJob_T1,T2,T3,T4_.md#'Friflo.Engine.ECS.QueryJob<T1,T2,T3,T4>')  
&#8627; [QueryJob&lt;T1,T2,T3&gt;](QueryJob_T1,T2,T3_.md#'Friflo.Engine.ECS.QueryJob<T1,T2,T3>')  
&#8627; [QueryJob&lt;T1,T2&gt;](QueryJob_T1,T2_.md#'Friflo.Engine.ECS.QueryJob<T1,T2>')  
&#8627; [QueryJob&lt;T1&gt;](QueryJob_T1_.md#'Friflo.Engine.ECS.QueryJob<T1>')

### Remarks
To execute a query job [Sequential](JobExecution.md#Friflo.Engine.ECS.JobExecution.Sequential#'Friflo.Engine.ECS.JobExecution.Sequential') use the [Run()](QueryJob.Run().md#'Friflo.Engine.ECS.QueryJob.Run()') method.<br/>
To execute a query job [Parallel](JobExecution.md#Friflo.Engine.ECS.JobExecution.Parallel#'Friflo.Engine.ECS.JobExecution.Parallel') use the [RunParallel()](QueryJob.RunParallel().md#'Friflo.Engine.ECS.QueryJob.RunParallel()') method.

| Properties | |
| :--- | :--- |
| [JobRunner](QueryJob.JobRunner.md#'Friflo.Engine.ECS.QueryJob.JobRunner') | The job runner used to execute a query [Parallel](JobExecution.md#Friflo.Engine.ECS.JobExecution.Parallel#'Friflo.Engine.ECS.JobExecution.Parallel'). |
| [MinParallelChunkLength](QueryJob.MinParallelChunkLength.md#'Friflo.Engine.ECS.QueryJob.MinParallelChunkLength') | The minimum number of [Chunk&lt;T&gt;](Chunk_T_.md#'Friflo.Engine.ECS.Chunk<T>') components per thread required to execute a query [Parallel](JobExecution.md#Friflo.Engine.ECS.JobExecution.Parallel#'Friflo.Engine.ECS.JobExecution.Parallel').<br/> Default: 1000. |
| [ParallelComponentMultiple](QueryJob.ParallelComponentMultiple.md#'Friflo.Engine.ECS.QueryJob.ParallelComponentMultiple') | The [ParallelComponentMultiple](QueryJob.ParallelComponentMultiple.md#'Friflo.Engine.ECS.QueryJob.ParallelComponentMultiple') is used to align the [Chunk&lt;T&gt;](Chunk_T_.md#'Friflo.Engine.ECS.Chunk<T>') components length  of a [Parallel](JobExecution.md#Friflo.Engine.ECS.JobExecution.Parallel#'Friflo.Engine.ECS.JobExecution.Parallel') executed component chunks. |

| Methods | |
| :--- | :--- |
| [Run()](QueryJob.Run().md#'Friflo.Engine.ECS.QueryJob.Run()') | Execute the query [Sequential](JobExecution.md#Friflo.Engine.ECS.JobExecution.Sequential#'Friflo.Engine.ECS.JobExecution.Sequential'). |
| [RunParallel()](QueryJob.RunParallel().md#'Friflo.Engine.ECS.QueryJob.RunParallel()') | Execute the query.             See <a href="https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md#parallel-query-job">Example.</a>.<br/>             All chunks having at least [MinParallelChunkLength](QueryJob.MinParallelChunkLength.md#'Friflo.Engine.ECS.QueryJob.MinParallelChunkLength') * [ThreadCount](ParallelJobRunner.ThreadCount.md#'Friflo.Engine.ECS.ParallelJobRunner.ThreadCount')             components are executed [Parallel](JobExecution.md#Friflo.Engine.ECS.JobExecution.Parallel#'Friflo.Engine.ECS.JobExecution.Parallel'). |
