#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.ChildEntities Property

Return all child entities of an entity.

```csharp
public Friflo.Engine.ECS.ChildEntities ChildEntities { get; }
```

#### Property Value
[ChildEntities](ChildEntities.md 'Friflo.Engine.ECS.ChildEntities')

### Remarks
Executes in O(1).<br/> Enumerate with:

```csharp
foreach (var child in entity.ChildEntities)
```
To iterate all entities with child entities use [TreeNode](TreeNode.md 'Friflo.Engine.ECS.TreeNode') in a `Query()`.