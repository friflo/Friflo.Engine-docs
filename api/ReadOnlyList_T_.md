#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ReadOnlyList<T> Struct

Represents a strongly typed readonly list of objects that can be accessed by index.

```csharp
public struct ReadOnlyList<T> :
System.Collections.Generic.IReadOnlyList<T>,
System.Collections.Generic.IEnumerable<T>,
System.Collections.IEnumerable,
System.Collections.Generic.IReadOnlyCollection<T>
    where T : class
```
#### Type parameters

<a name='Friflo.Engine.ECS.ReadOnlyList_T_.T'></a>

`T`

Implements [System.Collections.Generic.IReadOnlyList&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyList-1 'System.Collections.Generic.IReadOnlyList`1')[T](ReadOnlyList_T_.md#Friflo.Engine.ECS.ReadOnlyList_T_.T 'Friflo.Engine.ECS.ReadOnlyList<T>.T')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyList-1 'System.Collections.Generic.IReadOnlyList`1'), [System.Collections.Generic.IEnumerable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1')[T](ReadOnlyList_T_.md#Friflo.Engine.ECS.ReadOnlyList_T_.T 'Friflo.Engine.ECS.ReadOnlyList<T>.T')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1'), [System.Collections.IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerable 'System.Collections.IEnumerable'), [System.Collections.Generic.IReadOnlyCollection&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')[T](ReadOnlyList_T_.md#Friflo.Engine.ECS.ReadOnlyList_T_.T 'Friflo.Engine.ECS.ReadOnlyList<T>.T')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')

| Properties | |
| :--- | :--- |
| [Count](ReadOnlyList_T_.Count.md 'Friflo.Engine.ECS.ReadOnlyList<T>.Count') | Returns the number of elements contained in the list. |
| [Span](ReadOnlyList_T_.Span.md 'Friflo.Engine.ECS.ReadOnlyList<T>.Span') | Returns an [System.ReadOnlySpan&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.ReadOnlySpan-1 'System.ReadOnlySpan`1') of the list elements. |
| [this[int]](ReadOnlyList_T_.this[int].md 'Friflo.Engine.ECS.ReadOnlyList<T>.this[int]') | Gets the element at the specified index. |

| Methods | |
| :--- | :--- |
| [GetEnumerator()](ReadOnlyList_T_.GetEnumerator().md 'Friflo.Engine.ECS.ReadOnlyList<T>.GetEnumerator()') | Returns an enumerator that iterates through the list. |
| [IndexOf(T)](ReadOnlyList_T_.IndexOf(T).md 'Friflo.Engine.ECS.ReadOnlyList<T>.IndexOf(T)') | Returns the zero-based index of the first occurrence of a value within the entire list. |
| [ToString()](ReadOnlyList_T_.ToString().md 'Friflo.Engine.ECS.ReadOnlyList<T>.ToString()') | |

| Explicit Interface Implementations | |
| :--- | :--- |
| [System.Collections.Generic.IEnumerable&lt;T&gt;.GetEnumerator()](ReadOnlyList_T_.System.Collections.Generic.IEnumerable_T_.GetEnumerator().md 'Friflo.Engine.ECS.ReadOnlyList<T>.System.Collections.Generic.IEnumerable<T>.GetEnumerator()') | |
| [System.Collections.IEnumerable.GetEnumerator()](ReadOnlyList_T_.System.Collections.IEnumerable.GetEnumerator().md 'Friflo.Engine.ECS.ReadOnlyList<T>.System.Collections.IEnumerable.GetEnumerator()') | |
