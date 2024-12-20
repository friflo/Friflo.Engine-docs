#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## QueryChunks<T1,T2,T3,T4> Struct

Contains the component chunks returned by a component query.
See <a href="https://friflo.gitbook.io/friflo.engine.ecs/examples/optimization#enumerate-query-chunks">Example.</a>

```csharp
public readonly struct QueryChunks<T1,T2,T3,T4> :
System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.Chunks<T1, T2, T3, T4>>,
System.Collections.IEnumerable
    where T1 : struct, System.ValueType, System.ValueType
    where T2 : struct, System.ValueType, System.ValueType
    where T3 : struct, System.ValueType, System.ValueType
    where T4 : struct, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.QueryChunks_T1,T2,T3,T4_.T1'></a>

`T1`

<a name='Friflo.Engine.ECS.QueryChunks_T1,T2,T3,T4_.T2'></a>

`T2`

<a name='Friflo.Engine.ECS.QueryChunks_T1,T2,T3,T4_.T3'></a>

`T3`

<a name='Friflo.Engine.ECS.QueryChunks_T1,T2,T3,T4_.T4'></a>

`T4`

Implements [System.Collections.Generic.IEnumerable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1')[Friflo.Engine.ECS.Chunks&lt;](Chunks_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4>')[T1](QueryChunks_T1,T2,T3,T4_.md#Friflo.Engine.ECS.QueryChunks_T1,T2,T3,T4_.T1 'Friflo.Engine.ECS.QueryChunks<T1,T2,T3,T4>.T1')[,](Chunks_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4>')[T2](QueryChunks_T1,T2,T3,T4_.md#Friflo.Engine.ECS.QueryChunks_T1,T2,T3,T4_.T2 'Friflo.Engine.ECS.QueryChunks<T1,T2,T3,T4>.T2')[,](Chunks_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4>')[T3](QueryChunks_T1,T2,T3,T4_.md#Friflo.Engine.ECS.QueryChunks_T1,T2,T3,T4_.T3 'Friflo.Engine.ECS.QueryChunks<T1,T2,T3,T4>.T3')[,](Chunks_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4>')[T4](QueryChunks_T1,T2,T3,T4_.md#Friflo.Engine.ECS.QueryChunks_T1,T2,T3,T4_.T4 'Friflo.Engine.ECS.QueryChunks<T1,T2,T3,T4>.T4')[&gt;](Chunks_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4>')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1'), [System.Collections.IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerable 'System.Collections.IEnumerable')

| Properties | |
| :--- | :--- |
| [Count](QueryChunks_T1,T2,T3,T4_.Count.md 'Friflo.Engine.ECS.QueryChunks<T1,T2,T3,T4>.Count') | |
| [EntityCount](QueryChunks_T1,T2,T3,T4_.EntityCount.md 'Friflo.Engine.ECS.QueryChunks<T1,T2,T3,T4>.EntityCount') | Obsolete. Renamed to [Count](QueryChunks_T1,T2,T3,T4_.Count.md 'Friflo.Engine.ECS.QueryChunks<T1,T2,T3,T4>.Count'). |

| Methods | |
| :--- | :--- |
| [GetEnumerator()](QueryChunks_T1,T2,T3,T4_.GetEnumerator().md 'Friflo.Engine.ECS.QueryChunks<T1,T2,T3,T4>.GetEnumerator()') | |
| [ToString()](QueryChunks_T1,T2,T3,T4_.ToString().md 'Friflo.Engine.ECS.QueryChunks<T1,T2,T3,T4>.ToString()') | |

| Explicit Interface Implementations | |
| :--- | :--- |
| [System.Collections.Generic.IEnumerable&lt;Friflo.Engine.ECS.Chunks&lt;T1,T2,T3,T4&gt;&gt;.GetEnumerator()](QueryChunks_T1,T2,T3,T4_.System.Collections.Generic.IEnumerable_Friflo.Engine.ECS.Chunks_T1,T2,T3,T4__.GetEnumerator().md 'Friflo.Engine.ECS.QueryChunks<T1,T2,T3,T4>.System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.Chunks<T1,T2,T3,T4>>.GetEnumerator()') | |
| [System.Collections.IEnumerable.GetEnumerator()](QueryChunks_T1,T2,T3,T4_.System.Collections.IEnumerable.GetEnumerator().md 'Friflo.Engine.ECS.QueryChunks<T1,T2,T3,T4>.System.Collections.IEnumerable.GetEnumerator()') | |
