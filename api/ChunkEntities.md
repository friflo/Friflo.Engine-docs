#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ChunkEntities Struct

Provide the entity [Id](Entity.Id.md 'Friflo.Engine.ECS.Entity.Id')'s for [Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>') components using [Ids](ChunkEntities.Ids.md 'Friflo.Engine.ECS.ChunkEntities.Ids') or [this[int]](ChunkEntities.this[int].md 'Friflo.Engine.ECS.ChunkEntities.this[int]').<br/>

```csharp
public readonly struct ChunkEntities :
System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.Entity>,
System.Collections.IEnumerable
```

Implements [System.Collections.Generic.IEnumerable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1')[Entity](Entity.md 'Friflo.Engine.ECS.Entity')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1'), [System.Collections.IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerable 'System.Collections.IEnumerable')

### Remarks
Its [Length](ChunkEntities.Length.md 'Friflo.Engine.ECS.ChunkEntities.Length') is equal to the [Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>').[Length](Chunk_T_.Length.md 'Friflo.Engine.ECS.Chunk<T>.Length').<br/><br/>
It implements [System.Collections.Generic.IEnumerable&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1') only to provide comprehensive information of [Entity](Entity.md 'Friflo.Engine.ECS.Entity')'s in a debugger.<br/>
Its unlikely to enumerate [ChunkEntities](ChunkEntities.md 'Friflo.Engine.ECS.ChunkEntities') in an application.<br/>
The recommended methods used by an application are [Ids](ChunkEntities.Ids.md 'Friflo.Engine.ECS.ChunkEntities.Ids'), [this[int]](ChunkEntities.this[int].md 'Friflo.Engine.ECS.ChunkEntities.this[int]') or [EntityAt(int)](ChunkEntities.EntityAt(int).md 'Friflo.Engine.ECS.ChunkEntities.EntityAt(int)').

| Fields | |
| :--- | :--- |
| [Archetype](ChunkEntities.Archetype.md 'Friflo.Engine.ECS.ChunkEntities.Archetype') | The [Archetype](ChunkEntities.Archetype.md 'Friflo.Engine.ECS.ChunkEntities.Archetype') containing the [Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>') components. |
| [Execution](ChunkEntities.Execution.md 'Friflo.Engine.ECS.ChunkEntities.Execution') | The execution type used to provide the chunk entities. |
| [Length](ChunkEntities.Length.md 'Friflo.Engine.ECS.ChunkEntities.Length') | The number of entities in [ChunkEntities](ChunkEntities.md 'Friflo.Engine.ECS.ChunkEntities'). |
| [TaskIndex](ChunkEntities.TaskIndex.md 'Friflo.Engine.ECS.ChunkEntities.TaskIndex') | if    0 - The entities are provided from the main (caller) thread using `foreach(...)` loop, [Run()](QueryJob.Run().md 'Friflo.Engine.ECS.QueryJob.Run()') or [RunParallel()](QueryJob.RunParallel().md 'Friflo.Engine.ECS.QueryJob.RunParallel()').<br/> if >= 1 - The entities are provided from a worker thread using [RunParallel()](QueryJob.RunParallel().md 'Friflo.Engine.ECS.QueryJob.RunParallel()'). |

| Properties | |
| :--- | :--- |
| [Ids](ChunkEntities.Ids.md 'Friflo.Engine.ECS.ChunkEntities.Ids') | Return the entity [Id](Entity.Id.md 'Friflo.Engine.ECS.Entity.Id')'s for the components in a [Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>'). |
| [this[int]](ChunkEntities.this[int].md 'Friflo.Engine.ECS.ChunkEntities.this[int]') | Return the entity [Id](Entity.Id.md 'Friflo.Engine.ECS.Entity.Id') for a [Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>') component at the given [index](ChunkEntities.this[int].md#Friflo.Engine.ECS.ChunkEntities.this[int].index 'Friflo.Engine.ECS.ChunkEntities.this[int].index'). |

| Methods | |
| :--- | :--- |
| [EntityAt(int)](ChunkEntities.EntityAt(int).md 'Friflo.Engine.ECS.ChunkEntities.EntityAt(int)') | Return the [Entity](Entity.md 'Friflo.Engine.ECS.Entity') for a [Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>') component at the given [index](ChunkEntities.EntityAt(int).md#Friflo.Engine.ECS.ChunkEntities.EntityAt(int).index 'Friflo.Engine.ECS.ChunkEntities.EntityAt(int).index'). |
| [GetEnumerator()](ChunkEntities.GetEnumerator().md 'Friflo.Engine.ECS.ChunkEntities.GetEnumerator()') | |
| [ToString()](ChunkEntities.ToString().md 'Friflo.Engine.ECS.ChunkEntities.ToString()') | |

| Explicit Interface Implementations | |
| :--- | :--- |
| [System.Collections.Generic.IEnumerable&lt;Friflo.Engine.ECS.Entity&gt;.GetEnumerator()](ChunkEntities.System.Collections.Generic.IEnumerable_Friflo.Engine.ECS.Entity_.GetEnumerator().md 'Friflo.Engine.ECS.ChunkEntities.System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.Entity>.GetEnumerator()') | |
| [System.Collections.IEnumerable.GetEnumerator()](ChunkEntities.System.Collections.IEnumerable.GetEnumerator().md 'Friflo.Engine.ECS.ChunkEntities.System.Collections.IEnumerable.GetEnumerator()') | |
