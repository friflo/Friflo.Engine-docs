#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS')

## EventRecorder Class

Used to record events of structural changes like add/remove component/tag.<br/>
The recorder is required to filter these events using an [EventFilter](EventFilter.md#'Friflo.Engine.ECS.EventFilter').

```csharp
public sealed class EventRecorder
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object#'System.Object') &#129106; EventRecorder

| Properties | |
| :--- | :--- |
| [AllEventsCount](EventRecorder.AllEventsCount.md#'Friflo.Engine.ECS.EventRecorder.AllEventsCount') | Return the number of all recorded events.<br/> Calling [ClearEvents()](EventRecorder.ClearEvents().md#'Friflo.Engine.ECS.EventRecorder.ClearEvents()') does not affect the counter. |
| [ComponentEvents](EventRecorder.ComponentEvents.md#'Friflo.Engine.ECS.EventRecorder.ComponentEvents') | The list of all recorded component events. |
| [Enabled](EventRecorder.Enabled.md#'Friflo.Engine.ECS.EventRecorder.Enabled') | Record component / tag events if true.<br/> It is required when using an [EventFilter](EventFilter.md#'Friflo.Engine.ECS.EventFilter'). |
| [TagEvents](EventRecorder.TagEvents.md#'Friflo.Engine.ECS.EventRecorder.TagEvents') | The list of all recorded tag events. |

| Methods | |
| :--- | :--- |
| [ClearEvents()](EventRecorder.ClearEvents().md#'Friflo.Engine.ECS.EventRecorder.ClearEvents()') | Clear all  [ComponentEvents](EventRecorder.ComponentEvents.md#'Friflo.Engine.ECS.EventRecorder.ComponentEvents') and [TagEvents](EventRecorder.TagEvents.md#'Friflo.Engine.ECS.EventRecorder.TagEvents'). |
| [ToString()](EventRecorder.ToString().md#'Friflo.Engine.ECS.EventRecorder.ToString()') | |
