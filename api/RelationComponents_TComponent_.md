#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## RelationComponents<TComponent> Struct

Contains the relation components of a specific entity returned by [GetRelations&lt;TComponent&gt;(this Entity)](RelationExtensions.GetRelations_TComponent_(thisEntity).md 'Friflo.Engine.ECS.RelationExtensions.GetRelations<TComponent>(this Friflo.Engine.ECS.Entity)').

```csharp
public readonly struct RelationComponents<TComponent> :
System.Collections.Generic.IEnumerable<TComponent>,
System.Collections.IEnumerable
    where TComponent : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.RelationComponents_TComponent_.TComponent'></a>

`TComponent`

Implements [System.Collections.Generic.IEnumerable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1')[TComponent](RelationComponents_TComponent_.md#Friflo.Engine.ECS.RelationComponents_TComponent_.TComponent 'Friflo.Engine.ECS.RelationComponents<TComponent>.TComponent')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1'), [System.Collections.IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerable 'System.Collections.IEnumerable')

| Fields | |
| :--- | :--- |
| [Length](RelationComponents_TComponent_.Length.md 'Friflo.Engine.ECS.RelationComponents<TComponent>.Length') | Return the number of relation components.<br/> Executes in O(1). |

| Properties | |
| :--- | :--- |
| [this[int]](RelationComponents_TComponent_.this[int].md 'Friflo.Engine.ECS.RelationComponents<TComponent>.this[int]') | Return the relation component at the given [index](RelationComponents_TComponent_.this[int].md#Friflo.Engine.ECS.RelationComponents_TComponent_.this[int].index 'Friflo.Engine.ECS.RelationComponents<TComponent>.this[int].index').<br/> Executes in O(1). |

| Methods | |
| :--- | :--- |
| [Debug()](RelationComponents_TComponent_.Debug().md 'Friflo.Engine.ECS.RelationComponents<TComponent>.Debug()') | Returns a string containing the relation keys.<br/>E.g `"{ 1, 3, 7 }"` |
| [GetEnumerator()](RelationComponents_TComponent_.GetEnumerator().md 'Friflo.Engine.ECS.RelationComponents<TComponent>.GetEnumerator()') | |
| [ToString()](RelationComponents_TComponent_.ToString().md 'Friflo.Engine.ECS.RelationComponents<TComponent>.ToString()') | |

| Explicit Interface Implementations | |
| :--- | :--- |
| [System.Collections.Generic.IEnumerable&lt;TComponent&gt;.GetEnumerator()](RelationComponents_TComponent_.System.Collections.Generic.IEnumerable_TComponent_.GetEnumerator().md 'Friflo.Engine.ECS.RelationComponents<TComponent>.System.Collections.Generic.IEnumerable<TComponent>.GetEnumerator()') | |
| [System.Collections.IEnumerable.GetEnumerator()](RelationComponents_TComponent_.System.Collections.IEnumerable.GetEnumerator().md 'Friflo.Engine.ECS.RelationComponents<TComponent>.System.Collections.IEnumerable.GetEnumerator()') | |
