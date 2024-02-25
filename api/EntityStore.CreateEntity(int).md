#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore')

## EntityStore.CreateEntity(int) Method

Create and return new [Entity](Entity.md#'Friflo.Engine.ECS.Entity') with the passed [id](EntityStore.CreateEntity(int).md#Friflo.Engine.ECS.EntityStore.CreateEntity(int).id#'Friflo.Engine.ECS.EntityStore.CreateEntity(int).id') in the entity store.

```csharp
public Friflo.Engine.ECS.Entity CreateEntity(int id);
```
#### Parameters

<a name='Friflo.Engine.ECS.EntityStore.CreateEntity(int).id'></a>

`id` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32#'System.Int32')

#### Returns
[Entity](Entity.md#'Friflo.Engine.ECS.Entity')  
an [attached](StoreOwnership.md#Friflo.Engine.ECS.StoreOwnership.attached#'Friflo.Engine.ECS.StoreOwnership.attached') and [floating](TreeMembership.md#Friflo.Engine.ECS.TreeMembership.floating#'Friflo.Engine.ECS.TreeMembership.floating') entity