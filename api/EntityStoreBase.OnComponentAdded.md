#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[EntityStoreBase](EntityStoreBase.md#'Friflo.Engine.ECS.EntityStoreBase')

## EntityStoreBase.OnComponentAdded Event

Add / remove an event handler for [ComponentChanged](ComponentChanged.md#'Friflo.Engine.ECS.ComponentChanged') events triggered by: <br/>[AddComponent&lt;T&gt;()](Entity.AddComponent_T_().md#'Friflo.Engine.ECS.Entity.AddComponent<T>()').

```csharp
public event Action<ComponentChanged> OnComponentAdded;
```

#### Event Type
[System.Action&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1#'System.Action`1')[ComponentChanged](ComponentChanged.md#'Friflo.Engine.ECS.ComponentChanged')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1#'System.Action`1')