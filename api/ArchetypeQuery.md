#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ArchetypeQuery Class

[ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') an all its generic implementation are immutable and designed to reuse its instances.

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

| Properties | |
| :--- | :--- |
| [Archetypes](ArchetypeQuery.Archetypes.md 'Friflo.Engine.ECS.ArchetypeQuery.Archetypes') | |
| [ChunkCount](ArchetypeQuery.ChunkCount.md 'Friflo.Engine.ECS.ArchetypeQuery.ChunkCount') | |
| [Entities](ArchetypeQuery.Entities.md 'Friflo.Engine.ECS.ArchetypeQuery.Entities') | Return the [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') entities mainly for debugging.<br/> For efficient access to entity [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')'s use one of the generic <b> tore.Query()</c>  methods. |
| [EntityCount](ArchetypeQuery.EntityCount.md 'Friflo.Engine.ECS.ArchetypeQuery.EntityCount') | |
| [EventFilter](ArchetypeQuery.EventFilter.md 'Friflo.Engine.ECS.ArchetypeQuery.EventFilter') | |
| [Store](ArchetypeQuery.Store.md 'Friflo.Engine.ECS.ArchetypeQuery.Store') | |

| Methods | |
| :--- | :--- |
| [AllTags(Tags)](ArchetypeQuery.AllTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery.AllTags(Friflo.Engine.ECS.Tags)') | |
| [HasEvent(int)](ArchetypeQuery.HasEvent(int).md 'Friflo.Engine.ECS.ArchetypeQuery.HasEvent(int)') | Returns true if a component or tag was added / removed to / from the entity with the passed [entityId](ArchetypeQuery.HasEvent(int).md#Friflo.Engine.ECS.ArchetypeQuery.HasEvent(int).entityId 'Friflo.Engine.ECS.ArchetypeQuery.HasEvent(int).entityId'). |
| [ToString()](ArchetypeQuery.ToString().md 'Friflo.Engine.ECS.ArchetypeQuery.ToString()') | |
