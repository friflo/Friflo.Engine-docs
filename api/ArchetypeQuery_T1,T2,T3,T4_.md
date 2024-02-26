#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ArchetypeQuery<T1,T2,T3,T4> Class

A query instance use to retrieve the given component types.
See <a href="https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md#query-entities">Example.</a>

```csharp
public sealed class ArchetypeQuery<T1,T2,T3,T4> : Friflo.Engine.ECS.ArchetypeQuery
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T4 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3,T4_.T1'></a>

`T1`

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3,T4_.T2'></a>

`T2`

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3,T4_.T3'></a>

`T3`

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3,T4_.T4'></a>

`T4`

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') &#129106; ArchetypeQuery<T1,T2,T3,T4>

| Properties | |
| :--- | :--- |
| [Chunks](ArchetypeQuery_T1,T2,T3,T4_.Chunks.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>.Chunks') | Return the [Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>')'s storing the components and entities of an [ArchetypeQuery&lt;T1,T2,T3,T4&gt;](ArchetypeQuery_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>').<br/> See <a href="https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md#enumerate-query-chunks">Example.</a> |

| Methods | |
| :--- | :--- |
| [AllComponents(ComponentTypes)](ArchetypeQuery_T1,T2,T3,T4_.AllComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>.AllComponents(Friflo.Engine.ECS.ComponentTypes)') | |
| [AllTags(Tags)](ArchetypeQuery_T1,T2,T3,T4_.AllTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>.AllTags(Friflo.Engine.ECS.Tags)') | |
| [AnyComponents(ComponentTypes)](ArchetypeQuery_T1,T2,T3,T4_.AnyComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>.AnyComponents(Friflo.Engine.ECS.ComponentTypes)') | |
| [AnyTags(Tags)](ArchetypeQuery_T1,T2,T3,T4_.AnyTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>.AnyTags(Friflo.Engine.ECS.Tags)') | |
| [ForEach(Action&lt;Chunk&lt;T1&gt;,Chunk&lt;T2&gt;,Chunk&lt;T3&gt;,Chunk&lt;T4&gt;,ChunkEntities&gt;)](ArchetypeQuery_T1,T2,T3,T4_.ForEach(Action_Chunk_T1_,Chunk_T2_,Chunk_T3_,Chunk_T4_,ChunkEntities_).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>.ForEach(System.Action<Friflo.Engine.ECS.Chunk<T1>,Friflo.Engine.ECS.Chunk<T2>,Friflo.Engine.ECS.Chunk<T3>,Friflo.Engine.ECS.Chunk<T4>,Friflo.Engine.ECS.ChunkEntities>)') | Returns a [QueryJob](QueryJob.md 'Friflo.Engine.ECS.QueryJob') that enables [Parallel](JobExecution.md#Friflo.Engine.ECS.JobExecution.Parallel 'Friflo.Engine.ECS.JobExecution.Parallel') query execution. |
| [ForEachEntity(ForEachEntity&lt;T1,T2,T3,T4&gt;)](ArchetypeQuery_T1,T2,T3,T4_.ForEachEntity(ForEachEntity_T1,T2,T3,T4_).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>.ForEachEntity(Friflo.Engine.ECS.ForEachEntity<T1,T2,T3,T4>)') | Executes the given [lambda](ArchetypeQuery_T1,T2,T3,T4_.ForEachEntity(ForEachEntity_T1,T2,T3,T4_).md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3,T4_.ForEachEntity(Friflo.Engine.ECS.ForEachEntity_T1,T2,T3,T4_).lambda 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>.ForEachEntity(Friflo.Engine.ECS.ForEachEntity<T1,T2,T3,T4>).lambda') for each entity in the query result. |
| [ReadOnly&lt;T&gt;()](ArchetypeQuery_T1,T2,T3,T4_.ReadOnly_T_().md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>.ReadOnly<T>()') | |
| [WithDisabled()](ArchetypeQuery_T1,T2,T3,T4_.WithDisabled().md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>.WithDisabled()') | |
| [WithoutAllComponents(ComponentTypes)](ArchetypeQuery_T1,T2,T3,T4_.WithoutAllComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes)') | |
| [WithoutAllTags(Tags)](ArchetypeQuery_T1,T2,T3,T4_.WithoutAllTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>.WithoutAllTags(Friflo.Engine.ECS.Tags)') | |
| [WithoutAnyComponents(ComponentTypes)](ArchetypeQuery_T1,T2,T3,T4_.WithoutAnyComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>.WithoutAnyComponents(Friflo.Engine.ECS.ComponentTypes)') | |
| [WithoutAnyTags(Tags)](ArchetypeQuery_T1,T2,T3,T4_.WithoutAnyTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>.WithoutAnyTags(Friflo.Engine.ECS.Tags)') | |
