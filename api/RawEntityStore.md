#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS')

## RawEntityStore Class

A [RawEntityStore](RawEntityStore.md#'Friflo.Engine.ECS.RawEntityStore') enables using an entity store without using [Entity](Entity.md#'Friflo.Engine.ECS.Entity')'s.<br/>

```csharp
public sealed class RawEntityStore : Friflo.Engine.ECS.EntityStoreBase
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object#'System.Object') &#129106; [EntityStoreBase](EntityStoreBase.md#'Friflo.Engine.ECS.EntityStoreBase') &#129106; RawEntityStore

### Remarks
The focus of the this entity store implementation is performance.<br/>
The key is to minimize heap consumption required by [EntityNode](EntityNode.md#'Friflo.Engine.ECS.EntityNode')'s - 48 bytes<br/>
A [RawEntityStore](RawEntityStore.md#'Friflo.Engine.ECS.RawEntityStore') stores only an array of blittable [Friflo.Engine.ECS.RawEntity](https://docs.microsoft.com/en-us/dotnet/api/Friflo.Engine.ECS.RawEntity#'Friflo.Engine.ECS.RawEntity')'s -
structs having no reference type fields.<br/><br/>
The downside of this approach are:<br/>
- Entities can be created only programmatically but not within the editor which requires (managed) [Entity](Entity.md#'Friflo.Engine.ECS.Entity')'s.
- The API to access / query / mutate [Friflo.Engine.ECS.RawEntity](https://docs.microsoft.com/en-us/dotnet/api/Friflo.Engine.ECS.RawEntity#'Friflo.Engine.ECS.RawEntity')'s is less convenient.<br/>
                  It requires always two parameters - a [RawEntityStore](RawEntityStore.md#'Friflo.Engine.ECS.RawEntityStore') + entity `id` - instead of a single [Entity](Entity.md#'Friflo.Engine.ECS.Entity') reference.

| Methods | |
| :--- | :--- |
| [AddEntityComponent&lt;T&gt;(int, T)](RawEntityStore.AddEntityComponent_T_(int,T).md#'Friflo.Engine.ECS.RawEntityStore.AddEntityComponent<T>(int, T)') | |
| [AddEntityTags(int, Tags)](RawEntityStore.AddEntityTags(int,Tags).md#'Friflo.Engine.ECS.RawEntityStore.AddEntityTags(int, Friflo.Engine.ECS.Tags)') | |
| [CreateEntity()](RawEntityStore.CreateEntity().md#'Friflo.Engine.ECS.RawEntityStore.CreateEntity()') | |
| [CreateEntity(Archetype)](RawEntityStore.CreateEntity(Archetype).md#'Friflo.Engine.ECS.RawEntityStore.CreateEntity(Friflo.Engine.ECS.Archetype)') | Creates a new entity with the components and tags of the given [archetype](RawEntityStore.CreateEntity(Archetype).md#Friflo.Engine.ECS.RawEntityStore.CreateEntity(Friflo.Engine.ECS.Archetype).archetype#'Friflo.Engine.ECS.RawEntityStore.CreateEntity(Friflo.Engine.ECS.Archetype).archetype') |
| [CreateEntity(int)](RawEntityStore.CreateEntity(int).md#'Friflo.Engine.ECS.RawEntityStore.CreateEntity(int)') | |
| [DeleteEntity(int)](RawEntityStore.DeleteEntity(int).md#'Friflo.Engine.ECS.RawEntityStore.DeleteEntity(int)') | |
| [EnsureEntityCapacity(int)](RawEntityStore.EnsureEntityCapacity(int).md#'Friflo.Engine.ECS.RawEntityStore.EnsureEntityCapacity(int)') | |
| [GetEntityArchetype(int)](RawEntityStore.GetEntityArchetype(int).md#'Friflo.Engine.ECS.RawEntityStore.GetEntityArchetype(int)') | |
| [GetEntityComponent&lt;T&gt;(int)](RawEntityStore.GetEntityComponent_T_(int).md#'Friflo.Engine.ECS.RawEntityStore.GetEntityComponent<T>(int)') | |
| [GetEntityComponentCount(int)](RawEntityStore.GetEntityComponentCount(int).md#'Friflo.Engine.ECS.RawEntityStore.GetEntityComponentCount(int)') | |
| [GetEntityTags(int)](RawEntityStore.GetEntityTags(int).md#'Friflo.Engine.ECS.RawEntityStore.GetEntityTags(int)') | |
| [RemoveEntityComponent&lt;T&gt;(int)](RawEntityStore.RemoveEntityComponent_T_(int).md#'Friflo.Engine.ECS.RawEntityStore.RemoveEntityComponent<T>(int)') | |
| [RemoveEntityTags(int, Tags)](RawEntityStore.RemoveEntityTags(int,Tags).md#'Friflo.Engine.ECS.RawEntityStore.RemoveEntityTags(int, Friflo.Engine.ECS.Tags)') | |
