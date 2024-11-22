#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## QueryChunks<T1> Struct

Contains the component chunks returned by a component query.
See <a href="https://friflo.gitbook.io/friflo.engine.ecs/examples/optimization#enumerate-query-chunks">Example.</a>

```csharp
public readonly struct QueryChunks<T1> :
System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.Chunks<T1>>,
System.Collections.IEnumerable
    where T1 : struct, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.QueryChunks_T1_.T1'></a>

`T1`

Implements [System.Collections.Generic.IEnumerable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1')[Friflo.Engine.ECS.Chunks&lt;](Chunks_T1_.md 'Friflo.Engine.ECS.Chunks<T1>')[T1](QueryChunks_T1_.md#Friflo.Engine.ECS.QueryChunks_T1_.T1 'Friflo.Engine.ECS.QueryChunks<T1>.T1')[&gt;](Chunks_T1_.md 'Friflo.Engine.ECS.Chunks<T1>')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1'), [System.Collections.IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerable 'System.Collections.IEnumerable')

| Properties | |
| :--- | :--- |
| [Count](QueryChunks_T1_.Count.md 'Friflo.Engine.ECS.QueryChunks<T1>.Count') | |
| [EntityCount](QueryChunks_T1_.EntityCount.md 'Friflo.Engine.ECS.QueryChunks<T1>.EntityCount') | Obsolete. Renamed to [Count](QueryChunks_T1_.Count.md 'Friflo.Engine.ECS.QueryChunks<T1>.Count'). |

| Methods | |
| :--- | :--- |
| [GetEnumerator()](QueryChunks_T1_.GetEnumerator().md 'Friflo.Engine.ECS.QueryChunks<T1>.GetEnumerator()') | |
| [ToString()](QueryChunks_T1_.ToString().md 'Friflo.Engine.ECS.QueryChunks<T1>.ToString()') | |

| Explicit Interface Implementations | |
| :--- | :--- |
| [System.Collections.Generic.IEnumerable&lt;Friflo.Engine.ECS.Chunks&lt;T1&gt;&gt;.GetEnumerator()](QueryChunks_T1_.System.Collections.Generic.IEnumerable_Friflo.Engine.ECS.Chunks_T1__.GetEnumerator().md 'Friflo.Engine.ECS.QueryChunks<T1>.System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.Chunks<T1>>.GetEnumerator()') | |
| [System.Collections.IEnumerable.GetEnumerator()](QueryChunks_T1_.System.Collections.IEnumerable.GetEnumerator().md 'Friflo.Engine.ECS.QueryChunks<T1>.System.Collections.IEnumerable.GetEnumerator()') | |
