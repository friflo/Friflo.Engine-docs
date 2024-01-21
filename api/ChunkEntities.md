#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ChunkEntities Struct

Provide the entity id for each [Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>').[Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>') element with [Ids](ChunkEntities.Ids.md 'Friflo.Engine.ECS.ChunkEntities.Ids') or [this[int]](ChunkEntities.this[int].md 'Friflo.Engine.ECS.ChunkEntities.this[int]').<br/>

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
| [Archetype](ChunkEntities.Archetype.md 'Friflo.Engine.ECS.ChunkEntities.Archetype') | |
| [Length](ChunkEntities.Length.md 'Friflo.Engine.ECS.ChunkEntities.Length') | |

| Properties | |
| :--- | :--- |
| [Ids](ChunkEntities.Ids.md 'Friflo.Engine.ECS.ChunkEntities.Ids') | |
| [this[int]](ChunkEntities.this[int].md 'Friflo.Engine.ECS.ChunkEntities.this[int]') | |

| Methods | |
| :--- | :--- |
| [EntityAt(int)](ChunkEntities.EntityAt(int).md 'Friflo.Engine.ECS.ChunkEntities.EntityAt(int)') | |
| [GetEnumerator()](ChunkEntities.GetEnumerator().md 'Friflo.Engine.ECS.ChunkEntities.GetEnumerator()') | |
| [ToString()](ChunkEntities.ToString().md 'Friflo.Engine.ECS.ChunkEntities.ToString()') | |

| Explicit Interface Implementations | |
| :--- | :--- |
| [System.Collections.Generic.IEnumerable&lt;Friflo.Engine.ECS.Entity&gt;.GetEnumerator()](ChunkEntities.System.Collections.Generic.IEnumerable_Friflo.Engine.ECS.Entity_.GetEnumerator().md 'Friflo.Engine.ECS.ChunkEntities.System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.Entity>.GetEnumerator()') | |
| [System.Collections.IEnumerable.GetEnumerator()](ChunkEntities.System.Collections.IEnumerable.GetEnumerator().md 'Friflo.Engine.ECS.ChunkEntities.System.Collections.IEnumerable.GetEnumerator()') | |
