#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[ArchetypeQuery&lt;T1&gt;](ArchetypeQuery_T1_.md#'Friflo.Engine.ECS.ArchetypeQuery<T1>')

## ArchetypeQuery<T1>.ForEach(Action<Chunk<T1>,ChunkEntities>) Method

Returns a [QueryJob](QueryJob.md#'Friflo.Engine.ECS.QueryJob') that enables [Parallel](JobExecution.md#Friflo.Engine.ECS.JobExecution.Parallel#'Friflo.Engine.ECS.JobExecution.Parallel') query execution.

```csharp
public Friflo.Engine.ECS.QueryJob<T1> ForEach(System.Action<Friflo.Engine.ECS.Chunk<T1>,Friflo.Engine.ECS.ChunkEntities> action);
```
#### Parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1_.ForEach(System.Action_Friflo.Engine.ECS.Chunk_T1_,Friflo.Engine.ECS.ChunkEntities_).action'></a>

`action` [System.Action&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-2#'System.Action`2')[Friflo.Engine.ECS.Chunk&lt;](Chunk_T_.md#'Friflo.Engine.ECS.Chunk<T>')[T1](ArchetypeQuery_T1_.md#Friflo.Engine.ECS.ArchetypeQuery_T1_.T1#'Friflo.Engine.ECS.ArchetypeQuery<T1>.T1')[&gt;](Chunk_T_.md#'Friflo.Engine.ECS.Chunk<T>')[,](https://docs.microsoft.com/en-us/dotnet/api/System.Action-2#'System.Action`2')[ChunkEntities](ChunkEntities.md#'Friflo.Engine.ECS.ChunkEntities')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-2#'System.Action`2')

#### Returns
[Friflo.Engine.ECS.QueryJob&lt;](QueryJob_T1_.md#'Friflo.Engine.ECS.QueryJob<T1>')[T1](ArchetypeQuery_T1_.md#Friflo.Engine.ECS.ArchetypeQuery_T1_.T1#'Friflo.Engine.ECS.ArchetypeQuery<T1>.T1')[&gt;](QueryJob_T1_.md#'Friflo.Engine.ECS.QueryJob<T1>')