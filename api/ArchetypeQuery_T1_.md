#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS')

## ArchetypeQuery<T1> Class

A query instance use to retrieve the given component types.
See <a href="https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md#query-entities">Example.</a>

```csharp
public sealed class ArchetypeQuery<T1> : Friflo.Engine.ECS.ArchetypeQuery
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1_.T1'></a>

`T1`

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object#'System.Object') &#129106; [ArchetypeQuery](ArchetypeQuery.md#'Friflo.Engine.ECS.ArchetypeQuery') &#129106; ArchetypeQuery<T1>

| Properties | |
| :--- | :--- |
| [Chunks](ArchetypeQuery_T1_.Chunks.md#'Friflo.Engine.ECS.ArchetypeQuery<T1>.Chunks') | Return the [Chunk&lt;T&gt;](Chunk_T_.md#'Friflo.Engine.ECS.Chunk<T>')'s storing the components and entities of an [ArchetypeQuery&lt;T1&gt;](ArchetypeQuery_T1_.md#'Friflo.Engine.ECS.ArchetypeQuery<T1>').<br/> See <a href="https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md#enumerate-query-chunks">Example.</a> |

| Methods | |
| :--- | :--- |
| [AllComponents(ComponentTypes)](ArchetypeQuery_T1_.AllComponents(ComponentTypes).md#'Friflo.Engine.ECS.ArchetypeQuery<T1>.AllComponents(Friflo.Engine.ECS.ComponentTypes)') | |
| [AllTags(Tags)](ArchetypeQuery_T1_.AllTags(Tags).md#'Friflo.Engine.ECS.ArchetypeQuery<T1>.AllTags(Friflo.Engine.ECS.Tags)') | |
| [AnyComponents(ComponentTypes)](ArchetypeQuery_T1_.AnyComponents(ComponentTypes).md#'Friflo.Engine.ECS.ArchetypeQuery<T1>.AnyComponents(Friflo.Engine.ECS.ComponentTypes)') | |
| [AnyTags(Tags)](ArchetypeQuery_T1_.AnyTags(Tags).md#'Friflo.Engine.ECS.ArchetypeQuery<T1>.AnyTags(Friflo.Engine.ECS.Tags)') | |
| [ForEach(Action&lt;Chunk&lt;T1&gt;,ChunkEntities&gt;)](ArchetypeQuery_T1_.ForEach(Action_Chunk_T1_,ChunkEntities_).md#'Friflo.Engine.ECS.ArchetypeQuery<T1>.ForEach(System.Action<Friflo.Engine.ECS.Chunk<T1>,Friflo.Engine.ECS.ChunkEntities>)') | Returns a [QueryJob](QueryJob.md#'Friflo.Engine.ECS.QueryJob') that enables [Parallel](JobExecution.md#Friflo.Engine.ECS.JobExecution.Parallel#'Friflo.Engine.ECS.JobExecution.Parallel') query execution. |
| [ReadOnly&lt;T&gt;()](ArchetypeQuery_T1_.ReadOnly_T_().md#'Friflo.Engine.ECS.ArchetypeQuery<T1>.ReadOnly<T>()') | |
| [WithDisabled()](ArchetypeQuery_T1_.WithDisabled().md#'Friflo.Engine.ECS.ArchetypeQuery<T1>.WithDisabled()') | |
| [WithoutAllComponents(ComponentTypes)](ArchetypeQuery_T1_.WithoutAllComponents(ComponentTypes).md#'Friflo.Engine.ECS.ArchetypeQuery<T1>.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes)') | |
| [WithoutAllTags(Tags)](ArchetypeQuery_T1_.WithoutAllTags(Tags).md#'Friflo.Engine.ECS.ArchetypeQuery<T1>.WithoutAllTags(Friflo.Engine.ECS.Tags)') | |
| [WithoutAnyComponents(ComponentTypes)](ArchetypeQuery_T1_.WithoutAnyComponents(ComponentTypes).md#'Friflo.Engine.ECS.ArchetypeQuery<T1>.WithoutAnyComponents(Friflo.Engine.ECS.ComponentTypes)') | |
| [WithoutAnyTags(Tags)](ArchetypeQuery_T1_.WithoutAnyTags(Tags).md#'Friflo.Engine.ECS.ArchetypeQuery<T1>.WithoutAnyTags(Friflo.Engine.ECS.Tags)') | |
