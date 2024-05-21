#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## EventFilter Class

Used to filter structural changes made to an entity like added / removed components / tags using [HasEvent(int)](EventFilter.HasEvent(int).md 'Friflo.Engine.ECS.EventFilter.HasEvent(int)').<br/>
The [EventRecorder](EntityStore.EventRecorder.md 'Friflo.Engine.ECS.EntityStore.EventRecorder') must be enabled to get add / remove events.<br/>
See <a href="https://github.com/friflo/Friflo.Json.Fliox/wiki/Examples-~-Optimization#eventfilter">Example.</a>

```csharp
public sealed class EventFilter
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; EventFilter

| Constructors | |
| :--- | :--- |
| [EventFilter(EventRecorder)](EventFilter.EventFilter(EventRecorder).md 'Friflo.Engine.ECS.EventFilter.EventFilter(Friflo.Engine.ECS.EventRecorder)') | Create and event filter for the passed [EventRecorder](EventRecorder.md 'Friflo.Engine.ECS.EventRecorder'). |

| Methods | |
| :--- | :--- |
| [ComponentAdded&lt;T&gt;()](EventFilter.ComponentAdded_T_().md 'Friflo.Engine.ECS.EventFilter.ComponentAdded<T>()') | Enable filtering add component events of the given [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') type [T](EventFilter.ComponentAdded_T_().md#Friflo.Engine.ECS.EventFilter.ComponentAdded_T_().T 'Friflo.Engine.ECS.EventFilter.ComponentAdded<T>().T'). |
| [ComponentRemoved&lt;T&gt;()](EventFilter.ComponentRemoved_T_().md 'Friflo.Engine.ECS.EventFilter.ComponentRemoved<T>()') | Enable filtering remove component events of the given [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') type [T](EventFilter.ComponentRemoved_T_().md#Friflo.Engine.ECS.EventFilter.ComponentRemoved_T_().T 'Friflo.Engine.ECS.EventFilter.ComponentRemoved<T>().T'). |
| [HasEvent(int)](EventFilter.HasEvent(int).md 'Friflo.Engine.ECS.EventFilter.HasEvent(int)') | Returns true if a component or tag was added / removed to / from the entity with the passed [entityId](EventFilter.HasEvent(int).md#Friflo.Engine.ECS.EventFilter.HasEvent(int).entityId 'Friflo.Engine.ECS.EventFilter.HasEvent(int).entityId'). |
| [TagAdded&lt;T&gt;()](EventFilter.TagAdded_T_().md 'Friflo.Engine.ECS.EventFilter.TagAdded<T>()') | Enable filtering add tag events of the given [ITag](ITag.md 'Friflo.Engine.ECS.ITag') type [T](EventFilter.TagAdded_T_().md#Friflo.Engine.ECS.EventFilter.TagAdded_T_().T 'Friflo.Engine.ECS.EventFilter.TagAdded<T>().T'). |
| [TagRemoved&lt;T&gt;()](EventFilter.TagRemoved_T_().md 'Friflo.Engine.ECS.EventFilter.TagRemoved<T>()') | Enable filtering remove tag events of the given [ITag](ITag.md 'Friflo.Engine.ECS.ITag') type [T](EventFilter.TagRemoved_T_().md#Friflo.Engine.ECS.EventFilter.TagRemoved_T_().T 'Friflo.Engine.ECS.EventFilter.TagRemoved<T>().T'). |
| [ToString()](EventFilter.ToString().md 'Friflo.Engine.ECS.EventFilter.ToString()') | |
