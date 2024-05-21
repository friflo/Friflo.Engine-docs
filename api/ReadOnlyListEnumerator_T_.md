#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ReadOnlyListEnumerator<T> Struct

Enumerates the elements of a [ReadOnlyList&lt;T&gt;](ReadOnlyList_T_.md 'Friflo.Engine.ECS.ReadOnlyList<T>').

```csharp
public struct ReadOnlyListEnumerator<T> :
System.Collections.Generic.IEnumerator<T>,
System.Collections.IEnumerator,
System.IDisposable
    where T : class
```
#### Type parameters

<a name='Friflo.Engine.ECS.ReadOnlyListEnumerator_T_.T'></a>

`T`

Implements [System.Collections.Generic.IEnumerator&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerator-1 'System.Collections.Generic.IEnumerator`1')[T](ReadOnlyListEnumerator_T_.md#Friflo.Engine.ECS.ReadOnlyListEnumerator_T_.T 'Friflo.Engine.ECS.ReadOnlyListEnumerator<T>.T')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerator-1 'System.Collections.Generic.IEnumerator`1'), [System.Collections.IEnumerator](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerator 'System.Collections.IEnumerator'), [System.IDisposable](https://docs.microsoft.com/en-us/dotnet/api/System.IDisposable 'System.IDisposable')

| Properties | |
| :--- | :--- |
| [Current](ReadOnlyListEnumerator_T_.Current.md 'Friflo.Engine.ECS.ReadOnlyListEnumerator<T>.Current') | Gets the element at the current position of the enumerator. |

| Methods | |
| :--- | :--- |
| [Dispose()](ReadOnlyListEnumerator_T_.Dispose().md 'Friflo.Engine.ECS.ReadOnlyListEnumerator<T>.Dispose()') | Releases all resources used by the list enumerator. |
| [MoveNext()](ReadOnlyListEnumerator_T_.MoveNext().md 'Friflo.Engine.ECS.ReadOnlyListEnumerator<T>.MoveNext()') | Advances the enumerator to the next element of the collection. |
| [Reset()](ReadOnlyListEnumerator_T_.Reset().md 'Friflo.Engine.ECS.ReadOnlyListEnumerator<T>.Reset()') | Sets the enumerator to its initial position, which is before the first element in the list. |

| Explicit Interface Implementations | |
| :--- | :--- |
| [System.Collections.IEnumerator.Current](ReadOnlyListEnumerator_T_.System.Collections.IEnumerator.Current.md 'Friflo.Engine.ECS.ReadOnlyListEnumerator<T>.System.Collections.IEnumerator.Current') | |
