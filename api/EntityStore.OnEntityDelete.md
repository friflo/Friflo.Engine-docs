#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

## EntityStore.OnEntityDelete Event

Add / remove an event handler for [EntityDelete](EntityDelete.md 'Friflo.Engine.ECS.EntityDelete') events triggered by [DeleteEntity()](Entity.DeleteEntity().md 'Friflo.Engine.ECS.Entity.DeleteEntity()').

```csharp
public event Action<EntityDelete> OnEntityDelete;
```

#### Event Type
[System.Action&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')[EntityDelete](EntityDelete.md 'Friflo.Engine.ECS.EntityDelete')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')