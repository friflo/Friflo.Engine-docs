#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ComponentEnumerator Struct

Enumerate the components of an entity by iterating [EntityComponents](EntityComponents.md 'Friflo.Engine.ECS.EntityComponents').

```csharp
public struct ComponentEnumerator :
System.Collections.Generic.IEnumerator<Friflo.Engine.ECS.EntityComponent>,
System.Collections.IEnumerator,
System.IDisposable
```

Implements [System.Collections.Generic.IEnumerator&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerator-1 'System.Collections.Generic.IEnumerator`1')[EntityComponent](EntityComponent.md 'Friflo.Engine.ECS.EntityComponent')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerator-1 'System.Collections.Generic.IEnumerator`1'), [System.Collections.IEnumerator](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerator 'System.Collections.IEnumerator'), [System.IDisposable](https://docs.microsoft.com/en-us/dotnet/api/System.IDisposable 'System.IDisposable')

| Properties | |
| :--- | :--- |
| [Current](ComponentEnumerator.Current.md 'Friflo.Engine.ECS.ComponentEnumerator.Current') | |

| Methods | |
| :--- | :--- |
| [Dispose()](ComponentEnumerator.Dispose().md 'Friflo.Engine.ECS.ComponentEnumerator.Dispose()') | |
| [MoveNext()](ComponentEnumerator.MoveNext().md 'Friflo.Engine.ECS.ComponentEnumerator.MoveNext()') | |
| [Reset()](ComponentEnumerator.Reset().md 'Friflo.Engine.ECS.ComponentEnumerator.Reset()') | |

| Explicit Interface Implementations | |
| :--- | :--- |
| [System.Collections.IEnumerator.Current](ComponentEnumerator.System.Collections.IEnumerator.Current.md 'Friflo.Engine.ECS.ComponentEnumerator.System.Collections.IEnumerator.Current') | |
