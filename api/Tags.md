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
| [Add(Tags)](Tags.Add(Tags).md 'Friflo.Engine.ECS.Tags.Add(Friflo.Engine.ECS.Tags)') | Add the passed [tags](Tags.Add(Tags).md#Friflo.Engine.ECS.Tags.Add(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.Tags.Add(Friflo.Engine.ECS.Tags).tags') to [Tags](Tags.md 'Friflo.Engine.ECS.Tags'). |
| [Add&lt;T&gt;()](Tags.Add_T_().md 'Friflo.Engine.ECS.Tags.Add<T>()') | Add the passed [ITag](ITag.md 'Friflo.Engine.ECS.ITag') to [Tags](Tags.md 'Friflo.Engine.ECS.Tags'). |
| [Get&lt;T&gt;()](Tags.Get_T_().md 'Friflo.Engine.ECS.Tags.Get<T>()') | Create [Tags](Tags.md 'Friflo.Engine.ECS.Tags') containging the given [ITag](ITag.md 'Friflo.Engine.ECS.ITag') |
| [Get&lt;T1,T2&gt;()](Tags.Get_T1,T2_().md 'Friflo.Engine.ECS.Tags.Get<T1,T2>()') | Create [Tags](Tags.md 'Friflo.Engine.ECS.Tags') containging the given [ITag](ITag.md 'Friflo.Engine.ECS.ITag')'s |
| [GetEnumerator()](Tags.GetEnumerator().md 'Friflo.Engine.ECS.Tags.GetEnumerator()') | |
| [Has&lt;T&gt;()](Tags.Has_T_().md 'Friflo.Engine.ECS.Tags.Has<T>()') | Return true if the [Tags](Tags.md 'Friflo.Engine.ECS.Tags') contain the passed tag [T](Tags.Has_T_().md#Friflo.Engine.ECS.Tags.Has_T_().T 'Friflo.Engine.ECS.Tags.Has<T>().T'). |
| [Has&lt;T1,T2,T3&gt;()](Tags.Has_T1,T2,T3_().md 'Friflo.Engine.ECS.Tags.Has<T1,T2,T3>()') | Return true if the [Tags](Tags.md 'Friflo.Engine.ECS.Tags') contain the passed tags. |
| [Has&lt;T1,T2&gt;()](Tags.Has_T1,T2_().md 'Friflo.Engine.ECS.Tags.Has<T1,T2>()') | Return true if the [Tags](Tags.md 'Friflo.Engine.ECS.Tags') contain the passed tags. |
| [HasAll(Tags)](Tags.HasAll(Tags).md 'Friflo.Engine.ECS.Tags.HasAll(Friflo.Engine.ECS.Tags)') | Return true if the [Tags](Tags.md 'Friflo.Engine.ECS.Tags') contain all passed [tags](Tags.HasAll(Tags).md#Friflo.Engine.ECS.Tags.HasAll(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.Tags.HasAll(Friflo.Engine.ECS.Tags).tags'). |
| [HasAny(Tags)](Tags.HasAny(Tags).md 'Friflo.Engine.ECS.Tags.HasAny(Friflo.Engine.ECS.Tags)') | Return true if the [Tags](Tags.md 'Friflo.Engine.ECS.Tags') contain any of the passed [tags](Tags.HasAny(Tags).md#Friflo.Engine.ECS.Tags.HasAny(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.Tags.HasAny(Friflo.Engine.ECS.Tags).tags'). |
| [Remove(Tags)](Tags.Remove(Tags).md 'Friflo.Engine.ECS.Tags.Remove(Friflo.Engine.ECS.Tags)') | Removes the passed [tags](Tags.Remove(Tags).md#Friflo.Engine.ECS.Tags.Remove(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.Tags.Remove(Friflo.Engine.ECS.Tags).tags') from [Tags](Tags.md 'Friflo.Engine.ECS.Tags'). |
| [Remove&lt;T&gt;()](Tags.Remove_T_().md 'Friflo.Engine.ECS.Tags.Remove<T>()') | Removes the passed [ITag](ITag.md 'Friflo.Engine.ECS.ITag') from [Tags](Tags.md 'Friflo.Engine.ECS.Tags'). |
| [ToString()](Tags.ToString().md 'Friflo.Engine.ECS.Tags.ToString()') | |

| Explicit Interface Implementations | |
| :--- | :--- |
| [System.Collections.Generic.IEnumerable&lt;Friflo.Engine.ECS.TagType&gt;.GetEnumerator()](Tags.System.Collections.Generic.IEnumerable_Friflo.Engine.ECS.TagType_.GetEnumerator().md 'Friflo.Engine.ECS.Tags.System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.TagType>.GetEnumerator()') | |
| [System.Collections.IEnumerable.GetEnumerator()](Tags.System.Collections.IEnumerable.GetEnumerator().md 'Friflo.Engine.ECS.Tags.System.Collections.IEnumerable.GetEnumerator()') | |
