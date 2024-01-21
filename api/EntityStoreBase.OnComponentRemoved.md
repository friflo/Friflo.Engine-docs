#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStoreBase](EntityStoreBase.md 'Friflo.Engine.ECS.EntityStoreBase')

## EntityStoreBase.OnComponentRemoved Event

Add / remove an event handler for [ComponentChanged](ComponentChanged.md 'Friflo.Engine.ECS.ComponentChanged') events triggered by: <br/>[RemoveComponent&lt;T&gt;()](Entity.RemoveComponent_T_().md 'Friflo.Engine.ECS.Entity.RemoveComponent<T>()').

```csharp
public event Action<ComponentChanged> OnComponentRemoved;
```

#### Event Type
[System.Action&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')[ComponentChanged](ComponentChanged.md 'Friflo.Engine.ECS.ComponentChanged')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')