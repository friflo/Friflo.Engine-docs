#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## Relations<TRelation> Struct

Contains the relations of a specific entity returned by [GetRelations&lt;TRelation&gt;(this Entity)](RelationExtensions.GetRelations_TRelation_(thisEntity).md 'Friflo.Engine.ECS.RelationExtensions.GetRelations<TRelation>(this Friflo.Engine.ECS.Entity)').

```csharp
public readonly struct Relations<TRelation> :
System.Collections.Generic.IEnumerable<TRelation>,
System.Collections.IEnumerable
    where TRelation : struct, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.Relations_TRelation_.TRelation'></a>

`TRelation`

Implements [System.Collections.Generic.IEnumerable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1')[TRelation](Relations_TRelation_.md#Friflo.Engine.ECS.Relations_TRelation_.TRelation 'Friflo.Engine.ECS.Relations<TRelation>.TRelation')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1'), [System.Collections.IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerable 'System.Collections.IEnumerable')

| Fields | |
| :--- | :--- |
| [Length](Relations_TRelation_.Length.md 'Friflo.Engine.ECS.Relations<TRelation>.Length') | Return the number of relations.<br/> Executes in O(1). |

| Properties | |
| :--- | :--- |
| [this[int]](Relations_TRelation_.this[int].md 'Friflo.Engine.ECS.Relations<TRelation>.this[int]') | Return the relation at the given [index](Relations_TRelation_.this[int].md#Friflo.Engine.ECS.Relations_TRelation_.this[int].index 'Friflo.Engine.ECS.Relations<TRelation>.this[int].index').<br/> Executes in O(1). |

| Methods | |
| :--- | :--- |
| [Debug()](Relations_TRelation_.Debug().md 'Friflo.Engine.ECS.Relations<TRelation>.Debug()') | Returns a string containing the relation keys.<br/>E.g `"{ 1, 3, 7 }"` |
| [GetEnumerator()](Relations_TRelation_.GetEnumerator().md 'Friflo.Engine.ECS.Relations<TRelation>.GetEnumerator()') | |
| [ToString()](Relations_TRelation_.ToString().md 'Friflo.Engine.ECS.Relations<TRelation>.ToString()') | |

| Explicit Interface Implementations | |
| :--- | :--- |
| [System.Collections.Generic.IEnumerable&lt;TRelation&gt;.GetEnumerator()](Relations_TRelation_.System.Collections.Generic.IEnumerable_TRelation_.GetEnumerator().md 'Friflo.Engine.ECS.Relations<TRelation>.System.Collections.Generic.IEnumerable<TRelation>.GetEnumerator()') | |
| [System.Collections.IEnumerable.GetEnumerator()](Relations_TRelation_.System.Collections.IEnumerable.GetEnumerator().md 'Friflo.Engine.ECS.Relations<TRelation>.System.Collections.IEnumerable.GetEnumerator()') | |
