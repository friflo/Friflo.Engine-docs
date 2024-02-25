#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS.Serialize](Friflo.Engine.ECS.Serialize.md#'Friflo.Engine.ECS.Serialize')

## DataEntity Class

A [DataEntity](DataEntity.md#'Friflo.Engine.ECS.Serialize.DataEntity') is used to serialize entities.

```csharp
public sealed class DataEntity
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object#'System.Object') &#129106; DataEntity

### Remarks
When reading / writing [DataEntity](DataEntity.md#'Friflo.Engine.ECS.Serialize.DataEntity')'s in the editor a special MemoryDatabase" implementation is required.<br/>
This implementation preserves the order of entities stored in a JSON file.<br/>
Therefor it stores the order of each entity when loaded and apply this order when writing them back to the JSON file.<br/><br/>
Having a stable order is required avoid merge conflicts.<br/>
Otherwise the entity order in a JSON file would be arbitrary.<br/>
Even small changes will show a massive diff in version control.

| Fields | |
| :--- | :--- |
| [children](DataEntity.children.md#'Friflo.Engine.ECS.Serialize.DataEntity.children') | |
| [components](DataEntity.components.md#'Friflo.Engine.ECS.Serialize.DataEntity.components') | Each key in [components](DataEntity.components.md#'Friflo.Engine.ECS.Serialize.DataEntity.components') defines the type of a component or script. Its value is the component / script value. |
| [modify](DataEntity.modify.md#'Friflo.Engine.ECS.Serialize.DataEntity.modify') | Modify the referenced entity of a`preFab`.<br/> with [components](DataEntity.components.md#'Friflo.Engine.ECS.Serialize.DataEntity.components') != null<br/> Remove the referenced entity if [components](DataEntity.components.md#'Friflo.Engine.ECS.Serialize.DataEntity.components') == null |
| [pid](DataEntity.pid.md#'Friflo.Engine.ECS.Serialize.DataEntity.pid') | permanent id used to identify entities in a database |
| [prefab](DataEntity.prefab.md#'Friflo.Engine.ECS.Serialize.DataEntity.prefab') | Reference to the `Prefab` the entity is based on |
| [sceneName](DataEntity.sceneName.md#'Friflo.Engine.ECS.Serialize.DataEntity.sceneName') | if != null the entity is the root of a scene using the assigned [sceneName](DataEntity.sceneName.md#'Friflo.Engine.ECS.Serialize.DataEntity.sceneName') |
| [tags](DataEntity.tags.md#'Friflo.Engine.ECS.Serialize.DataEntity.tags') | List of tags assigned to an entity |

| Properties | |
| :--- | :--- |
| [DebugJSON](DataEntity.DebugJSON.md#'Friflo.Engine.ECS.Serialize.DataEntity.DebugJSON') | Return the <b>JSON</b> representation of a [DataEntity](DataEntity.md#'Friflo.Engine.ECS.Serialize.DataEntity'). |

| Methods | |
| :--- | :--- |
| [ToString()](DataEntity.ToString().md#'Friflo.Engine.ECS.Serialize.DataEntity.ToString()') | |
