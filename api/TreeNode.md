#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## TreeNode Struct

A [TreeNode](TreeNode.md 'Friflo.Engine.ECS.TreeNode') component stores the [ChildEntities](Entity.ChildEntities.md 'Friflo.Engine.ECS.Entity.ChildEntities') of an [Entity](Entity.md 'Friflo.Engine.ECS.Entity').<br/>
It is used to build up an entity hierarchy used for scene graphs.

```csharp
public struct TreeNode :
Friflo.Engine.ECS.IComponent
```

Implements [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')

### Remarks
To change the [ChildEntities](Entity.ChildEntities.md 'Friflo.Engine.ECS.Entity.ChildEntities') of an [Entity](Entity.md 'Friflo.Engine.ECS.Entity') use:<br/>
- [AddChild(Entity)](Entity.AddChild(Entity).md 'Friflo.Engine.ECS.Entity.AddChild(Friflo.Engine.ECS.Entity)')<br/>
- [RemoveChild(Entity)](Entity.RemoveChild(Entity).md 'Friflo.Engine.ECS.Entity.RemoveChild(Friflo.Engine.ECS.Entity)')<br/>
- [InsertChild(int, Entity)](Entity.InsertChild(int,Entity).md 'Friflo.Engine.ECS.Entity.InsertChild(int, Friflo.Engine.ECS.Entity)')<br/><br/>
Internally the child entities of an entity are stored in up to a dozen int[] arrays.<br/>
If these array buffers grown large enough over time no heap allocations will happen if adding or removing child entities.<br/>

| Properties | |
| :--- | :--- |
| [ChildCount](TreeNode.ChildCount.md 'Friflo.Engine.ECS.TreeNode.ChildCount') | Returns the number of [ChildEntities](Entity.ChildEntities.md 'Friflo.Engine.ECS.Entity.ChildEntities'). |
| [ChildIds](TreeNode.ChildIds.md 'Friflo.Engine.ECS.TreeNode.ChildIds') | Property is obsolete. Use [GetChildIds(EntityStore)](TreeNode.GetChildIds(EntityStore).md 'Friflo.Engine.ECS.TreeNode.GetChildIds(Friflo.Engine.ECS.EntityStore)') instead. |

| Methods | |
| :--- | :--- |
| [GetChildEntities(EntityStore)](TreeNode.GetChildEntities(EntityStore).md 'Friflo.Engine.ECS.TreeNode.GetChildEntities(Friflo.Engine.ECS.EntityStore)') | Returns the child entities.<br/> Executes in O(1). |
| [GetChildIds(EntityStore)](TreeNode.GetChildIds(EntityStore).md 'Friflo.Engine.ECS.TreeNode.GetChildIds(Friflo.Engine.ECS.EntityStore)') | Returns the child entity ids.<br/> Executes in O(1). |
| [ToString()](TreeNode.ToString().md 'Friflo.Engine.ECS.TreeNode.ToString()') | |
