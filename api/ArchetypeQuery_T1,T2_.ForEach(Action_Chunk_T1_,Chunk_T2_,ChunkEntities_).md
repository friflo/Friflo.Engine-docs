#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[ArchetypeQuery&lt;T1,T2&gt;](ArchetypeQuery_T1,T2_.md#'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>')

## ArchetypeQuery<T1,T2>.ForEach(Action<Chunk<T1>,Chunk<T2>,ChunkEntities>) Method

Returns a [QueryJob](QueryJob.md#'Friflo.Engine.ECS.QueryJob') that enables [Parallel](JobExecution.md#Friflo.Engine.ECS.JobExecution.Parallel#'Friflo.Engine.ECS.JobExecution.Parallel') query execution.

```csharp
public Friflo.Engine.ECS.QueryJob<T1,T2> ForEach(System.Action<Friflo.Engine.ECS.Chunk<T1>,Friflo.Engine.ECS.Chunk<T2>,Friflo.Engine.ECS.ChunkEntities> action);
```
#### Parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2_.ForEach(System.Action_Friflo.Engine.ECS.Chunk_T1_,Friflo.Engine.ECS.Chunk_T2_,Friflo.Engine.ECS.ChunkEntities_).action'></a>

`action` [System.Action&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-3#'System.Action`3')[Friflo.Engine.ECS.Chunk&lt;](Chunk_T_.md#'Friflo.Engine.ECS.Chunk<T>')[T1](ArchetypeQuery_T1,T2_.md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2_.T1#'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>.T1')[&gt;](Chunk_T_.md#'Friflo.Engine.ECS.Chunk<T>')[,](https://docs.microsoft.com/en-us/dotnet/api/System.Action-3#'System.Action`3')[Friflo.Engine.ECS.Chunk&lt;](Chunk_T_.md#'Friflo.Engine.ECS.Chunk<T>')[T2](ArchetypeQuery_T1,T2_.md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2_.T2#'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>.T2')[&gt;](Chunk_T_.md#'Friflo.Engine.ECS.Chunk<T>')[,](https://docs.microsoft.com/en-us/dotnet/api/System.Action-3#'System.Action`3')[ChunkEntities](ChunkEntities.md#'Friflo.Engine.ECS.ChunkEntities')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-3#'System.Action`3')

#### Returns
[Friflo.Engine.ECS.QueryJob&lt;](QueryJob_T1,T2_.md#'Friflo.Engine.ECS.QueryJob<T1,T2>')[T1](ArchetypeQuery_T1,T2_.md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2_.T1#'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>.T1')[,](QueryJob_T1,T2_.md#'Friflo.Engine.ECS.QueryJob<T1,T2>')[T2](ArchetypeQuery_T1,T2_.md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2_.T2#'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>.T2')[&gt;](QueryJob_T1,T2_.md#'Friflo.Engine.ECS.QueryJob<T1,T2>')