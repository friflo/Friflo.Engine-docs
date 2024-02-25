#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS.Collections](Friflo.Engine.ECS.Collections.md#'Friflo.Engine.ECS.Collections')

## ExplorerItem Class

Implements same interfaces as [System.Collections.ObjectModel.ObservableCollection&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.ObjectModel.ObservableCollection-1#'System.Collections.ObjectModel.ObservableCollection`1') to act as a replacement
for this container class using the generic type [ExplorerItem](ExplorerItem.md#'Friflo.Engine.ECS.Collections.ExplorerItem').<br/><br/>
This enables displaying and mutation of [Entity](ExplorerItem.Entity.md#'Friflo.Engine.ECS.Collections.ExplorerItem.Entity')'s in a
<a href="https://github.com/AvaloniaUI/Avalonia.Controls.TreeDataGrid">Avalonia.Controls.TreeDataGrid</a>.<br/>
A specialized implementation of this control is the <b>ExplorerTreeDataGrid</b> in this repository.

```csharp
public sealed class ExplorerItem :
System.Collections.Generic.IList<Friflo.Engine.ECS.Collections.ExplorerItem>,
System.Collections.Generic.ICollection<Friflo.Engine.ECS.Collections.ExplorerItem>,
System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.Collections.ExplorerItem>,
System.Collections.IEnumerable,
System.Collections.IList,
System.Collections.ICollection,
System.Collections.Generic.IReadOnlyList<Friflo.Engine.ECS.Collections.ExplorerItem>,
System.Collections.Generic.IReadOnlyCollection<Friflo.Engine.ECS.Collections.ExplorerItem>,
System.Collections.Specialized.INotifyCollectionChanged,
System.ComponentModel.INotifyPropertyChanged
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object#'System.Object') &#129106; ExplorerItem

Implements [System.Collections.Generic.IList&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IList-1#'System.Collections.Generic.IList`1')[ExplorerItem](ExplorerItem.md#'Friflo.Engine.ECS.Collections.ExplorerItem')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IList-1#'System.Collections.Generic.IList`1'), [System.Collections.Generic.ICollection&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.ICollection-1#'System.Collections.Generic.ICollection`1')[ExplorerItem](ExplorerItem.md#'Friflo.Engine.ECS.Collections.ExplorerItem')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.ICollection-1#'System.Collections.Generic.ICollection`1'), [System.Collections.Generic.IEnumerable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1#'System.Collections.Generic.IEnumerable`1')[ExplorerItem](ExplorerItem.md#'Friflo.Engine.ECS.Collections.ExplorerItem')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1#'System.Collections.Generic.IEnumerable`1'), [System.Collections.IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerable#'System.Collections.IEnumerable'), [System.Collections.IList](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IList#'System.Collections.IList'), [System.Collections.ICollection](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.ICollection#'System.Collections.ICollection'), [System.Collections.Generic.IReadOnlyList&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyList-1#'System.Collections.Generic.IReadOnlyList`1')[ExplorerItem](ExplorerItem.md#'Friflo.Engine.ECS.Collections.ExplorerItem')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyList-1#'System.Collections.Generic.IReadOnlyList`1'), [System.Collections.Generic.IReadOnlyCollection&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1#'System.Collections.Generic.IReadOnlyCollection`1')[ExplorerItem](ExplorerItem.md#'Friflo.Engine.ECS.Collections.ExplorerItem')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1#'System.Collections.Generic.IReadOnlyCollection`1'), [System.Collections.Specialized.INotifyCollectionChanged](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Specialized.INotifyCollectionChanged#'System.Collections.Specialized.INotifyCollectionChanged'), [System.ComponentModel.INotifyPropertyChanged](https://docs.microsoft.com/en-us/dotnet/api/System.ComponentModel.INotifyPropertyChanged#'System.ComponentModel.INotifyPropertyChanged')

### Remarks
It seems a common and reasonable approach that other UI frameworks like <b>MAUI</b> or <b>UNO Platform</b> provide<br/>
TreeView controls by using TreeView items implementing [System.Collections.Specialized.INotifyCollectionChanged](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Specialized.INotifyCollectionChanged#'System.Collections.Specialized.INotifyCollectionChanged') and
optionally [System.ComponentModel.INotifyPropertyChanged](https://docs.microsoft.com/en-us/dotnet/api/System.ComponentModel.INotifyPropertyChanged#'System.ComponentModel.INotifyPropertyChanged').<br/><br/>
Major advantages of this approach.
- Support millions of items within a TreeView hierarchy without any UI stuttering.
- Enabling binding hierarchical data to a UI without the need of 3rd party libraries in the data layer.<br/>[System.Collections.Specialized.INotifyCollectionChanged](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Specialized.INotifyCollectionChanged#'System.Collections.Specialized.INotifyCollectionChanged') and optionally [System.ComponentModel.INotifyPropertyChanged](https://docs.microsoft.com/en-us/dotnet/api/System.ComponentModel.INotifyPropertyChanged#'System.ComponentModel.INotifyPropertyChanged') of the BCL are sufficient.

| Fields | |
| :--- | :--- |
| [flag](ExplorerItem.flag.md#'Friflo.Engine.ECS.Collections.ExplorerItem.flag') | |
| [propertyChangedHandler](ExplorerItem.propertyChangedHandler.md#'Friflo.Engine.ECS.Collections.ExplorerItem.propertyChangedHandler') | |

| Properties | |
| :--- | :--- |
| [AllowDrag](ExplorerItem.AllowDrag.md#'Friflo.Engine.ECS.Collections.ExplorerItem.AllowDrag') | |
| [DebugTreeName](ExplorerItem.DebugTreeName.md#'Friflo.Engine.ECS.Collections.ExplorerItem.DebugTreeName') | |
| [Entity](ExplorerItem.Entity.md#'Friflo.Engine.ECS.Collections.ExplorerItem.Entity') | |
| [Id](ExplorerItem.Id.md#'Friflo.Engine.ECS.Collections.ExplorerItem.Id') | |
| [IsExpanded](ExplorerItem.IsExpanded.md#'Friflo.Engine.ECS.Collections.ExplorerItem.IsExpanded') | |
| [IsRoot](ExplorerItem.IsRoot.md#'Friflo.Engine.ECS.Collections.ExplorerItem.IsRoot') | |
| [Name](ExplorerItem.Name.md#'Friflo.Engine.ECS.Collections.ExplorerItem.Name') | |

| Methods | |
| :--- | :--- |
| [GetEnumerator()](ExplorerItem.GetEnumerator().md#'Friflo.Engine.ECS.Collections.ExplorerItem.GetEnumerator()') | |
| [ToString()](ExplorerItem.ToString().md#'Friflo.Engine.ECS.Collections.ExplorerItem.ToString()') | |

| Events | |
| :--- | :--- |
| [CollectionChanged](ExplorerItem.CollectionChanged.md#'Friflo.Engine.ECS.Collections.ExplorerItem.CollectionChanged') | |
| [PropertyChanged](ExplorerItem.PropertyChanged.md#'Friflo.Engine.ECS.Collections.ExplorerItem.PropertyChanged') | |

| Explicit Interface Implementations | |
| :--- | :--- |
| [System.Collections.Generic.ICollection&lt;Friflo.Engine.ECS.Collections.ExplorerItem&gt;.Add(ExplorerItem)](ExplorerItem.System.Collections.Generic.ICollection_Friflo.Engine.ECS.Collections.ExplorerItem_.Add(ExplorerItem).md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.Generic.ICollection<Friflo.Engine.ECS.Collections.ExplorerItem>.Add(Friflo.Engine.ECS.Collections.ExplorerItem)') | |
| [System.Collections.Generic.ICollection&lt;Friflo.Engine.ECS.Collections.ExplorerItem&gt;.Clear()](ExplorerItem.System.Collections.Generic.ICollection_Friflo.Engine.ECS.Collections.ExplorerItem_.Clear().md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.Generic.ICollection<Friflo.Engine.ECS.Collections.ExplorerItem>.Clear()') | |
| [System.Collections.Generic.ICollection&lt;Friflo.Engine.ECS.Collections.ExplorerItem&gt;.Contains(ExplorerItem)](ExplorerItem.System.Collections.Generic.ICollection_Friflo.Engine.ECS.Collections.ExplorerItem_.Contains(ExplorerItem).md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.Generic.ICollection<Friflo.Engine.ECS.Collections.ExplorerItem>.Contains(Friflo.Engine.ECS.Collections.ExplorerItem)') | |
| [System.Collections.Generic.ICollection&lt;Friflo.Engine.ECS.Collections.ExplorerItem&gt;.CopyTo(ExplorerItem[], int)](ExplorerItem.System.Collections.Generic.ICollection_Friflo.Engine.ECS.Collections.ExplorerItem_.CopyTo(ExplorerItem[],int).md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.Generic.ICollection<Friflo.Engine.ECS.Collections.ExplorerItem>.CopyTo(Friflo.Engine.ECS.Collections.ExplorerItem[], int)') | |
| [System.Collections.Generic.ICollection&lt;Friflo.Engine.ECS.Collections.ExplorerItem&gt;.Count](ExplorerItem.System.Collections.Generic.ICollection_Friflo.Engine.ECS.Collections.ExplorerItem_.Count.md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.Generic.ICollection<Friflo.Engine.ECS.Collections.ExplorerItem>.Count') | |
| [System.Collections.Generic.ICollection&lt;Friflo.Engine.ECS.Collections.ExplorerItem&gt;.IsReadOnly](ExplorerItem.System.Collections.Generic.ICollection_Friflo.Engine.ECS.Collections.ExplorerItem_.IsReadOnly.md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.Generic.ICollection<Friflo.Engine.ECS.Collections.ExplorerItem>.IsReadOnly') | |
| [System.Collections.Generic.ICollection&lt;Friflo.Engine.ECS.Collections.ExplorerItem&gt;.Remove(ExplorerItem)](ExplorerItem.System.Collections.Generic.ICollection_Friflo.Engine.ECS.Collections.ExplorerItem_.Remove(ExplorerItem).md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.Generic.ICollection<Friflo.Engine.ECS.Collections.ExplorerItem>.Remove(Friflo.Engine.ECS.Collections.ExplorerItem)') | |
| [System.Collections.Generic.IList&lt;Friflo.Engine.ECS.Collections.ExplorerItem&gt;.IndexOf(ExplorerItem)](ExplorerItem.System.Collections.Generic.IList_Friflo.Engine.ECS.Collections.ExplorerItem_.IndexOf(ExplorerItem).md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.Generic.IList<Friflo.Engine.ECS.Collections.ExplorerItem>.IndexOf(Friflo.Engine.ECS.Collections.ExplorerItem)') | |
| [System.Collections.Generic.IList&lt;Friflo.Engine.ECS.Collections.ExplorerItem&gt;.Insert(int, ExplorerItem)](ExplorerItem.System.Collections.Generic.IList_Friflo.Engine.ECS.Collections.ExplorerItem_.Insert(int,ExplorerItem).md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.Generic.IList<Friflo.Engine.ECS.Collections.ExplorerItem>.Insert(int, Friflo.Engine.ECS.Collections.ExplorerItem)') | |
| [System.Collections.Generic.IList&lt;Friflo.Engine.ECS.Collections.ExplorerItem&gt;.RemoveAt(int)](ExplorerItem.System.Collections.Generic.IList_Friflo.Engine.ECS.Collections.ExplorerItem_.RemoveAt(int).md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.Generic.IList<Friflo.Engine.ECS.Collections.ExplorerItem>.RemoveAt(int)') | |
| [System.Collections.Generic.IReadOnlyCollection&lt;Friflo.Engine.ECS.Collections.ExplorerItem&gt;.Count](ExplorerItem.System.Collections.Generic.IReadOnlyCollection_Friflo.Engine.ECS.Collections.ExplorerItem_.Count.md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.Generic.IReadOnlyCollection<Friflo.Engine.ECS.Collections.ExplorerItem>.Count') | |
| [System.Collections.ICollection.CopyTo(Array, int)](ExplorerItem.System.Collections.ICollection.CopyTo(Array,int).md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.ICollection.CopyTo(System.Array, int)') | |
| [System.Collections.ICollection.Count](ExplorerItem.System.Collections.ICollection.Count.md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.ICollection.Count') | |
| [System.Collections.ICollection.IsSynchronized](ExplorerItem.System.Collections.ICollection.IsSynchronized.md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.ICollection.IsSynchronized') | |
| [System.Collections.ICollection.SyncRoot](ExplorerItem.System.Collections.ICollection.SyncRoot.md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.ICollection.SyncRoot') | |
| [System.Collections.IEnumerable.GetEnumerator()](ExplorerItem.System.Collections.IEnumerable.GetEnumerator().md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.IEnumerable.GetEnumerator()') | |
| [System.Collections.IList.Add(object)](ExplorerItem.System.Collections.IList.Add(object).md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.IList.Add(object)') | |
| [System.Collections.IList.Clear()](ExplorerItem.System.Collections.IList.Clear().md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.IList.Clear()') | |
| [System.Collections.IList.Contains(object)](ExplorerItem.System.Collections.IList.Contains(object).md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.IList.Contains(object)') | |
| [System.Collections.IList.IndexOf(object)](ExplorerItem.System.Collections.IList.IndexOf(object).md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.IList.IndexOf(object)') | |
| [System.Collections.IList.Insert(int, object)](ExplorerItem.System.Collections.IList.Insert(int,object).md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.IList.Insert(int, object)') | |
| [System.Collections.IList.IsFixedSize](ExplorerItem.System.Collections.IList.IsFixedSize.md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.IList.IsFixedSize') | |
| [System.Collections.IList.IsReadOnly](ExplorerItem.System.Collections.IList.IsReadOnly.md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.IList.IsReadOnly') | |
| [System.Collections.IList.Remove(object)](ExplorerItem.System.Collections.IList.Remove(object).md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.IList.Remove(object)') | |
| [System.Collections.IList.RemoveAt(int)](ExplorerItem.System.Collections.IList.RemoveAt(int).md#'Friflo.Engine.ECS.Collections.ExplorerItem.System.Collections.IList.RemoveAt(int)') | |
| [this[int]](ExplorerItem.this[int].md#'Friflo.Engine.ECS.Collections.ExplorerItem.this[int]') | |
| [this[int]](ExplorerItem.this[int].md#'Friflo.Engine.ECS.Collections.ExplorerItem.this[int]') | |
| [this[int]](ExplorerItem.this[int].md#'Friflo.Engine.ECS.Collections.ExplorerItem.this[int]') | |
