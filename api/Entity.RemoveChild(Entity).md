#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.RemoveChild(Entity) Method

Remove the given child [entity](Entity.RemoveChild(Entity).md#Friflo.Engine.ECS.Entity.RemoveChild(Friflo.Engine.ECS.Entity).entity 'Friflo.Engine.ECS.Entity.RemoveChild(Friflo.Engine.ECS.Entity).entity') from this entity.

```csharp
public bool RemoveChild(Friflo.Engine.ECS.Entity entity);
```
#### Parameters

<a name='Friflo.Engine.ECS.Entity.RemoveChild(Friflo.Engine.ECS.Entity).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')

### Remarks
Executes in O(N) to search the entity. N = [ChildCount](Entity.ChildCount.md 'Friflo.Engine.ECS.Entity.ChildCount')<br/>
The subtree structure of the removed entity remains unchanged<br/>