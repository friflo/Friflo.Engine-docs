#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ChunkEnumerator<T1> Struct

```csharp
public struct ChunkEnumerator<T1> :
System.Collections.Generic.IEnumerator<Friflo.Engine.ECS.Chunks<T1>>,
System.Collections.IEnumerator,
System.IDisposable
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.ChunkEnumerator_T1_.T1'></a>

`T1`

Implements [System.Collections.Generic.IEnumerator&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerator-1 'System.Collections.Generic.IEnumerator`1')[Friflo.Engine.ECS.Chunks&lt;](Chunks_T1_.md 'Friflo.Engine.ECS.Chunks<T1>')[T1](ChunkEnumerator_T1_.md#Friflo.Engine.ECS.ChunkEnumerator_T1_.T1 'Friflo.Engine.ECS.ChunkEnumerator<T1>.T1')[&gt;](Chunks_T1_.md 'Friflo.Engine.ECS.Chunks<T1>')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerator-1 'System.Collections.Generic.IEnumerator`1'), [System.Collections.IEnumerator](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerator 'System.Collections.IEnumerator'), [System.IDisposable](https://docs.microsoft.com/en-us/dotnet/api/System.IDisposable 'System.IDisposable')

| Properties | |
| :--- | :--- |
| [Current](ChunkEnumerator_T1_.Current.md 'Friflo.Engine.ECS.ChunkEnumerator<T1>.Current') | return Current by reference to avoid struct copy and enable mutation in library |

| Methods | |
| :--- | :--- |
| [Dispose()](ChunkEnumerator_T1_.Dispose().md 'Friflo.Engine.ECS.ChunkEnumerator<T1>.Dispose()') | |
| [MoveNext()](ChunkEnumerator_T1_.MoveNext().md 'Friflo.Engine.ECS.ChunkEnumerator<T1>.MoveNext()') | |
| [Reset()](ChunkEnumerator_T1_.Reset().md 'Friflo.Engine.ECS.ChunkEnumerator<T1>.Reset()') | |

| Explicit Interface Implementations | |
| :--- | :--- |
| [System.Collections.IEnumerator.Current](ChunkEnumerator_T1_.System.Collections.IEnumerator.Current.md 'Friflo.Engine.ECS.ChunkEnumerator<T1>.System.Collections.IEnumerator.Current') | |
