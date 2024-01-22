#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## Tags Struct

[Tags](Tags.md 'Friflo.Engine.ECS.Tags') define a set of [ITag](ITag.md 'Friflo.Engine.ECS.ITag')'s used to query entities in an [EntityStoreBase](EntityStoreBase.md 'Friflo.Engine.ECS.EntityStoreBase').

```csharp
public struct Tags :
System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.TagType>,
System.Collections.IEnumerable
```

Implements [System.Collections.Generic.IEnumerable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1')[TagType](TagType.md 'Friflo.Engine.ECS.TagType')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1'), [System.Collections.IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerable 'System.Collections.IEnumerable')

| Constructors | |
| :--- | :--- |
| [Tags(TagType)](Tags.Tags(TagType).md 'Friflo.Engine.ECS.Tags.Tags(Friflo.Engine.ECS.TagType)') | |
| [Tags(Vector256&lt;long&gt;)](Tags.Tags(Vector256_long_).md 'Friflo.Engine.ECS.Tags.Tags(System.Runtime.Intrinsics.Vector256<long>)') | |

| Properties | |
| :--- | :--- |
| [Count](Tags.Count.md 'Friflo.Engine.ECS.Tags.Count') | Return the number of contained [ITag](ITag.md 'Friflo.Engine.ECS.ITag')'s. |

| Methods | |
| :--- | :--- |
| [Add(Tags)](Tags.Add(Tags).md 'Friflo.Engine.ECS.Tags.Add(Friflo.Engine.ECS.Tags)') | Add the passed [tags](Tags.Add(Tags).md#Friflo.Engine.ECS.Tags.Add(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.Tags.Add(Friflo.Engine.ECS.Tags).tags'). |
| [Add&lt;T&gt;()](Tags.Add_T_().md 'Friflo.Engine.ECS.Tags.Add<T>()') | Add the passed [ITag](ITag.md 'Friflo.Engine.ECS.ITag') type [T](Tags.Add_T_().md#Friflo.Engine.ECS.Tags.Add_T_().T 'Friflo.Engine.ECS.Tags.Add<T>().T'). |
| [Get&lt;T&gt;()](Tags.Get_T_().md 'Friflo.Engine.ECS.Tags.Get<T>()') | Create an instance containing the given [ITag](ITag.md 'Friflo.Engine.ECS.ITag') type [T](Tags.Get_T_().md#Friflo.Engine.ECS.Tags.Get_T_().T 'Friflo.Engine.ECS.Tags.Get<T>().T'). |
| [Get&lt;T1,T2&gt;()](Tags.Get_T1,T2_().md 'Friflo.Engine.ECS.Tags.Get<T1,T2>()') | Create an instance containing the given [ITag](ITag.md 'Friflo.Engine.ECS.ITag') types [T1](Tags.Get_T1,T2_().md#Friflo.Engine.ECS.Tags.Get_T1,T2_().T1 'Friflo.Engine.ECS.Tags.Get<T1,T2>().T1') and [T2](Tags.Get_T1,T2_().md#Friflo.Engine.ECS.Tags.Get_T1,T2_().T2 'Friflo.Engine.ECS.Tags.Get<T1,T2>().T2'). |
| [GetEnumerator()](Tags.GetEnumerator().md 'Friflo.Engine.ECS.Tags.GetEnumerator()') | |
| [Has&lt;T1,T2,T3&gt;()](Tags.Has_T1,T2,T3_().md 'Friflo.Engine.ECS.Tags.Has<T1,T2,T3>()') | Return true if it contains all passed [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') types [T1](Tags.Has_T1,T2,T3_().md#Friflo.Engine.ECS.Tags.Has_T1,T2,T3_().T1 'Friflo.Engine.ECS.Tags.Has<T1,T2,T3>().T1'), [T2](Tags.Has_T1,T2,T3_().md#Friflo.Engine.ECS.Tags.Has_T1,T2,T3_().T2 'Friflo.Engine.ECS.Tags.Has<T1,T2,T3>().T2') and [T3](Tags.Has_T1,T2,T3_().md#Friflo.Engine.ECS.Tags.Has_T1,T2,T3_().T3 'Friflo.Engine.ECS.Tags.Has<T1,T2,T3>().T3'). |
| [Has&lt;T1,T2&gt;()](Tags.Has_T1,T2_().md 'Friflo.Engine.ECS.Tags.Has<T1,T2>()') | Return true if it contains all passed [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') types [T1](Tags.Has_T1,T2_().md#Friflo.Engine.ECS.Tags.Has_T1,T2_().T1 'Friflo.Engine.ECS.Tags.Has<T1,T2>().T1') and [T2](Tags.Has_T1,T2_().md#Friflo.Engine.ECS.Tags.Has_T1,T2_().T2 'Friflo.Engine.ECS.Tags.Has<T1,T2>().T2'). |
| [Has&lt;T1&gt;()](Tags.Has_T1_().md 'Friflo.Engine.ECS.Tags.Has<T1>()') | Return true if it contain the passed tag [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') type [T1](Tags.Has_T1_().md#Friflo.Engine.ECS.Tags.Has_T1_().T1 'Friflo.Engine.ECS.Tags.Has<T1>().T1'). |
| [HasAll(Tags)](Tags.HasAll(Tags).md 'Friflo.Engine.ECS.Tags.HasAll(Friflo.Engine.ECS.Tags)') | Return true if it contains all passed [tags](Tags.HasAll(Tags).md#Friflo.Engine.ECS.Tags.HasAll(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.Tags.HasAll(Friflo.Engine.ECS.Tags).tags'). |
| [HasAny(Tags)](Tags.HasAny(Tags).md 'Friflo.Engine.ECS.Tags.HasAny(Friflo.Engine.ECS.Tags)') | Return true if it contains any of the passed [tags](Tags.HasAny(Tags).md#Friflo.Engine.ECS.Tags.HasAny(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.Tags.HasAny(Friflo.Engine.ECS.Tags).tags'). |
| [Remove(Tags)](Tags.Remove(Tags).md 'Friflo.Engine.ECS.Tags.Remove(Friflo.Engine.ECS.Tags)') | Removes the passed [tags](Tags.Remove(Tags).md#Friflo.Engine.ECS.Tags.Remove(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.Tags.Remove(Friflo.Engine.ECS.Tags).tags'). |
| [Remove&lt;T&gt;()](Tags.Remove_T_().md 'Friflo.Engine.ECS.Tags.Remove<T>()') | Removes the passed [ITag](ITag.md 'Friflo.Engine.ECS.ITag') type [T](Tags.Remove_T_().md#Friflo.Engine.ECS.Tags.Remove_T_().T 'Friflo.Engine.ECS.Tags.Remove<T>().T'). |
| [ToString()](Tags.ToString().md 'Friflo.Engine.ECS.Tags.ToString()') | |

| Explicit Interface Implementations | |
| :--- | :--- |
| [System.Collections.Generic.IEnumerable&lt;Friflo.Engine.ECS.TagType&gt;.GetEnumerator()](Tags.System.Collections.Generic.IEnumerable_Friflo.Engine.ECS.TagType_.GetEnumerator().md 'Friflo.Engine.ECS.Tags.System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.TagType>.GetEnumerator()') | |
| [System.Collections.IEnumerable.GetEnumerator()](Tags.System.Collections.IEnumerable.GetEnumerator().md 'Friflo.Engine.ECS.Tags.System.Collections.IEnumerable.GetEnumerator()') | |
