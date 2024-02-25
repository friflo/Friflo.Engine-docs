#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## Chunks<T1,T2,T3> Struct

Contains the components returned by a component query.
See <a href="https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md#enumerate-query-chunks">Example.</a>

```csharp
public readonly struct Chunks<T1,T2,T3>
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.Chunks_T1,T2,T3_.T1'></a>

`T1`

<a name='Friflo.Engine.ECS.Chunks_T1,T2,T3_.T2'></a>

`T2`

<a name='Friflo.Engine.ECS.Chunks_T1,T2,T3_.T3'></a>

`T3`

| Fields | |
| :--- | :--- |
| [Chunk1](Chunks_T1,T2,T3_.Chunk1.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3>.Chunk1') | |
| [Chunk2](Chunks_T1,T2,T3_.Chunk2.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3>.Chunk2') | |
| [Chunk3](Chunks_T1,T2,T3_.Chunk3.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3>.Chunk3') | |
| [Entities](Chunks_T1,T2,T3_.Entities.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3>.Entities') | |

| Properties | |
| :--- | :--- |
| [Length](Chunks_T1,T2,T3_.Length.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3>.Length') | |

| Methods | |
| :--- | :--- |
| [Deconstruct(Chunk&lt;T1&gt;, Chunk&lt;T2&gt;, Chunk&lt;T3&gt;, ChunkEntities)](Chunks_T1,T2,T3_.Deconstruct(Chunk_T1_,Chunk_T2_,Chunk_T3_,ChunkEntities).md 'Friflo.Engine.ECS.Chunks<T1,T2,T3>.Deconstruct(Friflo.Engine.ECS.Chunk<T1>, Friflo.Engine.ECS.Chunk<T2>, Friflo.Engine.ECS.Chunk<T3>, Friflo.Engine.ECS.ChunkEntities)') | |
| [ToString()](Chunks_T1,T2,T3_.ToString().md 'Friflo.Engine.ECS.Chunks<T1,T2,T3>.ToString()') | |
