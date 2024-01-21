#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## DebugEventHandler Struct

Used as item type in [DebugEventHandlers](DebugEventHandlers.md 'Friflo.Engine.ECS.DebugEventHandlers') providing the number of handlers for a specific event [Type](DebugEventHandler.Type.md 'Friflo.Engine.ECS.DebugEventHandler.Type').

```csharp
public readonly struct DebugEventHandler
```

| Fields | |
| :--- | :--- |
| [Kind](DebugEventHandler.Kind.md 'Friflo.Engine.ECS.DebugEventHandler.Kind') | The type of the event handlers: build-in events or custom signals. |
| [Type](DebugEventHandler.Type.md 'Friflo.Engine.ECS.DebugEventHandler.Type') | The [System.Type](https://docs.microsoft.com/en-us/dotnet/api/System.Type 'System.Type') used for an event / signal handler. |

| Properties | |
| :--- | :--- |
| [Count](DebugEventHandler.Count.md 'Friflo.Engine.ECS.DebugEventHandler.Count') | Number of event handlers for a specific event [Type](DebugEventHandler.Type.md 'Friflo.Engine.ECS.DebugEventHandler.Type') added to an entity. |

| Methods | |
| :--- | :--- |
| [ToString()](DebugEventHandler.ToString().md 'Friflo.Engine.ECS.DebugEventHandler.ToString()') | |
