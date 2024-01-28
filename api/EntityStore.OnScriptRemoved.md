#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

## EntityStore.OnScriptRemoved Event

Add / remove an event handler for [ScriptChanged](ScriptChanged.md 'Friflo.Engine.ECS.ScriptChanged') events triggered by:<br/>[RemoveScript&lt;TScript&gt;()](Entity.RemoveScript_TScript_().md 'Friflo.Engine.ECS.Entity.RemoveScript<TScript>()') .

```csharp
public event Action<ScriptChanged> OnScriptRemoved;
```

#### Event Type
[System.Action&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')[ScriptChanged](ScriptChanged.md 'Friflo.Engine.ECS.ScriptChanged')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')