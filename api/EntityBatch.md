#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## EntityBatch Class

An entity batch is a container of component and tag commands that can be [Apply()](EntityBatch.Apply().md 'Friflo.Engine.ECS.EntityBatch.Apply()')'ed to an entity.<br/>
It can be used on a single entity via [Batch](Entity.Batch.md 'Friflo.Engine.ECS.Entity.Batch') or as a <b>bulk operation</b> an a set of entities.

```csharp
public sealed class EntityBatch
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; EntityBatch

### Remarks
Its purpose is to optimize add / remove component and tag changes on entities.<br/>
The same entity changes can be performed with the [Entity](Entity.md 'Friflo.Engine.ECS.Entity') methods using:<br/>[AddComponent&lt;T&gt;()](Entity.AddComponent_T_().md 'Friflo.Engine.ECS.Entity.AddComponent<T>()'), [RemoveComponent&lt;T&gt;()](Entity.RemoveComponent_T_().md 'Friflo.Engine.ECS.Entity.RemoveComponent<T>()'),
[AddTag&lt;TTag&gt;()](Entity.AddTag_TTag_().md 'Friflo.Engine.ECS.Entity.AddTag<TTag>()') or [RemoveTag&lt;TTag&gt;()](Entity.RemoveTag_TTag_().md 'Friflo.Engine.ECS.Entity.RemoveTag<TTag>()').<br/>
Each of this methods may cause a structural change which is a relative costly operation in comparison to others.<br/>
Using [EntityBatch](EntityBatch.md 'Friflo.Engine.ECS.EntityBatch') minimize theses structural changes to one or none.<br/><br/><b>Bulk operation</b><br/>
To perform the same batch on multiple entities you can use [ApplyBatch(EntityBatch)](QueryEntities.ApplyBatch(EntityBatch).md 'Friflo.Engine.ECS.QueryEntities.ApplyBatch(Friflo.Engine.ECS.EntityBatch)') for <br/>
- all entities of an [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') using [Entities](EntityStore.Entities.md 'Friflo.Engine.ECS.EntityStore.Entities').<br/>
- the entities of an [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') using [Entities](ArchetypeQuery.Entities.md 'Friflo.Engine.ECS.ArchetypeQuery.Entities').<br/>
- or the entities of an [Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype') using [Entities](Archetype.Entities.md 'Friflo.Engine.ECS.Archetype.Entities').

| Constructors | |
| :--- | :--- |
| [EntityBatch()](EntityBatch.EntityBatch().md 'Friflo.Engine.ECS.EntityBatch.EntityBatch()') | Creates a batch that can be applied to a <b>single</b> entity or a set of entities using a <b>bulk operation</b>.<br/> See [EntityBatch](EntityBatch.md 'Friflo.Engine.ECS.EntityBatch'). |

| Properties | |
| :--- | :--- |
| [CommandCount](EntityBatch.CommandCount.md 'Friflo.Engine.ECS.EntityBatch.CommandCount') | Return the number of commands stored in the [EntityBatch](EntityBatch.md 'Friflo.Engine.ECS.EntityBatch'). |

| Methods | |
| :--- | :--- |
| [AddComponent&lt;T&gt;(T)](EntityBatch.AddComponent_T_(T).md 'Friflo.Engine.ECS.EntityBatch.AddComponent<T>(T)') | Adds an add component command to the [EntityBatch](EntityBatch.md 'Friflo.Engine.ECS.EntityBatch') with the given [component](EntityBatch.AddComponent_T_(T).md#Friflo.Engine.ECS.EntityBatch.AddComponent_T_(T).component 'Friflo.Engine.ECS.EntityBatch.AddComponent<T>(T).component'). |
| [AddTag&lt;T&gt;()](EntityBatch.AddTag_T_().md 'Friflo.Engine.ECS.EntityBatch.AddTag<T>()') | Adds an add tag command to the [EntityBatch](EntityBatch.md 'Friflo.Engine.ECS.EntityBatch'). |
| [AddTags(Tags)](EntityBatch.AddTags(Tags).md 'Friflo.Engine.ECS.EntityBatch.AddTags(Friflo.Engine.ECS.Tags)') | Adds an add tags command to the [EntityBatch](EntityBatch.md 'Friflo.Engine.ECS.EntityBatch') adding the given [tags](EntityBatch.AddTags(Tags).md#Friflo.Engine.ECS.EntityBatch.AddTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.EntityBatch.AddTags(Friflo.Engine.ECS.Tags).tags'). |
| [Apply()](EntityBatch.Apply().md 'Friflo.Engine.ECS.EntityBatch.Apply()') | Apply the add / remove commands to the entity the [Batch](Entity.Batch.md 'Friflo.Engine.ECS.Entity.Batch') operates. |
| [ApplyTo(Entity)](EntityBatch.ApplyTo(Entity).md 'Friflo.Engine.ECS.EntityBatch.ApplyTo(Friflo.Engine.ECS.Entity)') | Apply the batch commands to the given [entity](EntityBatch.ApplyTo(Entity).md#Friflo.Engine.ECS.EntityBatch.ApplyTo(Friflo.Engine.ECS.Entity).entity 'Friflo.Engine.ECS.EntityBatch.ApplyTo(Friflo.Engine.ECS.Entity).entity'). |
| [Clear()](EntityBatch.Clear().md 'Friflo.Engine.ECS.EntityBatch.Clear()') | Clear all commands currently stored in the [EntityBatch](EntityBatch.md 'Friflo.Engine.ECS.EntityBatch'). |
| [RemoveComponent&lt;T&gt;()](EntityBatch.RemoveComponent_T_().md 'Friflo.Engine.ECS.EntityBatch.RemoveComponent<T>()') | Adds a remove component command to the [EntityBatch](EntityBatch.md 'Friflo.Engine.ECS.EntityBatch'). |
| [RemoveTag&lt;T&gt;()](EntityBatch.RemoveTag_T_().md 'Friflo.Engine.ECS.EntityBatch.RemoveTag<T>()') | Adds a remove tag command to the [EntityBatch](EntityBatch.md 'Friflo.Engine.ECS.EntityBatch'). |
| [RemoveTags(Tags)](EntityBatch.RemoveTags(Tags).md 'Friflo.Engine.ECS.EntityBatch.RemoveTags(Friflo.Engine.ECS.Tags)') | Adds a remove tags command to the [EntityBatch](EntityBatch.md 'Friflo.Engine.ECS.EntityBatch') removing the given [tags](EntityBatch.RemoveTags(Tags).md#Friflo.Engine.ECS.EntityBatch.RemoveTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.EntityBatch.RemoveTags(Friflo.Engine.ECS.Tags).tags'). |
| [ToString()](EntityBatch.ToString().md 'Friflo.Engine.ECS.EntityBatch.ToString()') | |
