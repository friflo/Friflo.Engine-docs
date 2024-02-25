#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[EventFilter](EventFilter.md#'Friflo.Engine.ECS.EventFilter')

## EventFilter.HasEvent(int) Method

Returns true if a component or tag was added / removed to / from the entity with the passed [entityId](EventFilter.HasEvent(int).md#Friflo.Engine.ECS.EventFilter.HasEvent(int).entityId#'Friflo.Engine.ECS.EventFilter.HasEvent(int).entityId').

```csharp
public bool HasEvent(int entityId);
```
#### Parameters

<a name='Friflo.Engine.ECS.EventFilter.HasEvent(int).entityId'></a>

`entityId` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32#'System.Int32')

#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean#'System.Boolean')

### Remarks
Therefore [EventRecorder](EntityStore.EventRecorder.md#'Friflo.Engine.ECS.EntityStore.EventRecorder') needs to be enabled and<br/> 
the component / tag (add / remove) events of interest need to be added to the [EventFilter](EventFilter.md#'Friflo.Engine.ECS.EventFilter').<br/><br/><b>Note</b>: [HasEvent(int)](EventFilter.HasEvent(int).md#'Friflo.Engine.ECS.EventFilter.HasEvent(int)') can be called from any thread.<br/>
No structural changes like adding / removing components/tags must not be executed at the same time by another thread.