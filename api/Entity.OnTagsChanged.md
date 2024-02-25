#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.OnTagsChanged Event

Add / remove an event handler for [TagsChanged](TagsChanged.md 'Friflo.Engine.ECS.TagsChanged') events triggered by:<br/>[AddTag&lt;TTag&gt;()](Entity.AddTag_TTag_().md 'Friflo.Engine.ECS.Entity.AddTag<TTag>()')<br/>[AddTags(Tags)](Entity.AddTags(Tags).md 'Friflo.Engine.ECS.Entity.AddTags(Friflo.Engine.ECS.Tags)')<br/>[RemoveTag&lt;TTag&gt;()](Entity.RemoveTag_TTag_().md 'Friflo.Engine.ECS.Entity.RemoveTag<TTag>()')<br/>[RemoveTags(Tags)](Entity.RemoveTags(Tags).md 'Friflo.Engine.ECS.Entity.RemoveTags(Friflo.Engine.ECS.Tags)').<br/>
See <a href="https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md#event">Example.</a>

```csharp
public event Action<TagsChanged> OnTagsChanged;
```

#### Event Type
[System.Action&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')[TagsChanged](TagsChanged.md 'Friflo.Engine.ECS.TagsChanged')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')