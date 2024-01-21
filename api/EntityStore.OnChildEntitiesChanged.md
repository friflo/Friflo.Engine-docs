#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

## EntityStore.OnChildEntitiesChanged Event

Add / remove an event handler for [ChildEntitiesChanged](ChildEntitiesChanged.md 'Friflo.Engine.ECS.ChildEntitiesChanged') events triggered by:<br/>[AddChild(Entity)](Entity.AddChild(Entity).md 'Friflo.Engine.ECS.Entity.AddChild(Friflo.Engine.ECS.Entity)')<br/>[InsertChild(int, Entity)](Entity.InsertChild(int,Entity).md 'Friflo.Engine.ECS.Entity.InsertChild(int, Friflo.Engine.ECS.Entity)')<br/>[RemoveChild(Entity)](Entity.RemoveChild(Entity).md 'Friflo.Engine.ECS.Entity.RemoveChild(Friflo.Engine.ECS.Entity)').

```csharp
public event Action<ChildEntitiesChanged> OnChildEntitiesChanged;
```

#### Event Type
[System.Action&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')[ChildEntitiesChanged](ChildEntitiesChanged.md 'Friflo.Engine.ECS.ChildEntitiesChanged')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')