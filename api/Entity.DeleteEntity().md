#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.DeleteEntity() Method

Delete the entity from its [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore').<br/>
The deleted instance is in [detached](StoreOwnership.md#Friflo.Engine.ECS.StoreOwnership.detached 'Friflo.Engine.ECS.StoreOwnership.detached') state.
Calling [Entity](Entity.md 'Friflo.Engine.ECS.Entity') methods result in [System.NullReferenceException](https://docs.microsoft.com/en-us/dotnet/api/System.NullReferenceException 'System.NullReferenceException')'s

```csharp
public void DeleteEntity();
```

### Remarks
Executes in O(1) in case the entity has no children and if it is the last entity in [Parent](Entity.Parent.md 'Friflo.Engine.ECS.Entity.Parent').[ChildIds](Entity.ChildIds.md 'Friflo.Engine.ECS.Entity.ChildIds')