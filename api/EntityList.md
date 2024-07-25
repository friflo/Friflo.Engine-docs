#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## EntityList Class

A list of entities of a specific [EntityStore](EntityList.EntityStore.md 'Friflo.Engine.ECS.EntityList.EntityStore') used to apply changes to all entities in the container.<br/>
It's recommended to reuse instances of this class to avoid unnecessary allocations.<br/>
See <a href="https://friflo.gitbook.io/friflo.engine.ecs/examples/optimization#entitybatch---entitylist">Example.</a>

```csharp
public sealed class EntityList :
System.Collections.Generic.IList<Friflo.Engine.ECS.Entity>,
System.Collections.Generic.ICollection<Friflo.Engine.ECS.Entity>,
System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.Entity>,
System.Collections.IEnumerable
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; EntityList

Implements [System.Collections.Generic.IList&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IList-1 'System.Collections.Generic.IList`1')[Entity](Entity.md 'Friflo.Engine.ECS.Entity')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IList-1 'System.Collections.Generic.IList`1'), [System.Collections.Generic.ICollection&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.ICollection-1 'System.Collections.Generic.ICollection`1')[Entity](Entity.md 'Friflo.Engine.ECS.Entity')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.ICollection-1 'System.Collections.Generic.ICollection`1'), [System.Collections.Generic.IEnumerable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1')[Entity](Entity.md 'Friflo.Engine.ECS.Entity')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1'), [System.Collections.IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerable 'System.Collections.IEnumerable')

| Constructors | |
| :--- | :--- |
| [EntityList()](EntityList.EntityList().md 'Friflo.Engine.ECS.EntityList.EntityList()') | Creates a container for entities returned by a query to perform structural changes.<br/> This constructor is intended for use in [ToEntityList()](QueryEntities.ToEntityList().md 'Friflo.Engine.ECS.QueryEntities.ToEntityList()'). |
| [EntityList(EntityStore)](EntityList.EntityList(EntityStore).md 'Friflo.Engine.ECS.EntityList.EntityList(Friflo.Engine.ECS.EntityStore)') | Creates a container to store entities of the given [store](EntityList.EntityList(EntityStore).md#Friflo.Engine.ECS.EntityList.EntityList(Friflo.Engine.ECS.EntityStore).store 'Friflo.Engine.ECS.EntityList.EntityList(Friflo.Engine.ECS.EntityStore).store'). |

| Properties | |
| :--- | :--- |
| [Capacity](EntityList.Capacity.md 'Friflo.Engine.ECS.EntityList.Capacity') | |
| [Count](EntityList.Count.md 'Friflo.Engine.ECS.EntityList.Count') | Returns the number of entities stored in the container. |
| [EntityStore](EntityList.EntityStore.md 'Friflo.Engine.ECS.EntityList.EntityStore') | Returns the store to which the list entities belong to. |
| [Ids](EntityList.Ids.md 'Friflo.Engine.ECS.EntityList.Ids') | Return the ids of entities stored in the container. |
| [IsReadOnly](EntityList.IsReadOnly.md 'Friflo.Engine.ECS.EntityList.IsReadOnly') | Gets a value indicating whether the [System.Collections.ICollection](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.ICollection 'System.Collections.ICollection') is read-only. |
| [this[int]](EntityList.this[int].md 'Friflo.Engine.ECS.EntityList.this[int]') | Return the entity at the given [index](EntityList.this[int].md#Friflo.Engine.ECS.EntityList.this[int].index 'Friflo.Engine.ECS.EntityList.this[int].index'). |

| Methods | |
| :--- | :--- |
| [Add(Entity)](EntityList.Add(Entity).md 'Friflo.Engine.ECS.EntityList.Add(Friflo.Engine.ECS.Entity)') | Adds the given [entity](EntityList.Add(Entity).md#Friflo.Engine.ECS.EntityList.Add(Friflo.Engine.ECS.Entity).entity 'Friflo.Engine.ECS.EntityList.Add(Friflo.Engine.ECS.Entity).entity') to the end of the [EntityList](EntityList.md 'Friflo.Engine.ECS.EntityList'). |
| [Add(int)](EntityList.Add(int).md 'Friflo.Engine.ECS.EntityList.Add(int)') | Adds the entity with the given [id](EntityList.Add(int).md#Friflo.Engine.ECS.EntityList.Add(int).id 'Friflo.Engine.ECS.EntityList.Add(int).id') to the end of the [EntityList](EntityList.md 'Friflo.Engine.ECS.EntityList'). |
| [AddTree(Entity)](EntityList.AddTree(Entity).md 'Friflo.Engine.ECS.EntityList.AddTree(Friflo.Engine.ECS.Entity)') | Adds the [entity](EntityList.AddTree(Entity).md#Friflo.Engine.ECS.EntityList.AddTree(Friflo.Engine.ECS.Entity).entity 'Friflo.Engine.ECS.EntityList.AddTree(Friflo.Engine.ECS.Entity).entity') and recursively all child entities of the given [entity](EntityList.AddTree(Entity).md#Friflo.Engine.ECS.EntityList.AddTree(Friflo.Engine.ECS.Entity).entity 'Friflo.Engine.ECS.EntityList.AddTree(Friflo.Engine.ECS.Entity).entity') to the end of the [EntityList](EntityList.md 'Friflo.Engine.ECS.EntityList'). |
| [ApplyAddTags(Tags)](EntityList.ApplyAddTags(Tags).md 'Friflo.Engine.ECS.EntityList.ApplyAddTags(Friflo.Engine.ECS.Tags)') | Adds the given [tags](EntityList.ApplyAddTags(Tags).md#Friflo.Engine.ECS.EntityList.ApplyAddTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.EntityList.ApplyAddTags(Friflo.Engine.ECS.Tags).tags') to all entities in the [EntityList](EntityList.md 'Friflo.Engine.ECS.EntityList'). |
| [ApplyBatch(EntityBatch)](EntityList.ApplyBatch(EntityBatch).md 'Friflo.Engine.ECS.EntityList.ApplyBatch(Friflo.Engine.ECS.EntityBatch)') | Apply the given [batch](EntityList.ApplyBatch(EntityBatch).md#Friflo.Engine.ECS.EntityList.ApplyBatch(Friflo.Engine.ECS.EntityBatch).batch 'Friflo.Engine.ECS.EntityList.ApplyBatch(Friflo.Engine.ECS.EntityBatch).batch') to all entities in the [EntityList](EntityList.md 'Friflo.Engine.ECS.EntityList'). |
| [ApplyRemoveTags(Tags)](EntityList.ApplyRemoveTags(Tags).md 'Friflo.Engine.ECS.EntityList.ApplyRemoveTags(Friflo.Engine.ECS.Tags)') | Removes the given [tags](EntityList.ApplyRemoveTags(Tags).md#Friflo.Engine.ECS.EntityList.ApplyRemoveTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.EntityList.ApplyRemoveTags(Friflo.Engine.ECS.Tags).tags') from all entities in the [EntityList](EntityList.md 'Friflo.Engine.ECS.EntityList'). |
| [Clear()](EntityList.Clear().md 'Friflo.Engine.ECS.EntityList.Clear()') | Removes all entities from the [EntityList](EntityList.md 'Friflo.Engine.ECS.EntityList'). |
| [Contains(Entity)](EntityList.Contains(Entity).md 'Friflo.Engine.ECS.EntityList.Contains(Friflo.Engine.ECS.Entity)') | not implemented |
| [CopyTo(Entity[], int)](EntityList.CopyTo(Entity[],int).md 'Friflo.Engine.ECS.EntityList.CopyTo(Friflo.Engine.ECS.Entity[], int)') | Copies the entities of the [EntityList](EntityList.md 'Friflo.Engine.ECS.EntityList') to an [Entity](Entity.md 'Friflo.Engine.ECS.Entity')[], starting at the given [index](EntityList.CopyTo(Entity[],int).md#Friflo.Engine.ECS.EntityList.CopyTo(Friflo.Engine.ECS.Entity[],int).index 'Friflo.Engine.ECS.EntityList.CopyTo(Friflo.Engine.ECS.Entity[], int).index') |
| [GetEnumerator()](EntityList.GetEnumerator().md 'Friflo.Engine.ECS.EntityList.GetEnumerator()') | Returns an enumerator that iterates through the [EntityList](EntityList.md 'Friflo.Engine.ECS.EntityList'). |
| [IndexOf(Entity)](EntityList.IndexOf(Entity).md 'Friflo.Engine.ECS.EntityList.IndexOf(Friflo.Engine.ECS.Entity)') | not implemented |
| [Insert(int, Entity)](EntityList.Insert(int,Entity).md 'Friflo.Engine.ECS.EntityList.Insert(int, Friflo.Engine.ECS.Entity)') | not implemented |
| [Remove(Entity)](EntityList.Remove(Entity).md 'Friflo.Engine.ECS.EntityList.Remove(Friflo.Engine.ECS.Entity)') | not implemented |
| [RemoveAt(int)](EntityList.RemoveAt(int).md 'Friflo.Engine.ECS.EntityList.RemoveAt(int)') | not implemented |
| [SetStore(EntityStore)](EntityList.SetStore(EntityStore).md 'Friflo.Engine.ECS.EntityList.SetStore(Friflo.Engine.ECS.EntityStore)') | Set the [store](EntityList.SetStore(EntityStore).md#Friflo.Engine.ECS.EntityList.SetStore(Friflo.Engine.ECS.EntityStore).store 'Friflo.Engine.ECS.EntityList.SetStore(Friflo.Engine.ECS.EntityStore).store') to which the list entities belong to.<br/> EntityList must be empty when setting [EntityStore](EntityList.EntityStore.md 'Friflo.Engine.ECS.EntityList.EntityStore'). |
| [ToString()](EntityList.ToString().md 'Friflo.Engine.ECS.EntityList.ToString()') | |

| Explicit Interface Implementations | |
| :--- | :--- |
| [System.Collections.Generic.IEnumerable&lt;Friflo.Engine.ECS.Entity&gt;.GetEnumerator()](EntityList.System.Collections.Generic.IEnumerable_Friflo.Engine.ECS.Entity_.GetEnumerator().md 'Friflo.Engine.ECS.EntityList.System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.Entity>.GetEnumerator()') | |
| [System.Collections.IEnumerable.GetEnumerator()](EntityList.System.Collections.IEnumerable.GetEnumerator().md 'Friflo.Engine.ECS.EntityList.System.Collections.IEnumerable.GetEnumerator()') | |
