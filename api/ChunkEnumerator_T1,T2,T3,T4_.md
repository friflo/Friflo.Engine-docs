#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ChunkEnumerator<T1,T2,T3,T4> Struct

```csharp
public struct ChunkEnumerator<T1,T2,T3,T4> :
System.Collections.Generic.IEnumerator<Friflo.Engine.ECS.Chunks<T1, T2, T3, T4>>,
System.Collections.IEnumerator,
System.IDisposable
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T4 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.ChunkEnumerator_T1,T2,T3,T4_.T1'></a>

`T1`

<a name='Friflo.Engine.ECS.ChunkEnumerator_T1,T2,T3,T4_.T2'></a>

`T2`

<a name='Friflo.Engine.ECS.ChunkEnumerator_T1,T2,T3,T4_.T3'></a>

`T3`

<a name='Friflo.Engine.ECS.ChunkEnumerator_T1,T2,T3,T4_.T4'></a>

`T4`

Implements [System.Collections.Generic.IEnumerator&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerator-1 'System.Collections.Generic.IEnumerator`1')[Friflo.Engine.ECS.Chunks&lt;](Chunks_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4>')[T1](ChunkEnumerator_T1,T2,T3,T4_.md#Friflo.Engine.ECS.ChunkEnumerator_T1,T2,T3,T4_.T1 'Friflo.Engine.ECS.ChunkEnumerator<T1,T2,T3,T4>.T1')[,](Chunks_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4>')[T2](ChunkEnumerator_T1,T2,T3,T4_.md#Friflo.Engine.ECS.ChunkEnumerator_T1,T2,T3,T4_.T2 'Friflo.Engine.ECS.ChunkEnumerator<T1,T2,T3,T4>.T2')[,](Chunks_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4>')[T3](ChunkEnumerator_T1,T2,T3,T4_.md#Friflo.Engine.ECS.ChunkEnumerator_T1,T2,T3,T4_.T3 'Friflo.Engine.ECS.ChunkEnumerator<T1,T2,T3,T4>.T3')[,](Chunks_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4>')[T4](ChunkEnumerator_T1,T2,T3,T4_.md#Friflo.Engine.ECS.ChunkEnumerator_T1,T2,T3,T4_.T4 'Friflo.Engine.ECS.ChunkEnumerator<T1,T2,T3,T4>.T4')[&gt;](Chunks_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4>')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerator-1 'System.Collections.Generic.IEnumerator`1'), [System.Collections.IEnumerator](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerator 'System.Collections.IEnumerator'), [System.IDisposable](https://docs.microsoft.com/en-us/dotnet/api/System.IDisposable 'System.IDisposable')

| Properties | |
| :--- | :--- |
| [Current](ChunkEnumerator_T1,T2,T3,T4_.Current.md 'Friflo.Engine.ECS.ChunkEnumerator<T1,T2,T3,T4>.Current') | return Current by reference to avoid struct copy and enable mutation in library |

| Methods | |
| :--- | :--- |
| [Dispose()](ChunkEnumerator_T1,T2,T3,T4_.Dispose().md 'Friflo.Engine.ECS.ChunkEnumerator<T1,T2,T3,T4>.Dispose()') | |
| [MoveNext()](ChunkEnumerator_T1,T2,T3,T4_.MoveNext().md 'Friflo.Engine.ECS.ChunkEnumerator<T1,T2,T3,T4>.MoveNext()') | |
| [Reset()](ChunkEnumerator_T1,T2,T3,T4_.Reset().md 'Friflo.Engine.ECS.ChunkEnumerator<T1,T2,T3,T4>.Reset()') | |

| Explicit Interface Implementations | |
| :--- | :--- |
| [System.Collections.IEnumerator.Current](ChunkEnumerator_T1,T2,T3,T4_.System.Collections.IEnumerator.Current.md 'Friflo.Engine.ECS.ChunkEnumerator<T1,T2,T3,T4>.System.Collections.IEnumerator.Current') | |
