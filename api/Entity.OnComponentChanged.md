#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.OnComponentChanged Event

Add / remove an event handler for [ComponentChanged](ComponentChanged.md 'Friflo.Engine.ECS.ComponentChanged') events triggered by: <br/>[AddComponent&lt;T&gt;()](Entity.AddComponent_T_().md 'Friflo.Engine.ECS.Entity.AddComponent<T>()')<br/>[RemoveComponent&lt;T&gt;()](Entity.RemoveComponent_T_().md 'Friflo.Engine.ECS.Entity.RemoveComponent<T>()').<br/>
See <a href="https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md#event">Example.</a>

```csharp
public event Action<ComponentChanged> OnComponentChanged;
```

#### Event Type
[System.Action&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')[ComponentChanged](ComponentChanged.md 'Friflo.Engine.ECS.ComponentChanged')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')