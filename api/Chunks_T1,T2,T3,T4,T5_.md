#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## Chunks<T1,T2,T3,T4,T5> Struct

Contains the components returned by a component query.
See <a href="https://friflo.gitbook.io/friflo.engine.ecs/examples/optimization#enumerate-query-chunks">Example.</a>

```csharp
public readonly struct Chunks<T1,T2,T3,T4,T5>
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T4 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T5 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.Chunks_T1,T2,T3,T4,T5_.T1'></a>

`T1`

<a name='Friflo.Engine.ECS.Chunks_T1,T2,T3,T4,T5_.T2'></a>

`T2`

<a name='Friflo.Engine.ECS.Chunks_T1,T2,T3,T4,T5_.T3'></a>

`T3`

<a name='Friflo.Engine.ECS.Chunks_T1,T2,T3,T4,T5_.T4'></a>

`T4`

<a name='Friflo.Engine.ECS.Chunks_T1,T2,T3,T4,T5_.T5'></a>

`T5`

| Fields | |
| :--- | :--- |
| [Chunk1](Chunks_T1,T2,T3,T4,T5_.Chunk1.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4,T5>.Chunk1') | |
| [Chunk2](Chunks_T1,T2,T3,T4,T5_.Chunk2.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4,T5>.Chunk2') | |
| [Chunk3](Chunks_T1,T2,T3,T4,T5_.Chunk3.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4,T5>.Chunk3') | |
| [Chunk4](Chunks_T1,T2,T3,T4,T5_.Chunk4.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4,T5>.Chunk4') | |
| [Chunk5](Chunks_T1,T2,T3,T4,T5_.Chunk5.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4,T5>.Chunk5') | |
| [Entities](Chunks_T1,T2,T3,T4,T5_.Entities.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4,T5>.Entities') | |

| Properties | |
| :--- | :--- |
| [Length](Chunks_T1,T2,T3,T4,T5_.Length.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4,T5>.Length') | |

| Methods | |
| :--- | :--- |
| [Deconstruct(Chunk&lt;T1&gt;, Chunk&lt;T2&gt;, Chunk&lt;T3&gt;, Chunk&lt;T4&gt;, Chunk&lt;T5&gt;, ChunkEntities)](Chunks_T1,T2,T3,T4,T5_.Deconstruct(Chunk_T1_,Chunk_T2_,Chunk_T3_,Chunk_T4_,Chunk_T5_,ChunkEntities).md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4,T5>.Deconstruct(Friflo.Engine.ECS.Chunk<T1>, Friflo.Engine.ECS.Chunk<T2>, Friflo.Engine.ECS.Chunk<T3>, Friflo.Engine.ECS.Chunk<T4>, Friflo.Engine.ECS.Chunk<T5>, Friflo.Engine.ECS.ChunkEntities)') | |
| [ToString()](Chunks_T1,T2,T3,T4,T5_.ToString().md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4,T5>.ToString()') | |
