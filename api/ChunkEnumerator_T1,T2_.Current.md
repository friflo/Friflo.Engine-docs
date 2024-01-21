#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[ChunkEnumerator&lt;T1,T2&gt;](ChunkEnumerator_T1,T2_.md 'Friflo.Engine.ECS.ChunkEnumerator<T1,T2>')

## ChunkEnumerator<T1,T2>.Current Property

return Current by reference to avoid struct copy and enable mutation in library

```csharp
public readonly Friflo.Engine.ECS.Chunks<T1,T2> Current { get; }
```

Implements [Current](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerator-1.Current 'System.Collections.Generic.IEnumerator`1.Current'), [Current](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerator.Current 'System.Collections.IEnumerator.Current')

#### Property Value
[Friflo.Engine.ECS.Chunks&lt;](Chunks_T1,T2_.md 'Friflo.Engine.ECS.Chunks<T1,T2>')[T1](ChunkEnumerator_T1,T2_.md#Friflo.Engine.ECS.ChunkEnumerator_T1,T2_.T1 'Friflo.Engine.ECS.ChunkEnumerator<T1,T2>.T1')[,](Chunks_T1,T2_.md 'Friflo.Engine.ECS.Chunks<T1,T2>')[T2](ChunkEnumerator_T1,T2_.md#Friflo.Engine.ECS.ChunkEnumerator_T1,T2_.T2 'Friflo.Engine.ECS.ChunkEnumerator<T1,T2>.T2')[&gt;](Chunks_T1,T2_.md 'Friflo.Engine.ECS.Chunks<T1,T2>')