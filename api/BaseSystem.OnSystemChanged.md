#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Systems](Friflo.Engine.ECS.Systems.md 'Friflo.Engine.ECS.Systems').[BaseSystem](BaseSystem.md 'Friflo.Engine.ECS.Systems.BaseSystem')

## BaseSystem.OnSystemChanged Event

Event handlers to notify a system has changed.<br/>
Like a changed system field or a system added / removed to / from a [SystemGroup](SystemGroup.md 'Friflo.Engine.ECS.Systems.SystemGroup').

```csharp
public event Action<SystemChanged> OnSystemChanged;
```

#### Event Type
[System.Action&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')[SystemChanged](SystemChanged.md 'Friflo.Engine.ECS.Systems.SystemChanged')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')