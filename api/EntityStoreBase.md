#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## EntityStoreBase Class

```csharp
public abstract class EntityStoreBase
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; EntityStoreBase

Derived  
&#8627; [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')  
&#8627; [RawEntityStore](RawEntityStore.md 'Friflo.Engine.ECS.RawEntityStore')

| Properties | |
| :--- | :--- |
| [ArchetypeCount](EntityStoreBase.ArchetypeCount.md 'Friflo.Engine.ECS.EntityStoreBase.ArchetypeCount') | |
| [Archetypes](EntityStoreBase.Archetypes.md 'Friflo.Engine.ECS.EntityStoreBase.Archetypes') | Array of [Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype')'s utilized by the entity store |
| [EntityCount](EntityStoreBase.EntityCount.md 'Friflo.Engine.ECS.EntityStoreBase.EntityCount') | Number of all entities stored in the entity store |
| [NodeMaxId](EntityStoreBase.NodeMaxId.md 'Friflo.Engine.ECS.EntityStoreBase.NodeMaxId') | |
| [Systems](EntityStoreBase.Systems.md 'Friflo.Engine.ECS.EntityStoreBase.Systems') | |
| [UniqueEntities](EntityStoreBase.UniqueEntities.md 'Friflo.Engine.ECS.EntityStoreBase.UniqueEntities') | Return all [UniqueEntity](UniqueEntity.md 'Friflo.Engine.ECS.UniqueEntity')'s in the entity store |

| Methods | |
| :--- | :--- |
| [FindArchetype(ComponentTypes, Tags)](EntityStoreBase.FindArchetype(ComponentTypes,Tags).md 'Friflo.Engine.ECS.EntityStoreBase.FindArchetype(Friflo.Engine.ECS.ComponentTypes, Friflo.Engine.ECS.Tags)') | |
| [GetArchetype(Tags)](EntityStoreBase.GetArchetype(Tags).md 'Friflo.Engine.ECS.EntityStoreBase.GetArchetype(Friflo.Engine.ECS.Tags)') | |
| [GetArchetype&lt;T1,T2,T3,T4,T5&gt;(Signature&lt;T1,T2,T3,T4,T5&gt;, Tags)](EntityStoreBase.GetArchetype_T1,T2,T3,T4,T5_(Signature_T1,T2,T3,T4,T5_,Tags).md 'Friflo.Engine.ECS.EntityStoreBase.GetArchetype<T1,T2,T3,T4,T5>(Friflo.Engine.ECS.Signature<T1,T2,T3,T4,T5>, Friflo.Engine.ECS.Tags)') | |
| [GetArchetype&lt;T1,T2,T3,T4&gt;(Signature&lt;T1,T2,T3,T4&gt;, Tags)](EntityStoreBase.GetArchetype_T1,T2,T3,T4_(Signature_T1,T2,T3,T4_,Tags).md 'Friflo.Engine.ECS.EntityStoreBase.GetArchetype<T1,T2,T3,T4>(Friflo.Engine.ECS.Signature<T1,T2,T3,T4>, Friflo.Engine.ECS.Tags)') | |
| [GetArchetype&lt;T1,T2,T3&gt;(Signature&lt;T1,T2,T3&gt;, Tags)](EntityStoreBase.GetArchetype_T1,T2,T3_(Signature_T1,T2,T3_,Tags).md 'Friflo.Engine.ECS.EntityStoreBase.GetArchetype<T1,T2,T3>(Friflo.Engine.ECS.Signature<T1,T2,T3>, Friflo.Engine.ECS.Tags)') | |
| [GetArchetype&lt;T1,T2&gt;(Signature&lt;T1,T2&gt;, Tags)](EntityStoreBase.GetArchetype_T1,T2_(Signature_T1,T2_,Tags).md 'Friflo.Engine.ECS.EntityStoreBase.GetArchetype<T1,T2>(Friflo.Engine.ECS.Signature<T1,T2>, Friflo.Engine.ECS.Tags)') | |
| [GetArchetype&lt;T1&gt;(Signature&lt;T1&gt;, Tags)](EntityStoreBase.GetArchetype_T1_(Signature_T1_,Tags).md 'Friflo.Engine.ECS.EntityStoreBase.GetArchetype<T1>(Friflo.Engine.ECS.Signature<T1>, Friflo.Engine.ECS.Tags)') | |
| [GetUniqueEntity(string)](EntityStoreBase.GetUniqueEntity(string).md 'Friflo.Engine.ECS.EntityStoreBase.GetUniqueEntity(string)') | Return the entity with a [UniqueEntity](UniqueEntity.md 'Friflo.Engine.ECS.UniqueEntity') component and its [uid](UniqueEntity.uid.md 'Friflo.Engine.ECS.UniqueEntity.uid') == [uid](EntityStoreBase.GetUniqueEntity(string).md#Friflo.Engine.ECS.EntityStoreBase.GetUniqueEntity(string).uid 'Friflo.Engine.ECS.EntityStoreBase.GetUniqueEntity(string).uid') |
| [Query()](EntityStoreBase.Query().md 'Friflo.Engine.ECS.EntityStoreBase.Query()') | Create a reusable [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') for the entity store |
| [Query&lt;T1,T2,T3,T4,T5&gt;()](EntityStoreBase.Query_T1,T2,T3,T4,T5_().md 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3,T4,T5>()') | |
| [Query&lt;T1,T2,T3,T4,T5&gt;(Signature&lt;T1,T2,T3,T4,T5&gt;)](EntityStoreBase.Query_T1,T2,T3,T4,T5_(Signature_T1,T2,T3,T4,T5_).md 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3,T4,T5>(Friflo.Engine.ECS.Signature<T1,T2,T3,T4,T5>)') | Create a reusable [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') for the entity store |
| [Query&lt;T1,T2,T3,T4&gt;()](EntityStoreBase.Query_T1,T2,T3,T4_().md 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3,T4>()') | |
| [Query&lt;T1,T2,T3,T4&gt;(Signature&lt;T1,T2,T3,T4&gt;)](EntityStoreBase.Query_T1,T2,T3,T4_(Signature_T1,T2,T3,T4_).md 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3,T4>(Friflo.Engine.ECS.Signature<T1,T2,T3,T4>)') | Create a reusable [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') for the entity store |
| [Query&lt;T1,T2,T3&gt;()](EntityStoreBase.Query_T1,T2,T3_().md 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3>()') | |
| [Query&lt;T1,T2,T3&gt;(Signature&lt;T1,T2,T3&gt;)](EntityStoreBase.Query_T1,T2,T3_(Signature_T1,T2,T3_).md 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3>(Friflo.Engine.ECS.Signature<T1,T2,T3>)') | Create a reusable [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') for the entity store |
| [Query&lt;T1,T2&gt;()](EntityStoreBase.Query_T1,T2_().md 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2>()') | |
| [Query&lt;T1,T2&gt;(Signature&lt;T1,T2&gt;)](EntityStoreBase.Query_T1,T2_(Signature_T1,T2_).md 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2>(Friflo.Engine.ECS.Signature<T1,T2>)') | Create a reusable [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') for the entity store |
| [Query&lt;T1&gt;()](EntityStoreBase.Query_T1_().md 'Friflo.Engine.ECS.EntityStoreBase.Query<T1>()') | |
| [Query&lt;T1&gt;(Signature&lt;T1&gt;)](EntityStoreBase.Query_T1_(Signature_T1_).md 'Friflo.Engine.ECS.EntityStoreBase.Query<T1>(Friflo.Engine.ECS.Signature<T1>)') | Create a reusable [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') for the entity store |
| [ToString()](EntityStoreBase.ToString().md 'Friflo.Engine.ECS.EntityStoreBase.ToString()') | |

| Events | |
| :--- | :--- |
| [OnComponentAdded](EntityStoreBase.OnComponentAdded.md 'Friflo.Engine.ECS.EntityStoreBase.OnComponentAdded') | Add / remove an event handler for [ComponentChanged](ComponentChanged.md 'Friflo.Engine.ECS.ComponentChanged') events triggered by: <br/>[AddComponent&lt;T&gt;()](Entity.AddComponent_T_().md 'Friflo.Engine.ECS.Entity.AddComponent<T>()'). |
| [OnComponentRemoved](EntityStoreBase.OnComponentRemoved.md 'Friflo.Engine.ECS.EntityStoreBase.OnComponentRemoved') | Add / remove an event handler for [ComponentChanged](ComponentChanged.md 'Friflo.Engine.ECS.ComponentChanged') events triggered by: <br/>[RemoveComponent&lt;T&gt;()](Entity.RemoveComponent_T_().md 'Friflo.Engine.ECS.Entity.RemoveComponent<T>()'). |
| [OnTagsChanged](EntityStoreBase.OnTagsChanged.md 'Friflo.Engine.ECS.EntityStoreBase.OnTagsChanged') | Add / remove an event handler for [TagsChanged](TagsChanged.md 'Friflo.Engine.ECS.TagsChanged') events triggered by:<br/>[AddTag&lt;TTag&gt;()](Entity.AddTag_TTag_().md 'Friflo.Engine.ECS.Entity.AddTag<TTag>()')<br/>[AddTags(Tags)](Entity.AddTags(Tags).md 'Friflo.Engine.ECS.Entity.AddTags(Friflo.Engine.ECS.Tags)')<br/>[RemoveTag&lt;TTag&gt;()](Entity.RemoveTag_TTag_().md 'Friflo.Engine.ECS.Entity.RemoveTag<TTag>()')<br/>[RemoveTags(Tags)](Entity.RemoveTags(Tags).md 'Friflo.Engine.ECS.Entity.RemoveTags(Friflo.Engine.ECS.Tags)'). |