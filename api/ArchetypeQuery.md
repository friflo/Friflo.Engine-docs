#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ArchetypeQuery Class

[ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') and all its generic implementations are designed to be reused.<br/>
            By default, a query does not contain [Disabled](Disabled.md 'Friflo.Engine.ECS.Disabled') entities. Use [WithDisabled()](ArchetypeQuery.WithDisabled().md 'Friflo.Engine.ECS.ArchetypeQuery.WithDisabled()') if needed.<br/>
            See <a href="https://github.com/friflo/Friflo.Json.Fliox/wiki/Examples-~-General#query-entities">Example.</a>

```csharp
public class ArchetypeQuery
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; ArchetypeQuery

Derived  
&#8627; [ArchetypeQuery&lt;T1,T2,T3,T4,T5&gt;](ArchetypeQuery_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>')  
&#8627; [ArchetypeQuery&lt;T1,T2,T3,T4&gt;](ArchetypeQuery_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>')  
&#8627; [ArchetypeQuery&lt;T1,T2,T3&gt;](ArchetypeQuery_T1,T2,T3_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>')  
&#8627; [ArchetypeQuery&lt;T1,T2&gt;](ArchetypeQuery_T1,T2_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>')  
&#8627; [ArchetypeQuery&lt;T1&gt;](ArchetypeQuery_T1_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1>')

| Fields | |
| :--- | :--- |
| [Filter](ArchetypeQuery.Filter.md 'Friflo.Engine.ECS.ArchetypeQuery.Filter') | Return component and tag filters added to the query |

| Properties | |
| :--- | :--- |
| [Archetypes](ArchetypeQuery.Archetypes.md 'Friflo.Engine.ECS.ArchetypeQuery.Archetypes') | Returns the set of [Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype')'s matching the query. |
| [ChunkCount](ArchetypeQuery.ChunkCount.md 'Friflo.Engine.ECS.ArchetypeQuery.ChunkCount') | Return the number of `Chunks` returned by the query. |
| [ComponentTypes](ArchetypeQuery.ComponentTypes.md 'Friflo.Engine.ECS.ArchetypeQuery.ComponentTypes') | Return the [ComponentTypes](ArchetypeQuery.ComponentTypes.md 'Friflo.Engine.ECS.ArchetypeQuery.ComponentTypes') of components returned by a query result. |
| [Count](ArchetypeQuery.Count.md 'Friflo.Engine.ECS.ArchetypeQuery.Count') | Return the number of entities matching the query. |
| [Entities](ArchetypeQuery.Entities.md 'Friflo.Engine.ECS.ArchetypeQuery.Entities') | Return the [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') entities mainly for debugging.<br/> For efficient access to entity [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')'s use one of the generic `EntityStore.Query()` methods. |
| [EntityCount](ArchetypeQuery.EntityCount.md 'Friflo.Engine.ECS.ArchetypeQuery.EntityCount') | Obsolete. Renamed to [Count](ArchetypeQuery.Count.md 'Friflo.Engine.ECS.ArchetypeQuery.Count'). |
| [EventFilter](ArchetypeQuery.EventFilter.md 'Friflo.Engine.ECS.ArchetypeQuery.EventFilter') | A [EventFilter](EventFilter.md 'Friflo.Engine.ECS.EventFilter') used to filter the query result for added/removed components/tags.<br/> See <a href="https://github.com/friflo/Friflo.Json.Fliox/wiki/Examples-~-Optimization#eventfilter">Example.</a> |
| [Store](ArchetypeQuery.Store.md 'Friflo.Engine.ECS.ArchetypeQuery.Store') | The [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') on which the query operates. |

| Methods | |
| :--- | :--- |
| [AllComponents(ComponentTypes)](ArchetypeQuery.AllComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery.AllComponents(Friflo.Engine.ECS.ComponentTypes)') | A query result will contain only entities having all passed [componentTypes](ArchetypeQuery.AllComponents(ComponentTypes).md#Friflo.Engine.ECS.ArchetypeQuery.AllComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes 'Friflo.Engine.ECS.ArchetypeQuery.AllComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes'). |
| [AllTags(Tags)](ArchetypeQuery.AllTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery.AllTags(Friflo.Engine.ECS.Tags)') | A query result will contain only entities having all passed [tags](ArchetypeQuery.AllTags(Tags).md#Friflo.Engine.ECS.ArchetypeQuery.AllTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.ArchetypeQuery.AllTags(Friflo.Engine.ECS.Tags).tags'). |
| [AnyComponents(ComponentTypes)](ArchetypeQuery.AnyComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery.AnyComponents(Friflo.Engine.ECS.ComponentTypes)') | A query result will contain only entities having any of the the passed [componentTypes](ArchetypeQuery.AnyComponents(ComponentTypes).md#Friflo.Engine.ECS.ArchetypeQuery.AnyComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes 'Friflo.Engine.ECS.ArchetypeQuery.AnyComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes'). |
| [AnyTags(Tags)](ArchetypeQuery.AnyTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery.AnyTags(Friflo.Engine.ECS.Tags)') | A query result will contain only entities having any of the the passed [tags](ArchetypeQuery.AnyTags(Tags).md#Friflo.Engine.ECS.ArchetypeQuery.AnyTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.ArchetypeQuery.AnyTags(Friflo.Engine.ECS.Tags).tags'). |
| [FreezeFilter()](ArchetypeQuery.FreezeFilter().md 'Friflo.Engine.ECS.ArchetypeQuery.FreezeFilter()') | The query [Filter](ArchetypeQuery.Filter.md 'Friflo.Engine.ECS.ArchetypeQuery.Filter') cannot be changed anymore. |
| [HasEvent(int)](ArchetypeQuery.HasEvent(int).md 'Friflo.Engine.ECS.ArchetypeQuery.HasEvent(int)') | Returns true if a component or tag was added / removed to / from the entity with the passed [entityId](ArchetypeQuery.HasEvent(int).md#Friflo.Engine.ECS.ArchetypeQuery.HasEvent(int).entityId 'Friflo.Engine.ECS.ArchetypeQuery.HasEvent(int).entityId'). |
| [HasValue&lt;TComponent,TValue&gt;(TValue)](ArchetypeQuery.HasValue_TComponent,TValue_(TValue).md 'Friflo.Engine.ECS.ArchetypeQuery.HasValue<TComponent,TValue>(TValue)') | Include entities having a component with the specified value.<br/> Executes in O(1). |
| [IsMatch(ComponentTypes, Tags)](ArchetypeQuery.IsMatch(ComponentTypes,Tags).md 'Friflo.Engine.ECS.ArchetypeQuery.IsMatch(Friflo.Engine.ECS.ComponentTypes, Friflo.Engine.ECS.Tags)') | Returns true if the passed [componentTypes](ArchetypeQuery.IsMatch(ComponentTypes,Tags).md#Friflo.Engine.ECS.ArchetypeQuery.IsMatch(Friflo.Engine.ECS.ComponentTypes,Friflo.Engine.ECS.Tags).componentTypes 'Friflo.Engine.ECS.ArchetypeQuery.IsMatch(Friflo.Engine.ECS.ComponentTypes, Friflo.Engine.ECS.Tags).componentTypes') and [tags](ArchetypeQuery.IsMatch(ComponentTypes,Tags).md#Friflo.Engine.ECS.ArchetypeQuery.IsMatch(Friflo.Engine.ECS.ComponentTypes,Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.ArchetypeQuery.IsMatch(Friflo.Engine.ECS.ComponentTypes, Friflo.Engine.ECS.Tags).tags') matches the query filter. |
| [ToEntityList()](ArchetypeQuery.ToEntityList().md 'Friflo.Engine.ECS.ArchetypeQuery.ToEntityList()') | Returns the query result as a [EntityList](EntityList.md 'Friflo.Engine.ECS.EntityList') used to perform structural changes. |
| [ToString()](ArchetypeQuery.ToString().md 'Friflo.Engine.ECS.ArchetypeQuery.ToString()') | |
| [ValueInRange&lt;TComponent,TValue&gt;(TValue, TValue)](ArchetypeQuery.ValueInRange_TComponent,TValue_(TValue,TValue).md 'Friflo.Engine.ECS.ArchetypeQuery.ValueInRange<TComponent,TValue>(TValue, TValue)') | Include entities having a component value in the specified range.<br/> Executes O(N ⋅ log N) N: all unique values. |
| [WithDisabled()](ArchetypeQuery.WithDisabled().md 'Friflo.Engine.ECS.ArchetypeQuery.WithDisabled()') | A query result will contain [Disabled](Disabled.md 'Friflo.Engine.ECS.Disabled') entities. |
| [WithoutAllComponents(ComponentTypes)](ArchetypeQuery.WithoutAllComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes)') | Entities having all passed [componentTypes](ArchetypeQuery.WithoutAllComponents(ComponentTypes).md#Friflo.Engine.ECS.ArchetypeQuery.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes 'Friflo.Engine.ECS.ArchetypeQuery.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes') are excluded from query result. |
| [WithoutAllTags(Tags)](ArchetypeQuery.WithoutAllTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery.WithoutAllTags(Friflo.Engine.ECS.Tags)') | Entities having all passed [tags](ArchetypeQuery.WithoutAllTags(Tags).md#Friflo.Engine.ECS.ArchetypeQuery.WithoutAllTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.ArchetypeQuery.WithoutAllTags(Friflo.Engine.ECS.Tags).tags') are excluded from query result. |
| [WithoutAnyComponents(ComponentTypes)](ArchetypeQuery.WithoutAnyComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery.WithoutAnyComponents(Friflo.Engine.ECS.ComponentTypes)') | Entities having any of the passed [componentTypes](ArchetypeQuery.WithoutAnyComponents(ComponentTypes).md#Friflo.Engine.ECS.ArchetypeQuery.WithoutAnyComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes 'Friflo.Engine.ECS.ArchetypeQuery.WithoutAnyComponents(Friflo.Engine.ECS.ComponentTypes).componentTypes') are excluded from query result. |
| [WithoutAnyTags(Tags)](ArchetypeQuery.WithoutAnyTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery.WithoutAnyTags(Friflo.Engine.ECS.Tags)') | Entities having any of the passed [tags](ArchetypeQuery.WithoutAnyTags(Tags).md#Friflo.Engine.ECS.ArchetypeQuery.WithoutAnyTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.ArchetypeQuery.WithoutAnyTags(Friflo.Engine.ECS.Tags).tags') are excluded from query result. |
