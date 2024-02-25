#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ScriptChangedAction Enum

The modification type of a [ScriptChanged](ScriptChanged.md 'Friflo.Engine.ECS.ScriptChanged') event: [Remove](ScriptChangedAction.md#Friflo.Engine.ECS.ScriptChangedAction.Remove 'Friflo.Engine.ECS.ScriptChangedAction.Remove'), [Add](ScriptChangedAction.md#Friflo.Engine.ECS.ScriptChangedAction.Add 'Friflo.Engine.ECS.ScriptChangedAction.Add') or [Replace](ScriptChangedAction.md#Friflo.Engine.ECS.ScriptChangedAction.Replace 'Friflo.Engine.ECS.ScriptChangedAction.Replace') script.

```csharp
public enum ScriptChangedAction : System.Byte
```
### Fields

<a name='Friflo.Engine.ECS.ScriptChangedAction.Add'></a>

`Add` 1

A [Script](Script.md 'Friflo.Engine.ECS.Script') was added to an [Entity](Entity.md 'Friflo.Engine.ECS.Entity').

<a name='Friflo.Engine.ECS.ScriptChangedAction.Remove'></a>

`Remove` 0

A [Script](Script.md 'Friflo.Engine.ECS.Script') was removed from an [Entity](Entity.md 'Friflo.Engine.ECS.Entity').

<a name='Friflo.Engine.ECS.ScriptChangedAction.Replace'></a>

`Replace` 2

An entity [Script](Script.md 'Friflo.Engine.ECS.Script') was replaced by another script.