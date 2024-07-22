#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ChildEntities Struct

Return the child entities of an [Entity](Entity.md 'Friflo.Engine.ECS.Entity').<br/>
To iterate all entities with child entities use [TreeNode](TreeNode.md 'Friflo.Engine.ECS.TreeNode') in a `Query()`.

```csharp
public readonly struct ChildEntities :
System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.Entity>,
System.Collections.IEnumerable
```

Implements [System.Collections.Generic.IEnumerable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1')[Entity](Entity.md 'Friflo.Engine.ECS.Entity')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1'), [System.Collections.IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerable 'System.Collections.IEnumerable')

| Properties | |
| :--- | :--- |
| [Count](ChildEntities.Count.md 'Friflo.Engine.ECS.ChildEntities.Count') | |
| [Ids](ChildEntities.Ids.md 'Friflo.Engine.ECS.ChildEntities.Ids') | |
| [this[int]](ChildEntities.this[int].md 'Friflo.Engine.ECS.ChildEntities.this[int]') | |

| Methods | |
| :--- | :--- |
| [GetEnumerator()](ChildEntities.GetEnumerator().md 'Friflo.Engine.ECS.ChildEntities.GetEnumerator()') | |
| [ToArray(Entity[])](ChildEntities.ToArray(Entity[]).md 'Friflo.Engine.ECS.ChildEntities.ToArray(Friflo.Engine.ECS.Entity[])') | |
| [ToString()](ChildEntities.ToString().md 'Friflo.Engine.ECS.ChildEntities.ToString()') | |

| Explicit Interface Implementations | |
| :--- | :--- |
| [System.Collections.Generic.IEnumerable&lt;Friflo.Engine.ECS.Entity&gt;.GetEnumerator()](ChildEntities.System.Collections.Generic.IEnumerable_Friflo.Engine.ECS.Entity_.GetEnumerator().md 'Friflo.Engine.ECS.ChildEntities.System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.Entity>.GetEnumerator()') | |
| [System.Collections.IEnumerable.GetEnumerator()](ChildEntities.System.Collections.IEnumerable.GetEnumerator().md 'Friflo.Engine.ECS.ChildEntities.System.Collections.IEnumerable.GetEnumerator()') | |
