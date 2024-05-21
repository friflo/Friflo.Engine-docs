#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## Chunks<T1,T2> Struct

Contains the components returned by a component query.
See <a href="https://github.com/friflo/Friflo.Json.Fliox/wiki/Examples-~-Optimization#enumerate-query-chunks">Example.</a>

```csharp
public readonly struct Chunks<T1,T2>
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.Chunks_T1,T2_.T1'></a>

`T1`

<a name='Friflo.Engine.ECS.Chunks_T1,T2_.T2'></a>

`T2`

| Fields | |
| :--- | :--- |
| [Chunk1](Chunks_T1,T2_.Chunk1.md 'Friflo.Engine.ECS.Chunks<T1,T2>.Chunk1') | |
| [Chunk2](Chunks_T1,T2_.Chunk2.md 'Friflo.Engine.ECS.Chunks<T1,T2>.Chunk2') | |
| [Entities](Chunks_T1,T2_.Entities.md 'Friflo.Engine.ECS.Chunks<T1,T2>.Entities') | |

| Properties | |
| :--- | :--- |
| [Length](Chunks_T1,T2_.Length.md 'Friflo.Engine.ECS.Chunks<T1,T2>.Length') | |

| Methods | |
| :--- | :--- |
| [Deconstruct(Chunk&lt;T1&gt;, Chunk&lt;T2&gt;, ChunkEntities)](Chunks_T1,T2_.Deconstruct(Chunk_T1_,Chunk_T2_,ChunkEntities).md 'Friflo.Engine.ECS.Chunks<T1,T2>.Deconstruct(Friflo.Engine.ECS.Chunk<T1>, Friflo.Engine.ECS.Chunk<T2>, Friflo.Engine.ECS.ChunkEntities)') | |
| [ToString()](Chunks_T1,T2_.ToString().md 'Friflo.Engine.ECS.Chunks<T1,T2>.ToString()') | |
