#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## QueryJob<T1> Class

Enables [Parallel](JobExecution.md#Friflo.Engine.ECS.JobExecution.Parallel 'Friflo.Engine.ECS.JobExecution.Parallel') query execution returning the specified components.
See <a href="https://friflo.gitbook.io/friflo.engine.ecs/examples/optimization#parallel-query-job">Example.</a>

```csharp
public sealed class QueryJob<T1> : Friflo.Engine.ECS.QueryJob
    where T1 : struct, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.QueryJob_T1_.T1'></a>

`T1`

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; [QueryJob](QueryJob.md 'Friflo.Engine.ECS.QueryJob') &#129106; QueryJob<T1>

| Properties | |
| :--- | :--- |
| [ParallelComponentMultiple](QueryJob_T1_.ParallelComponentMultiple.md 'Friflo.Engine.ECS.QueryJob<T1>.ParallelComponentMultiple') | |

| Methods | |
| :--- | :--- |
| [Run()](QueryJob_T1_.Run().md 'Friflo.Engine.ECS.QueryJob<T1>.Run()') | |
| [RunParallel()](QueryJob_T1_.RunParallel().md 'Friflo.Engine.ECS.QueryJob<T1>.RunParallel()') | Execute the query.             See <a href="https://friflo.gitbook.io/friflo.engine.ecs/examples/optimization#parallel-query-job">Example.</a>.<br/>             All chunks having at least [MinParallelChunkLength](QueryJob.MinParallelChunkLength.md 'Friflo.Engine.ECS.QueryJob.MinParallelChunkLength') * [ThreadCount](ParallelJobRunner.ThreadCount.md 'Friflo.Engine.ECS.ParallelJobRunner.ThreadCount')             components are executed [Parallel](JobExecution.md#Friflo.Engine.ECS.JobExecution.Parallel 'Friflo.Engine.ECS.JobExecution.Parallel'). |
| [ToString()](QueryJob_T1_.ToString().md 'Friflo.Engine.ECS.QueryJob<T1>.ToString()') | |
