#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[ScriptChanged](ScriptChanged.md#'Friflo.Engine.ECS.ScriptChanged')

## ScriptChanged.Script Field

The new [Script](Script.md#'Friflo.Engine.ECS.Script') after executing [Add](ScriptChangedAction.md#Friflo.Engine.ECS.ScriptChangedAction.Add#'Friflo.Engine.ECS.ScriptChangedAction.Add') or [Replace](ScriptChangedAction.md#Friflo.Engine.ECS.ScriptChangedAction.Replace#'Friflo.Engine.ECS.ScriptChangedAction.Replace').<br/>
Is null in case of [Remove](ScriptChangedAction.md#Friflo.Engine.ECS.ScriptChangedAction.Remove#'Friflo.Engine.ECS.ScriptChangedAction.Remove').

```csharp
public readonly Script Script;
```

#### Field Value
[Script](Script.md#'Friflo.Engine.ECS.Script')

### Remarks
Use the following code snippet to switch on [Script](ScriptChanged.Script.md#'Friflo.Engine.ECS.ScriptChanged.Script') type:
<br/>

```csharp
switch (args.Script) {
    case TestScript1 script1:
        break;
    case TestScript2 script2:
        break;
}
```