#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS')

## DebugEntityEventKind Enum

Event type of a [DebugEventHandler](DebugEventHandler.md#'Friflo.Engine.ECS.DebugEventHandler'): [Event](DebugEntityEventKind.md#Friflo.Engine.ECS.DebugEntityEventKind.Event#'Friflo.Engine.ECS.DebugEntityEventKind.Event') or [Signal](DebugEntityEventKind.md#Friflo.Engine.ECS.DebugEntityEventKind.Signal#'Friflo.Engine.ECS.DebugEntityEventKind.Signal').

```csharp
public enum DebugEntityEventKind
```
### Fields

<a name='Friflo.Engine.ECS.DebugEntityEventKind.Event'></a>

`Event` 0

Mark event handlers added with:<br/>[OnComponentChanged](Entity.OnComponentChanged.md#'Friflo.Engine.ECS.Entity.OnComponentChanged')<br/>[OnTagsChanged](Entity.OnTagsChanged.md#'Friflo.Engine.ECS.Entity.OnTagsChanged')<br/>[OnScriptChanged](Entity.OnScriptChanged.md#'Friflo.Engine.ECS.Entity.OnScriptChanged')<br/>[OnChildEntitiesChanged](Entity.OnChildEntitiesChanged.md#'Friflo.Engine.ECS.Entity.OnChildEntitiesChanged').

<a name='Friflo.Engine.ECS.DebugEntityEventKind.Signal'></a>

`Signal` 1

Mark signal handlers added with  [AddSignalHandler&lt;TEvent&gt;(Action&lt;Signal&lt;TEvent&gt;&gt;)](Entity.AddSignalHandler_TEvent_(Action_Signal_TEvent__).md#'Friflo.Engine.ECS.Entity.AddSignalHandler<TEvent>(System.Action<Friflo.Engine.ECS.Signal<TEvent>>)').