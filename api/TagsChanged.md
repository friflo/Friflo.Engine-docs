#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## TagsChanged Struct

Is the event for event handlers added to [OnTagsChanged](Entity.OnTagsChanged.md 'Friflo.Engine.ECS.Entity.OnTagsChanged') or [OnTagsChanged](EntityStoreBase.OnTagsChanged.md 'Friflo.Engine.ECS.EntityStoreBase.OnTagsChanged').

```csharp
public readonly struct TagsChanged
```

### Remarks
These events are fired on:
- [AddTag&lt;TTag&gt;()](Entity.AddTag_TTag_().md 'Friflo.Engine.ECS.Entity.AddTag<TTag>()')
- [AddTags(Tags)](Entity.AddTags(Tags).md 'Friflo.Engine.ECS.Entity.AddTags(Friflo.Engine.ECS.Tags)')
- [RemoveTag&lt;TTag&gt;()](Entity.RemoveTag_TTag_().md 'Friflo.Engine.ECS.Entity.RemoveTag<TTag>()')
- [RemoveTags(Tags)](Entity.RemoveTags(Tags).md 'Friflo.Engine.ECS.Entity.RemoveTags(Friflo.Engine.ECS.Tags)')

| Fields | |
| :--- | :--- |
| [EntityId](TagsChanged.EntityId.md 'Friflo.Engine.ECS.TagsChanged.EntityId') | The `Id` of the [Entity](TagsChanged.Entity.md 'Friflo.Engine.ECS.TagsChanged.Entity') that emitted the event. |
| [OldTags](TagsChanged.OldTags.md 'Friflo.Engine.ECS.TagsChanged.OldTags') | The old state of the [Entity](TagsChanged.Entity.md 'Friflo.Engine.ECS.TagsChanged.Entity')[Tags](Entity.Tags.md 'Friflo.Engine.ECS.Entity.Tags') before the change. |
| [Store](TagsChanged.Store.md 'Friflo.Engine.ECS.TagsChanged.Store') | The [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') containing the [Entity](TagsChanged.Entity.md 'Friflo.Engine.ECS.TagsChanged.Entity') that emitted the event. |
| [Tags](TagsChanged.Tags.md 'Friflo.Engine.ECS.TagsChanged.Tags') | The new state of the [Entity](TagsChanged.Entity.md 'Friflo.Engine.ECS.TagsChanged.Entity')[Tags](Entity.Tags.md 'Friflo.Engine.ECS.Entity.Tags'). |

| Properties | |
| :--- | :--- |
| [AddedTags](TagsChanged.AddedTags.md 'Friflo.Engine.ECS.TagsChanged.AddedTags') | The [Tags](Tags.md 'Friflo.Engine.ECS.Tags') added to the [Entity](TagsChanged.Entity.md 'Friflo.Engine.ECS.TagsChanged.Entity'). |
| [ChangedTags](TagsChanged.ChangedTags.md 'Friflo.Engine.ECS.TagsChanged.ChangedTags') | The changed (removed / added) entity [Tags](Tags.md 'Friflo.Engine.ECS.Tags'). |
| [Entity](TagsChanged.Entity.md 'Friflo.Engine.ECS.TagsChanged.Entity') | The [Entity](TagsChanged.Entity.md 'Friflo.Engine.ECS.TagsChanged.Entity') that emitted the event - aka the publisher. |
| [RemovedTags](TagsChanged.RemovedTags.md 'Friflo.Engine.ECS.TagsChanged.RemovedTags') | The [Tags](Tags.md 'Friflo.Engine.ECS.Tags') removed from the [Entity](TagsChanged.Entity.md 'Friflo.Engine.ECS.TagsChanged.Entity'). |

| Methods | |
| :--- | :--- |
| [ToString()](TagsChanged.ToString().md 'Friflo.Engine.ECS.TagsChanged.ToString()') | |
