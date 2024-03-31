#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

## EntityStore.TryGetEntityById(int, Entity) Method

Get the [Entity](Entity.md 'Friflo.Engine.ECS.Entity') associated with the passed [id](EntityStore.TryGetEntityById(int,Entity).md#Friflo.Engine.ECS.EntityStore.TryGetEntityById(int,Friflo.Engine.ECS.Entity).id 'Friflo.Engine.ECS.EntityStore.TryGetEntityById(int, Friflo.Engine.ECS.Entity).id').<br/>
Returns true if passed [id](EntityStore.TryGetEntityById(int,Entity).md#Friflo.Engine.ECS.EntityStore.TryGetEntityById(int,Friflo.Engine.ECS.Entity).id 'Friflo.Engine.ECS.EntityStore.TryGetEntityById(int, Friflo.Engine.ECS.Entity).id') is valid (id < [Capacity](EntityStore.Capacity.md 'Friflo.Engine.ECS.EntityStore.Capacity')).<br/>
The returned entity can be null ([IsNull](Entity.IsNull.md 'Friflo.Engine.ECS.Entity.IsNull') == true).

```csharp
public bool TryGetEntityById(int id, out Friflo.Engine.ECS.Entity entity);
```
#### Parameters

<a name='Friflo.Engine.ECS.EntityStore.TryGetEntityById(int,Friflo.Engine.ECS.Entity).id'></a>

`id` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

<a name='Friflo.Engine.ECS.EntityStore.TryGetEntityById(int,Friflo.Engine.ECS.Entity).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')