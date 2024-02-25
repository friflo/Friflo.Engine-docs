#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS')

## QueryJob<T1,T2,T3> Class

Enables [Parallel](JobExecution.md#Friflo.Engine.ECS.JobExecution.Parallel#'Friflo.Engine.ECS.JobExecution.Parallel') query execution returning the specified components.
See <a href="https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md#parallel-query-job">Example.</a>

```csharp
public sealed class QueryJob<T1,T2,T3> : Friflo.Engine.ECS.QueryJob
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.QueryJob_T1,T2,T3_.T1'></a>

`T1`

<a name='Friflo.Engine.ECS.QueryJob_T1,T2,T3_.T2'></a>

`T2`

<a name='Friflo.Engine.ECS.QueryJob_T1,T2,T3_.T3'></a>

`T3`

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object#'System.Object') &#129106; [QueryJob](QueryJob.md#'Friflo.Engine.ECS.QueryJob') &#129106; QueryJob<T1,T2,T3>

| Properties | |
| :--- | :--- |
| [ParallelComponentMultiple](QueryJob_T1,T2,T3_.ParallelComponentMultiple.md#'Friflo.Engine.ECS.QueryJob<T1,T2,T3>.ParallelComponentMultiple') | |

| Methods | |
| :--- | :--- |
| [Run()](QueryJob_T1,T2,T3_.Run().md#'Friflo.Engine.ECS.QueryJob<T1,T2,T3>.Run()') | |
| [RunParallel()](QueryJob_T1,T2,T3_.RunParallel().md#'Friflo.Engine.ECS.QueryJob<T1,T2,T3>.RunParallel()') | Execute the query.             See <a href="https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md#parallel-query-job">Example.</a>.<br/>             All chunks having at least [MinParallelChunkLength](QueryJob.MinParallelChunkLength.md#'Friflo.Engine.ECS.QueryJob.MinParallelChunkLength') * [ThreadCount](ParallelJobRunner.ThreadCount.md#'Friflo.Engine.ECS.ParallelJobRunner.ThreadCount')             components are executed [Parallel](JobExecution.md#Friflo.Engine.ECS.JobExecution.Parallel#'Friflo.Engine.ECS.JobExecution.Parallel'). |
| [ToString()](QueryJob_T1,T2,T3_.ToString().md#'Friflo.Engine.ECS.QueryJob<T1,T2,T3>.ToString()') | |
