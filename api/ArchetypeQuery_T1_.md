#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ArchetypeQuery<T1> Class

A query instance use to retrieve the given component types.
See <a href="https://friflo.gitbook.io/friflo.engine.ecs/examples/general#query-entities">Example.</a>

```csharp
public sealed class ArchetypeQuery<T1> : Friflo.Engine.ECS.ArchetypeQuery
    where T1 : struct, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1_.T1'></a>

`T1`

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') &#129106; ArchetypeQuery<T1>

| Properties | |
| :--- | :--- |
| [Chunks](ArchetypeQuery_T1_.Chunks.md 'Friflo.Engine.ECS.ArchetypeQuery<T1>.Chunks') | Return the [Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>')'s storing the components and entities of an [ArchetypeQuery&lt;T1&gt;](ArchetypeQuery_T1_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1>').<br/> See <a href="https://friflo.gitbook.io/friflo.engine.ecs/examples/optimization#enumerate-query-chunks">Example.</a> |

| Methods | |
| :--- | :--- |
| [AllComponents(ComponentTypes)](ArchetypeQuery_T1_.AllComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery<T1>.AllComponents(Friflo.Engine.ECS.ComponentTypes)') | A query result will contain only entities having all passed [componentTypes](ArchetypeQuery_T1_.AllComponents(ComponentTypes).md#Friflo.Engine.ECS.ArchetypeQuery_T1_.AllComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes 'Friflo.Engine.ECS.ArchetypeQuery<T1>.AllComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes'). |
| [AllTags(Tags)](ArchetypeQuery_T1_.AllTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery<T1>.AllTags(Friflo.Engine.ECS.Tags)') | A query result will contain only entities having all passed [tags](ArchetypeQuery_T1_.AllTags(Tags).md#Friflo.Engine.ECS.ArchetypeQuery_T1_.AllTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.ArchetypeQuery<T1>.AllTags(Friflo.Engine.ECS.Tags).tags'). |
| [AnyComponents(ComponentTypes)](ArchetypeQuery_T1_.AnyComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery<T1>.AnyComponents(Friflo.Engine.ECS.ComponentTypes)') | A query result will contain only entities having any of the the passed [componentTypes](ArchetypeQuery_T1_.AnyComponents(ComponentTypes).md#Friflo.Engine.ECS.ArchetypeQuery_T1_.AnyComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes 'Friflo.Engine.ECS.ArchetypeQuery<T1>.AnyComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes'). |
| [AnyTags(Tags)](ArchetypeQuery_T1_.AnyTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery<T1>.AnyTags(Friflo.Engine.ECS.Tags)') | A query result will contain only entities having any of the the passed [tags](ArchetypeQuery_T1_.AnyTags(Tags).md#Friflo.Engine.ECS.ArchetypeQuery_T1_.AnyTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.ArchetypeQuery<T1>.AnyTags(Friflo.Engine.ECS.Tags).tags'). |
| [ForEach(Action&lt;Chunk&lt;T1&gt;,ChunkEntities&gt;)](ArchetypeQuery_T1_.ForEach(Action_Chunk_T1_,ChunkEntities_).md 'Friflo.Engine.ECS.ArchetypeQuery<T1>.ForEach(System.Action<Friflo.Engine.ECS.Chunk<T1>,Friflo.Engine.ECS.ChunkEntities>)') | Returns a [QueryJob](QueryJob.md 'Friflo.Engine.ECS.QueryJob') that enables [Parallel](JobExecution.md#Friflo.Engine.ECS.JobExecution.Parallel 'Friflo.Engine.ECS.JobExecution.Parallel') query execution. |
| [ForEachEntity(ForEachEntity&lt;T1&gt;)](ArchetypeQuery_T1_.ForEachEntity(ForEachEntity_T1_).md 'Friflo.Engine.ECS.ArchetypeQuery<T1>.ForEachEntity(Friflo.Engine.ECS.ForEachEntity<T1>)') | Executes the given [lambda](ArchetypeQuery_T1_.ForEachEntity(ForEachEntity_T1_).md#Friflo.Engine.ECS.ArchetypeQuery_T1_.ForEachEntity(Friflo.Engine.ECS.ForEachEntity_T1_).lambda 'Friflo.Engine.ECS.ArchetypeQuery<T1>.ForEachEntity(Friflo.Engine.ECS.ForEachEntity<T1>).lambda') for each entity in the query result. |
| [FreezeFilter()](ArchetypeQuery_T1_.FreezeFilter().md 'Friflo.Engine.ECS.ArchetypeQuery<T1>.FreezeFilter()') | The query [Filter](ArchetypeQuery.Filter.md 'Friflo.Engine.ECS.ArchetypeQuery.Filter') cannot be changed anymore. |
| [HasValue&lt;TComponent,TValue&gt;(TValue)](ArchetypeQuery_T1_.HasValue_TComponent,TValue_(TValue).md 'Friflo.Engine.ECS.ArchetypeQuery<T1>.HasValue<TComponent,TValue>(TValue)') | Include entities having a component with the specified value.<br/> Executes in O(1). |
| [ValueInRange&lt;TComponent,TValue&gt;(TValue, TValue)](ArchetypeQuery_T1_.ValueInRange_TComponent,TValue_(TValue,TValue).md 'Friflo.Engine.ECS.ArchetypeQuery<T1>.ValueInRange<TComponent,TValue>(TValue, TValue)') | Include entities having a component value in the specified range.<br/> Executes O(N ⋅ log N) N: all unique values. |
| [WithDisabled()](ArchetypeQuery_T1_.WithDisabled().md 'Friflo.Engine.ECS.ArchetypeQuery<T1>.WithDisabled()') | A query result will contain [Disabled](Disabled.md 'Friflo.Engine.ECS.Disabled') entities. |
| [WithoutAllComponents(ComponentTypes)](ArchetypeQuery_T1_.WithoutAllComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery<T1>.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes)') | Entities having all passed [componentTypes](ArchetypeQuery_T1_.WithoutAllComponents(ComponentTypes).md#Friflo.Engine.ECS.ArchetypeQuery_T1_.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes 'Friflo.Engine.ECS.ArchetypeQuery<T1>.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes') are excluded from query result. |
| [WithoutAllTags(Tags)](ArchetypeQuery_T1_.WithoutAllTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery<T1>.WithoutAllTags(Friflo.Engine.ECS.Tags)') | Entities having all passed [tags](ArchetypeQuery_T1_.WithoutAllTags(Tags).md#Friflo.Engine.ECS.ArchetypeQuery_T1_.WithoutAllTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.ArchetypeQuery<T1>.WithoutAllTags(Friflo.Engine.ECS.Tags).tags') are excluded from query result. |
| [WithoutAnyComponents(ComponentTypes)](ArchetypeQuery_T1_.WithoutAnyComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery<T1>.WithoutAnyComponents(Friflo.Engine.ECS.ComponentTypes)') | Entities having any of the passed [componentTypes](ArchetypeQuery_T1_.WithoutAnyComponents(ComponentTypes).md#Friflo.Engine.ECS.ArchetypeQuery_T1_.WithoutAnyComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes 'Friflo.Engine.ECS.ArchetypeQuery<T1>.WithoutAnyComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes') are excluded from query result. |
| [WithoutAnyTags(Tags)](ArchetypeQuery_T1_.WithoutAnyTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery<T1>.WithoutAnyTags(Friflo.Engine.ECS.Tags)') | Entities having any of the passed [tags](ArchetypeQuery_T1_.WithoutAnyTags(Tags).md#Friflo.Engine.ECS.ArchetypeQuery_T1_.WithoutAnyTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.ArchetypeQuery<T1>.WithoutAnyTags(Friflo.Engine.ECS.Tags).tags') are excluded from query result. |
