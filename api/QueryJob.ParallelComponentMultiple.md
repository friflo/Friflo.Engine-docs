#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[QueryJob](QueryJob.md 'Friflo.Engine.ECS.QueryJob')

## QueryJob.ParallelComponentMultiple Property

The [ParallelComponentMultiple](QueryJob.ParallelComponentMultiple.md 'Friflo.Engine.ECS.QueryJob.ParallelComponentMultiple') is used to align the [Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>') components length 
of a [Parallel](JobExecution.md#Friflo.Engine.ECS.JobExecution.Parallel 'Friflo.Engine.ECS.JobExecution.Parallel') executed component chunks.

```csharp
public abstract int ParallelComponentMultiple { get; }
```

#### Property Value
[System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

### Remarks
This enables vectorization of the components without a remainder loop using<br/>[AsSpan128&lt;TTo&gt;()](Chunk_T_.AsSpan128_TTo_().md 'Friflo.Engine.ECS.Chunk<T>.AsSpan128<TTo>()'), [AsSpan256&lt;TTo&gt;()](Chunk_T_.AsSpan256_TTo_().md 'Friflo.Engine.ECS.Chunk<T>.AsSpan256<TTo>()') or [AsSpan512&lt;TTo&gt;()](Chunk_T_.AsSpan512_TTo_().md 'Friflo.Engine.ECS.Chunk<T>.AsSpan512<TTo>()').