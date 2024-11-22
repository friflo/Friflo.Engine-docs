#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ArchetypeQuery<T1,T2,T3> Class

A query instance use to retrieve the given component types.
See <a href="https://friflo.gitbook.io/friflo.engine.ecs/examples/general#query-entities">Example.</a>

```csharp
public sealed class ArchetypeQuery<T1,T2,T3> : Friflo.Engine.ECS.ArchetypeQuery
    where T1 : struct, System.ValueType, System.ValueType
    where T2 : struct, System.ValueType, System.ValueType
    where T3 : struct, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3_.T1'></a>

`T1`

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3_.T2'></a>

`T2`

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3_.T3'></a>

`T3`

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') &#129106; ArchetypeQuery<T1,T2,T3>

| Properties | |
| :--- | :--- |
| [Chunks](ArchetypeQuery_T1,T2,T3_.Chunks.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.Chunks') | Return the [Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>')'s storing the components and entities of an [ArchetypeQuery&lt;T1,T2,T3&gt;](ArchetypeQuery_T1,T2,T3_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>').<br/> See <a href="https://friflo.gitbook.io/friflo.engine.ecs/examples/optimization#enumerate-query-chunks">Example.</a> |

| Methods | |
| :--- | :--- |
| [AllComponents(ComponentTypes)](ArchetypeQuery_T1,T2,T3_.AllComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.AllComponents(Friflo.Engine.ECS.ComponentTypes)') | A query result will contain only entities having all passed [componentTypes](ArchetypeQuery_T1,T2,T3_.AllComponents(ComponentTypes).md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3_.AllComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.AllComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes'). |
| [AllTags(Tags)](ArchetypeQuery_T1,T2,T3_.AllTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.AllTags(Friflo.Engine.ECS.Tags)') | A query result will contain only entities having all passed [tags](ArchetypeQuery_T1,T2,T3_.AllTags(Tags).md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3_.AllTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.AllTags(Friflo.Engine.ECS.Tags).tags'). |
| [AnyComponents(ComponentTypes)](ArchetypeQuery_T1,T2,T3_.AnyComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.AnyComponents(Friflo.Engine.ECS.ComponentTypes)') | A query result will contain only entities having any of the the passed [componentTypes](ArchetypeQuery_T1,T2,T3_.AnyComponents(ComponentTypes).md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3_.AnyComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.AnyComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes'). |
| [AnyTags(Tags)](ArchetypeQuery_T1,T2,T3_.AnyTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.AnyTags(Friflo.Engine.ECS.Tags)') | A query result will contain only entities having any of the the passed [tags](ArchetypeQuery_T1,T2,T3_.AnyTags(Tags).md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3_.AnyTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.AnyTags(Friflo.Engine.ECS.Tags).tags'). |
| [ForEach(Action&lt;Chunk&lt;T1&gt;,Chunk&lt;T2&gt;,Chunk&lt;T3&gt;,ChunkEntities&gt;)](ArchetypeQuery_T1,T2,T3_.ForEach(Action_Chunk_T1_,Chunk_T2_,Chunk_T3_,ChunkEntities_).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.ForEach(System.Action<Friflo.Engine.ECS.Chunk<T1>,Friflo.Engine.ECS.Chunk<T2>,Friflo.Engine.ECS.Chunk<T3>,Friflo.Engine.ECS.ChunkEntities>)') | Returns a [QueryJob](QueryJob.md 'Friflo.Engine.ECS.QueryJob') that enables [Parallel](JobExecution.md#Friflo.Engine.ECS.JobExecution.Parallel 'Friflo.Engine.ECS.JobExecution.Parallel') query execution. |
| [ForEachEntity(ForEachEntity&lt;T1,T2,T3&gt;)](ArchetypeQuery_T1,T2,T3_.ForEachEntity(ForEachEntity_T1,T2,T3_).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.ForEachEntity(Friflo.Engine.ECS.ForEachEntity<T1,T2,T3>)') | Executes the given [lambda](ArchetypeQuery_T1,T2,T3_.ForEachEntity(ForEachEntity_T1,T2,T3_).md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3_.ForEachEntity(Friflo.Engine.ECS.ForEachEntity_T1,T2,T3_).lambda 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.ForEachEntity(Friflo.Engine.ECS.ForEachEntity<T1,T2,T3>).lambda') for each entity in the query result. |
| [FreezeFilter()](ArchetypeQuery_T1,T2,T3_.FreezeFilter().md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.FreezeFilter()') | The query [Filter](ArchetypeQuery.Filter.md 'Friflo.Engine.ECS.ArchetypeQuery.Filter') cannot be changed anymore. |
| [HasValue&lt;TComponent,TValue&gt;(TValue)](ArchetypeQuery_T1,T2,T3_.HasValue_TComponent,TValue_(TValue).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.HasValue<TComponent,TValue>(TValue)') | Include entities having a component with the specified value.<br/> Executes in O(1). |
| [ValueInRange&lt;TComponent,TValue&gt;(TValue, TValue)](ArchetypeQuery_T1,T2,T3_.ValueInRange_TComponent,TValue_(TValue,TValue).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.ValueInRange<TComponent,TValue>(TValue, TValue)') | Include entities having a component value in the specified range.<br/> Executes O(N ⋅ log N) N: all unique values. |
| [WithDisabled()](ArchetypeQuery_T1,T2,T3_.WithDisabled().md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.WithDisabled()') | A query result will contain [Disabled](Disabled.md 'Friflo.Engine.ECS.Disabled') entities. |
| [WithoutAllComponents(ComponentTypes)](ArchetypeQuery_T1,T2,T3_.WithoutAllComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes)') | Entities having all passed [componentTypes](ArchetypeQuery_T1,T2,T3_.WithoutAllComponents(ComponentTypes).md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3_.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes') are excluded from query result. |
| [WithoutAllTags(Tags)](ArchetypeQuery_T1,T2,T3_.WithoutAllTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.WithoutAllTags(Friflo.Engine.ECS.Tags)') | Entities having all passed [tags](ArchetypeQuery_T1,T2,T3_.WithoutAllTags(Tags).md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3_.WithoutAllTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.WithoutAllTags(Friflo.Engine.ECS.Tags).tags') are excluded from query result. |
| [WithoutAnyComponents(ComponentTypes)](ArchetypeQuery_T1,T2,T3_.WithoutAnyComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.WithoutAnyComponents(Friflo.Engine.ECS.ComponentTypes)') | Entities having any of the passed [componentTypes](ArchetypeQuery_T1,T2,T3_.WithoutAnyComponents(ComponentTypes).md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3_.WithoutAnyComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.WithoutAnyComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes') are excluded from query result. |
| [WithoutAnyTags(Tags)](ArchetypeQuery_T1,T2,T3_.WithoutAnyTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.WithoutAnyTags(Friflo.Engine.ECS.Tags)') | Entities having any of the passed [tags](ArchetypeQuery_T1,T2,T3_.WithoutAnyTags(Tags).md#Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3_.WithoutAnyTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.WithoutAnyTags(Friflo.Engine.ECS.Tags).tags') are excluded from query result. |
