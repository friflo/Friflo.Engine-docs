#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[QueryJob](QueryJob.md#'Friflo.Engine.ECS.QueryJob')

## QueryJob.MinParallelChunkLength Property

The minimum number of [Chunk&lt;T&gt;](Chunk_T_.md#'Friflo.Engine.ECS.Chunk<T>') components per thread required to execute a query [Parallel](JobExecution.md#Friflo.Engine.ECS.JobExecution.Parallel#'Friflo.Engine.ECS.JobExecution.Parallel').<br/>
Default: 1000.

```csharp
public int MinParallelChunkLength { get; set; }
```

#### Property Value
[System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32#'System.Int32')

### Remarks
Parallel query execution adds an overhead of 1 to 2 micro seconds per query for thread synchronization.<br/>
Execution of a simple computation like `health.value++` on a single component takes 0.5 to 1 nano seconds.<br/><br/>
E.g. processing a chunk with 100 components will take 50 to 100 nano seconds.<br/>
So the chunk components are executed [Sequential](JobExecution.md#Friflo.Engine.ECS.JobExecution.Sequential#'Friflo.Engine.ECS.JobExecution.Sequential') to avoid the parallelization overhead.<br/><br/>
For more complex computations [MinParallelChunkLength](QueryJob.MinParallelChunkLength.md#'Friflo.Engine.ECS.QueryJob.MinParallelChunkLength') can be reduced to execute a query
[Parallel](JobExecution.md#Friflo.Engine.ECS.JobExecution.Parallel#'Friflo.Engine.ECS.JobExecution.Parallel') when dealing with a lower number of components.