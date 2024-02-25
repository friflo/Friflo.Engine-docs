#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS')

## ScriptChanged Struct

Is the event for event handlers added to [OnScriptChanged](Entity.OnScriptChanged.md#'Friflo.Engine.ECS.Entity.OnScriptChanged'),
[OnScriptAdded](EntityStore.OnScriptAdded.md#'Friflo.Engine.ECS.EntityStore.OnScriptAdded') or [OnScriptRemoved](EntityStore.OnScriptRemoved.md#'Friflo.Engine.ECS.EntityStore.OnScriptRemoved').

```csharp
public readonly struct ScriptChanged
```

### Remarks
<br/>
            These events are fired on:
            
- [AddScript&lt;TScript&gt;(TScript)](Entity.AddScript_TScript_(TScript).md#'Friflo.Engine.ECS.Entity.AddScript<TScript>(TScript)')
- [RemoveScript&lt;TScript&gt;()](Entity.RemoveScript_TScript_().md#'Friflo.Engine.ECS.Entity.RemoveScript<TScript>()')

| Fields | |
| :--- | :--- |
| [Action](ScriptChanged.Action.md#'Friflo.Engine.ECS.ScriptChanged.Action') | The executed entity change: [Remove](ScriptChangedAction.md#Friflo.Engine.ECS.ScriptChangedAction.Remove#'Friflo.Engine.ECS.ScriptChangedAction.Remove'),             [Add](ScriptChangedAction.md#Friflo.Engine.ECS.ScriptChangedAction.Add#'Friflo.Engine.ECS.ScriptChangedAction.Add') or [Replace](ScriptChangedAction.md#Friflo.Engine.ECS.ScriptChangedAction.Replace#'Friflo.Engine.ECS.ScriptChangedAction.Replace') script. |
| [Entity](ScriptChanged.Entity.md#'Friflo.Engine.ECS.ScriptChanged.Entity') | The [Entity](ScriptChanged.Entity.md#'Friflo.Engine.ECS.ScriptChanged.Entity') that emitted the event - aka the publisher / subject. |
| [OldScript](ScriptChanged.OldScript.md#'Friflo.Engine.ECS.ScriptChanged.OldScript') | The [Script](Script.md#'Friflo.Engine.ECS.Script') before executing [Remove](ScriptChangedAction.md#Friflo.Engine.ECS.ScriptChangedAction.Remove#'Friflo.Engine.ECS.ScriptChangedAction.Remove') or [Replace](ScriptChangedAction.md#Friflo.Engine.ECS.ScriptChangedAction.Replace#'Friflo.Engine.ECS.ScriptChangedAction.Replace').<br/> Is null in case of [Add](ScriptChangedAction.md#Friflo.Engine.ECS.ScriptChangedAction.Add#'Friflo.Engine.ECS.ScriptChangedAction.Add'). |
| [Script](ScriptChanged.Script.md#'Friflo.Engine.ECS.ScriptChanged.Script') | The new [Script](Script.md#'Friflo.Engine.ECS.Script') after executing [Add](ScriptChangedAction.md#Friflo.Engine.ECS.ScriptChangedAction.Add#'Friflo.Engine.ECS.ScriptChangedAction.Add') or [Replace](ScriptChangedAction.md#Friflo.Engine.ECS.ScriptChangedAction.Replace#'Friflo.Engine.ECS.ScriptChangedAction.Replace').<br/> Is null in case of [Remove](ScriptChangedAction.md#Friflo.Engine.ECS.ScriptChangedAction.Remove#'Friflo.Engine.ECS.ScriptChangedAction.Remove'). |
| [ScriptType](ScriptChanged.ScriptType.md#'Friflo.Engine.ECS.ScriptChanged.ScriptType') | The [ScriptType](ScriptType.md#'Friflo.Engine.ECS.ScriptType') of the remove, added or replaced script. |

| Properties | |
| :--- | :--- |
| [Store](ScriptChanged.Store.md#'Friflo.Engine.ECS.ScriptChanged.Store') | The [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore') containing the [Entity](ScriptChanged.Entity.md#'Friflo.Engine.ECS.ScriptChanged.Entity') that emitted the event. |

| Methods | |
| :--- | :--- |
| [ToString()](ScriptChanged.ToString().md#'Friflo.Engine.ECS.ScriptChanged.ToString()') | |
