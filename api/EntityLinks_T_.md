#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## EntityLinks<T> Struct

```csharp
public readonly struct EntityLinks<T> :
System.Collections.Generic.IReadOnlyList<Friflo.Engine.ECS.EntityLink<T>>,
System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.EntityLink<T>>,
System.Collections.IEnumerable,
System.Collections.Generic.IReadOnlyCollection<Friflo.Engine.ECS.EntityLink<T>>
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityLinks_T_.T'></a>

`T`

Implements [System.Collections.Generic.IReadOnlyList&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyList-1 'System.Collections.Generic.IReadOnlyList`1')[Friflo.Engine.ECS.EntityLink&lt;](EntityLink_TComponent_.md 'Friflo.Engine.ECS.EntityLink<TComponent>')[T](EntityLinks_T_.md#Friflo.Engine.ECS.EntityLinks_T_.T 'Friflo.Engine.ECS.EntityLinks<T>.T')[&gt;](EntityLink_TComponent_.md 'Friflo.Engine.ECS.EntityLink<TComponent>')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyList-1 'System.Collections.Generic.IReadOnlyList`1'), [System.Collections.Generic.IEnumerable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1')[Friflo.Engine.ECS.EntityLink&lt;](EntityLink_TComponent_.md 'Friflo.Engine.ECS.EntityLink<TComponent>')[T](EntityLinks_T_.md#Friflo.Engine.ECS.EntityLinks_T_.T 'Friflo.Engine.ECS.EntityLinks<T>.T')[&gt;](EntityLink_TComponent_.md 'Friflo.Engine.ECS.EntityLink<TComponent>')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1'), [System.Collections.IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerable 'System.Collections.IEnumerable'), [System.Collections.Generic.IReadOnlyCollection&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')[Friflo.Engine.ECS.EntityLink&lt;](EntityLink_TComponent_.md 'Friflo.Engine.ECS.EntityLink<TComponent>')[T](EntityLinks_T_.md#Friflo.Engine.ECS.EntityLinks_T_.T 'Friflo.Engine.ECS.EntityLinks<T>.T')[&gt;](EntityLink_TComponent_.md 'Friflo.Engine.ECS.EntityLink<TComponent>')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')

| Fields | |
| :--- | :--- |
| [Entities](EntityLinks_T_.Entities.md 'Friflo.Engine.ECS.EntityLinks<T>.Entities') | |

| Properties | |
| :--- | :--- |
| [Count](EntityLinks_T_.Count.md 'Friflo.Engine.ECS.EntityLinks<T>.Count') | |
| [Store](EntityLinks_T_.Store.md 'Friflo.Engine.ECS.EntityLinks<T>.Store') | |
| [this[int]](EntityLinks_T_.this[int].md 'Friflo.Engine.ECS.EntityLinks<T>.this[int]') | |

| Methods | |
| :--- | :--- |
| [Debug()](EntityLinks_T_.Debug().md 'Friflo.Engine.ECS.EntityLinks<T>.Debug()') | Return the entity ids as a string.<br/>E.g `"{ 1, 3, 7 }"` |
| [GetEnumerator()](EntityLinks_T_.GetEnumerator().md 'Friflo.Engine.ECS.EntityLinks<T>.GetEnumerator()') | |
| [ToString()](EntityLinks_T_.ToString().md 'Friflo.Engine.ECS.EntityLinks<T>.ToString()') | |

| Explicit Interface Implementations | |
| :--- | :--- |
| [System.Collections.Generic.IEnumerable&lt;Friflo.Engine.ECS.EntityLink&lt;T&gt;&gt;.GetEnumerator()](EntityLinks_T_.System.Collections.Generic.IEnumerable_Friflo.Engine.ECS.EntityLink_T__.GetEnumerator().md 'Friflo.Engine.ECS.EntityLinks<T>.System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.EntityLink<T>>.GetEnumerator()') | |
| [System.Collections.IEnumerable.GetEnumerator()](EntityLinks_T_.System.Collections.IEnumerable.GetEnumerator().md 'Friflo.Engine.ECS.EntityLinks<T>.System.Collections.IEnumerable.GetEnumerator()') | |
