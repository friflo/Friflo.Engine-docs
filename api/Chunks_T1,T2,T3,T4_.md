#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## Chunks<T1,T2,T3,T4> Struct

Contains the components returned by a component query.
See <a href="https://friflo.gitbook.io/friflo.engine.ecs/examples/optimization#enumerate-query-chunks">Example.</a>

```csharp
public readonly struct Chunks<T1,T2,T3,T4>
    where T1 : struct, System.ValueType, System.ValueType
    where T2 : struct, System.ValueType, System.ValueType
    where T3 : struct, System.ValueType, System.ValueType
    where T4 : struct, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.Chunks_T1,T2,T3,T4_.T1'></a>

`T1`

<a name='Friflo.Engine.ECS.Chunks_T1,T2,T3,T4_.T2'></a>

`T2`

<a name='Friflo.Engine.ECS.Chunks_T1,T2,T3,T4_.T3'></a>

`T3`

<a name='Friflo.Engine.ECS.Chunks_T1,T2,T3,T4_.T4'></a>

`T4`

| Fields | |
| :--- | :--- |
| [Chunk1](Chunks_T1,T2,T3,T4_.Chunk1.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4>.Chunk1') | |
| [Chunk2](Chunks_T1,T2,T3,T4_.Chunk2.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4>.Chunk2') | |
| [Chunk3](Chunks_T1,T2,T3,T4_.Chunk3.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4>.Chunk3') | |
| [Chunk4](Chunks_T1,T2,T3,T4_.Chunk4.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4>.Chunk4') | |
| [Entities](Chunks_T1,T2,T3,T4_.Entities.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4>.Entities') | |

| Properties | |
| :--- | :--- |
| [Length](Chunks_T1,T2,T3,T4_.Length.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4>.Length') | |

| Methods | |
| :--- | :--- |
| [Deconstruct(Chunk&lt;T1&gt;, Chunk&lt;T2&gt;, Chunk&lt;T3&gt;, Chunk&lt;T4&gt;, ChunkEntities)](Chunks_T1,T2,T3,T4_.Deconstruct(Chunk_T1_,Chunk_T2_,Chunk_T3_,Chunk_T4_,ChunkEntities).md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4>.Deconstruct(Friflo.Engine.ECS.Chunk<T1>, Friflo.Engine.ECS.Chunk<T2>, Friflo.Engine.ECS.Chunk<T3>, Friflo.Engine.ECS.Chunk<T4>, Friflo.Engine.ECS.ChunkEntities)') | |
| [ToString()](Chunks_T1,T2,T3,T4_.ToString().md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4>.ToString()') | |
