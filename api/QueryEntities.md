#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## QueryEntities Struct

Provide the result set of an [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') as a set of [Entity](Entity.md 'Friflo.Engine.ECS.Entity')'s.

```csharp
public readonly struct QueryEntities :
System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.Entity>,
System.Collections.IEnumerable
```

Implements [System.Collections.Generic.IEnumerable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1')[Entity](Entity.md 'Friflo.Engine.ECS.Entity')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1'), [System.Collections.IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerable 'System.Collections.IEnumerable')

| Properties | |
| :--- | :--- |
| [Count](QueryEntities.Count.md 'Friflo.Engine.ECS.QueryEntities.Count') | Return the number of entities matching the query. |

| Methods | |
| :--- | :--- |
| [ApplyBatch(EntityBatch)](QueryEntities.ApplyBatch(EntityBatch).md 'Friflo.Engine.ECS.QueryEntities.ApplyBatch(Friflo.Engine.ECS.EntityBatch)') | Apply the given entity [batch](QueryEntities.ApplyBatch(EntityBatch).md#Friflo.Engine.ECS.QueryEntities.ApplyBatch(Friflo.Engine.ECS.EntityBatch).batch 'Friflo.Engine.ECS.QueryEntities.ApplyBatch(Friflo.Engine.ECS.EntityBatch).batch') to all entities in this set.<br/> See <a href="https://github.com/friflo/Friflo.Json.Fliox/wiki/Examples-~-Optimization#entitybatch---query">Example.</a> |
| [GetEnumerator()](QueryEntities.GetEnumerator().md 'Friflo.Engine.ECS.QueryEntities.GetEnumerator()') | |
| [ToEntityList()](QueryEntities.ToEntityList().md 'Friflo.Engine.ECS.QueryEntities.ToEntityList()') | Returns the query result as an [EntityList](EntityList.md 'Friflo.Engine.ECS.EntityList') to perform structural changes. |
| [ToEntityList(EntityList)](QueryEntities.ToEntityList(EntityList).md 'Friflo.Engine.ECS.QueryEntities.ToEntityList(Friflo.Engine.ECS.EntityList)') | Returns the query result as an [EntityList](EntityList.md 'Friflo.Engine.ECS.EntityList') to perform structural changes. |
| [ToString()](QueryEntities.ToString().md 'Friflo.Engine.ECS.QueryEntities.ToString()') | |

| Explicit Interface Implementations | |
| :--- | :--- |
| [System.Collections.Generic.IEnumerable&lt;Friflo.Engine.ECS.Entity&gt;.GetEnumerator()](QueryEntities.System.Collections.Generic.IEnumerable_Friflo.Engine.ECS.Entity_.GetEnumerator().md 'Friflo.Engine.ECS.QueryEntities.System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.Entity>.GetEnumerator()') | |
| [System.Collections.IEnumerable.GetEnumerator()](QueryEntities.System.Collections.IEnumerable.GetEnumerator().md 'Friflo.Engine.ECS.QueryEntities.System.Collections.IEnumerable.GetEnumerator()') | |
