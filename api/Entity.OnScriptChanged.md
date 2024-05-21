#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.OnScriptChanged Event

Add / remove an event handler for [ScriptChanged](ScriptChanged.md 'Friflo.Engine.ECS.ScriptChanged') events triggered by:<br/>[AddScript&lt;TScript&gt;(TScript)](Entity.AddScript_TScript_(TScript).md 'Friflo.Engine.ECS.Entity.AddScript<TScript>(TScript)')<br/>[RemoveScript&lt;TScript&gt;()](Entity.RemoveScript_TScript_().md 'Friflo.Engine.ECS.Entity.RemoveScript<TScript>()').<br/>
See <a href="https://github.com/friflo/Friflo.Json.Fliox/wiki/Examples-~-General#event">Example.</a>

```csharp
public event Action<ScriptChanged> OnScriptChanged;
```

#### Event Type
[System.Action&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')[ScriptChanged](ScriptChanged.md 'Friflo.Engine.ECS.ScriptChanged')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')