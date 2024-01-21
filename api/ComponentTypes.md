#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ComponentTypes Struct

[ComponentTypes](ComponentTypes.md 'Friflo.Engine.ECS.ComponentTypes') define a set of [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')'s used to list the component types of an [Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype').

```csharp
public struct ComponentTypes :
System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.ComponentType>,
System.Collections.IEnumerable
```

Implements [System.Collections.Generic.IEnumerable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1')[ComponentType](ComponentType.md 'Friflo.Engine.ECS.ComponentType')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1'), [System.Collections.IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerable 'System.Collections.IEnumerable')

| Properties | |
| :--- | :--- |
| [Count](ComponentTypes.Count.md 'Friflo.Engine.ECS.ComponentTypes.Count') | Return the number of contained [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')'s. |

| Methods | |
| :--- | :--- |
| [Add(ComponentTypes)](ComponentTypes.Add(ComponentTypes).md 'Friflo.Engine.ECS.ComponentTypes.Add(Friflo.Engine.ECS.ComponentTypes)') | |
| [Add&lt;T&gt;()](ComponentTypes.Add_T_().md 'Friflo.Engine.ECS.ComponentTypes.Add<T>()') | |
| [Get&lt;T1,T2,T3,T4,T5&gt;()](ComponentTypes.Get_T1,T2,T3,T4,T5_().md 'Friflo.Engine.ECS.ComponentTypes.Get<T1,T2,T3,T4,T5>()') | |
| [Get&lt;T1,T2,T3,T4&gt;()](ComponentTypes.Get_T1,T2,T3,T4_().md 'Friflo.Engine.ECS.ComponentTypes.Get<T1,T2,T3,T4>()') | |
| [Get&lt;T1,T2,T3&gt;()](ComponentTypes.Get_T1,T2,T3_().md 'Friflo.Engine.ECS.ComponentTypes.Get<T1,T2,T3>()') | |
| [Get&lt;T1,T2&gt;()](ComponentTypes.Get_T1,T2_().md 'Friflo.Engine.ECS.ComponentTypes.Get<T1,T2>()') | |
| [Get&lt;T1&gt;()](ComponentTypes.Get_T1_().md 'Friflo.Engine.ECS.ComponentTypes.Get<T1>()') | |
| [GetEnumerator()](ComponentTypes.GetEnumerator().md 'Friflo.Engine.ECS.ComponentTypes.GetEnumerator()') | |
| [Has&lt;T1,T2,T3&gt;()](ComponentTypes.Has_T1,T2,T3_().md 'Friflo.Engine.ECS.ComponentTypes.Has<T1,T2,T3>()') | |
| [Has&lt;T1,T2&gt;()](ComponentTypes.Has_T1,T2_().md 'Friflo.Engine.ECS.ComponentTypes.Has<T1,T2>()') | |
| [Has&lt;T1&gt;()](ComponentTypes.Has_T1_().md 'Friflo.Engine.ECS.ComponentTypes.Has<T1>()') | |
| [HasAll(ComponentTypes)](ComponentTypes.HasAll(ComponentTypes).md 'Friflo.Engine.ECS.ComponentTypes.HasAll(Friflo.Engine.ECS.ComponentTypes)') | |
| [HasAny(ComponentTypes)](ComponentTypes.HasAny(ComponentTypes).md 'Friflo.Engine.ECS.ComponentTypes.HasAny(Friflo.Engine.ECS.ComponentTypes)') | |
| [Remove(ComponentTypes)](ComponentTypes.Remove(ComponentTypes).md 'Friflo.Engine.ECS.ComponentTypes.Remove(Friflo.Engine.ECS.ComponentTypes)') | |
| [Remove&lt;T&gt;()](ComponentTypes.Remove_T_().md 'Friflo.Engine.ECS.ComponentTypes.Remove<T>()') | |
| [ToString()](ComponentTypes.ToString().md 'Friflo.Engine.ECS.ComponentTypes.ToString()') | |

| Explicit Interface Implementations | |
| :--- | :--- |
| [System.Collections.Generic.IEnumerable&lt;Friflo.Engine.ECS.ComponentType&gt;.GetEnumerator()](ComponentTypes.System.Collections.Generic.IEnumerable_Friflo.Engine.ECS.ComponentType_.GetEnumerator().md 'Friflo.Engine.ECS.ComponentTypes.System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.ComponentType>.GetEnumerator()') | |
| [System.Collections.IEnumerable.GetEnumerator()](ComponentTypes.System.Collections.IEnumerable.GetEnumerator().md 'Friflo.Engine.ECS.ComponentTypes.System.Collections.IEnumerable.GetEnumerator()') | |