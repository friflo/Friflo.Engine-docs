#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

## EntityStore.OnEntityCreate Event

Add / remove an event handler for [EntityCreate](EntityCreate.md 'Friflo.Engine.ECS.EntityCreate') events triggered by [CreateEntity()](EntityStore.CreateEntity().md 'Friflo.Engine.ECS.EntityStore.CreateEntity()').

```csharp
public event Action<EntityCreate> OnEntityCreate;
```

#### Event Type
[System.Action&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')[EntityCreate](EntityCreate.md 'Friflo.Engine.ECS.EntityCreate')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')