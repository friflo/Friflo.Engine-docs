#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## Chunks<T1> Struct

Contains the components returned by a component query.
See <a href="https://friflo.gitbook.io/friflo.engine.ecs/examples/optimization#enumerate-query-chunks">Example.</a>

```csharp
public readonly struct Chunks<T1>
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.Chunks_T1_.T1'></a>

`T1`

| Fields | |
| :--- | :--- |
| [Chunk1](Chunks_T1_.Chunk1.md 'Friflo.Engine.ECS.Chunks<T1>.Chunk1') | |
| [Entities](Chunks_T1_.Entities.md 'Friflo.Engine.ECS.Chunks<T1>.Entities') | |

| Properties | |
| :--- | :--- |
| [Length](Chunks_T1_.Length.md 'Friflo.Engine.ECS.Chunks<T1>.Length') | |

| Methods | |
| :--- | :--- |
| [Deconstruct(Chunk&lt;T1&gt;, ChunkEntities)](Chunks_T1_.Deconstruct(Chunk_T1_,ChunkEntities).md 'Friflo.Engine.ECS.Chunks<T1>.Deconstruct(Friflo.Engine.ECS.Chunk<T1>, Friflo.Engine.ECS.ChunkEntities)') | |
| [ToString()](Chunks_T1_.ToString().md 'Friflo.Engine.ECS.Chunks<T1>.ToString()') | |
