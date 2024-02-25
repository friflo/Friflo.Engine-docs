#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## Scripts Struct

Contains the [Script](Script.md 'Friflo.Engine.ECS.Script')'s added to an entity.

```csharp
public readonly struct Scripts :
System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.Script>,
System.Collections.IEnumerable
```

Implements [System.Collections.Generic.IEnumerable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1')[Script](Script.md 'Friflo.Engine.ECS.Script')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1'), [System.Collections.IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerable 'System.Collections.IEnumerable')

| Properties | |
| :--- | :--- |
| [Length](Scripts.Length.md 'Friflo.Engine.ECS.Scripts.Length') | return number ob [Script](Script.md 'Friflo.Engine.ECS.Script')'s. |
| [Span](Scripts.Span.md 'Friflo.Engine.ECS.Scripts.Span') | return the [Script](Script.md 'Friflo.Engine.ECS.Script')'s as a Span. |
| [this[int]](Scripts.this[int].md 'Friflo.Engine.ECS.Scripts.this[int]') | |

| Methods | |
| :--- | :--- |
| [GetEnumerator()](Scripts.GetEnumerator().md 'Friflo.Engine.ECS.Scripts.GetEnumerator()') | |
| [ToString()](Scripts.ToString().md 'Friflo.Engine.ECS.Scripts.ToString()') | |

| Explicit Interface Implementations | |
| :--- | :--- |
| [System.Collections.Generic.IEnumerable&lt;Friflo.Engine.ECS.Script&gt;.GetEnumerator()](Scripts.System.Collections.Generic.IEnumerable_Friflo.Engine.ECS.Script_.GetEnumerator().md 'Friflo.Engine.ECS.Scripts.System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.Script>.GetEnumerator()') | |
| [System.Collections.IEnumerable.GetEnumerator()](Scripts.System.Collections.IEnumerable.GetEnumerator().md 'Friflo.Engine.ECS.Scripts.System.Collections.IEnumerable.GetEnumerator()') | |
