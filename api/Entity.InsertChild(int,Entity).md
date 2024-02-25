#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.InsertChild(int, Entity) Method

Insert the given [entity](Entity.InsertChild(int,Entity).md#Friflo.Engine.ECS.Entity.InsertChild(int,Friflo.Engine.ECS.Entity).entity 'Friflo.Engine.ECS.Entity.InsertChild(int, Friflo.Engine.ECS.Entity).entity') as a child to the entity at the passed [index](Entity.InsertChild(int,Entity).md#Friflo.Engine.ECS.Entity.InsertChild(int,Friflo.Engine.ECS.Entity).index 'Friflo.Engine.ECS.Entity.InsertChild(int, Friflo.Engine.ECS.Entity).index').

```csharp
public void InsertChild(int index, Friflo.Engine.ECS.Entity entity);
```
#### Parameters

<a name='Friflo.Engine.ECS.Entity.InsertChild(int,Friflo.Engine.ECS.Entity).index'></a>

`index` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

<a name='Friflo.Engine.ECS.Entity.InsertChild(int,Friflo.Engine.ECS.Entity).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

### Remarks
Executes in O(1) in case [index](Entity.InsertChild(int,Entity).md#Friflo.Engine.ECS.Entity.InsertChild(int,Friflo.Engine.ECS.Entity).index 'Friflo.Engine.ECS.Entity.InsertChild(int, Friflo.Engine.ECS.Entity).index') == [ChildCount](Entity.ChildCount.md 'Friflo.Engine.ECS.Entity.ChildCount').<br/>
Otherwise O(N). N = [ChildCount](Entity.ChildCount.md 'Friflo.Engine.ECS.Entity.ChildCount') - [index](Entity.InsertChild(int,Entity).md#Friflo.Engine.ECS.Entity.InsertChild(int,Friflo.Engine.ECS.Entity).index 'Friflo.Engine.ECS.Entity.InsertChild(int, Friflo.Engine.ECS.Entity).index')<br/>
If its [TreeMembership](Entity.TreeMembership.md 'Friflo.Engine.ECS.Entity.TreeMembership') changes O(number of nodes in sub tree).<br/>
The subtree structure of the added entity remains unchanged<br/>