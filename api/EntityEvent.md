#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS')

## EntityEvent Struct

The information about a structural change recorded by the [EventRecorder](EventRecorder.md#'Friflo.Engine.ECS.EventRecorder').

```csharp
public struct EntityEvent
```

| Fields | |
| :--- | :--- |
| [Action](EntityEvent.Action.md#'Friflo.Engine.ECS.EntityEvent.Action') | The change type - add / remove - of a component / tag. |
| [Id](EntityEvent.Id.md#'Friflo.Engine.ECS.EntityEvent.Id') | The id of the changed entity. |
| [Kind](EntityEvent.Kind.md#'Friflo.Engine.ECS.EntityEvent.Kind') | The kind - component / tag - of the structural change. |
| [TypeIndex](EntityEvent.TypeIndex.md#'Friflo.Engine.ECS.EntityEvent.TypeIndex') | The index in [EntitySchema](EntitySchema.md#'Friflo.Engine.ECS.EntitySchema') properties [Components](EntitySchema.Components.md#'Friflo.Engine.ECS.EntitySchema.Components') or [Tags](EntitySchema.Tags.md#'Friflo.Engine.ECS.EntitySchema.Tags'). |

| Methods | |
| :--- | :--- |
| [ToString()](EntityEvent.ToString().md#'Friflo.Engine.ECS.EntityEvent.ToString()') | |
