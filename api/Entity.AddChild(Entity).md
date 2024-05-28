#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.AddChild(Entity) Method

Add the given [child](Entity.AddChild(Entity).md#Friflo.Engine.ECS.Entity.AddChild(Friflo.Engine.ECS.Entity).child 'Friflo.Engine.ECS.Entity.AddChild(Friflo.Engine.ECS.Entity).child') as a child to the entity.<br/>
See <a href="https://github.com/friflo/Friflo.Json.Fliox/wiki/Examples-~-General#child-entities">Example.</a>

```csharp
public int AddChild(Friflo.Engine.ECS.Entity child);
```
#### Parameters

<a name='Friflo.Engine.ECS.Entity.AddChild(Friflo.Engine.ECS.Entity).child'></a>

`child` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

#### Returns
[System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')  
The index within [ChildIds](Entity.ChildIds.md 'Friflo.Engine.ECS.Entity.ChildIds') the [child](Entity.AddChild(Entity).md#Friflo.Engine.ECS.Entity.AddChild(Friflo.Engine.ECS.Entity).child 'Friflo.Engine.ECS.Entity.AddChild(Friflo.Engine.ECS.Entity).child') is added.<br/>
-1 if the [child](Entity.AddChild(Entity).md#Friflo.Engine.ECS.Entity.AddChild(Friflo.Engine.ECS.Entity).child 'Friflo.Engine.ECS.Entity.AddChild(Friflo.Engine.ECS.Entity).child') is already a child entity.

### Remarks
Executes in O(1).<br/>If its [TreeMembership](Entity.TreeMembership.md 'Friflo.Engine.ECS.Entity.TreeMembership') changes O(number of nodes in sub tree).<br/>
The subtree structure of the added entity remains unchanged<br/>