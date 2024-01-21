#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.OnScriptChanged Event

Add / remove an event handler for [ScriptChanged](ScriptChanged.md 'Friflo.Engine.ECS.ScriptChanged') events triggered by:<br/>[AddScript&lt;TScript&gt;(TScript)](Entity.AddScript_TScript_(TScript).md 'Friflo.Engine.ECS.Entity.AddScript<TScript>(TScript)')<br/>[RemoveScript&lt;T&gt;()](Entity.RemoveScript_T_().md 'Friflo.Engine.ECS.Entity.RemoveScript<T>()').

```csharp
public event Action<ScriptChanged> OnScriptChanged;
```

#### Event Type
[System.Action&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')[ScriptChanged](ScriptChanged.md 'Friflo.Engine.ECS.ScriptChanged')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')