#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS')

## Unresolved Struct

[Unresolved](Unresolved.md#'Friflo.Engine.ECS.Unresolved') is a container for unresolved entity components.

```csharp
public struct Unresolved :
Friflo.Engine.ECS.IComponent
```

Implements [IComponent](IComponent.md#'Friflo.Engine.ECS.IComponent')

### Remarks
An [Unresolved](Unresolved.md#'Friflo.Engine.ECS.Unresolved') component is added to an [Entity](Entity.md#'Friflo.Engine.ECS.Entity') by [DataEntityToEntity(DataEntity, EntityStore, string)](EntityConverter.DataEntityToEntity(DataEntity,EntityStore,string).md#'Friflo.Engine.ECS.Serialize.EntityConverter.DataEntityToEntity(Friflo.Engine.ECS.Serialize.DataEntity, Friflo.Engine.ECS.EntityStore, string)') if:<br/>
- A component in [DataEntity](DataEntity.md#'Friflo.Engine.ECS.Serialize.DataEntity').[components](DataEntity.components.md#'Friflo.Engine.ECS.Serialize.DataEntity.components') cannot be resolved to an [IComponent](IComponent.md#'Friflo.Engine.ECS.IComponent') or [Script](Script.md#'Friflo.Engine.ECS.Script') type.
- A tag in [DataEntity](DataEntity.md#'Friflo.Engine.ECS.Serialize.DataEntity').[tags](DataEntity.tags.md#'Friflo.Engine.ECS.Serialize.DataEntity.tags')  cannot be resolved to an [ITag](ITag.md#'Friflo.Engine.ECS.ITag') type.
The [Unresolved](Unresolved.md#'Friflo.Engine.ECS.Unresolved') component enables conversion of a [DataEntity](DataEntity.md#'Friflo.Engine.ECS.Serialize.DataEntity') to an [Entity](Entity.md#'Friflo.Engine.ECS.Entity') and vice versa<br/>
with components or tags that cannot be resolved to [ITag](ITag.md#'Friflo.Engine.ECS.ITag'), [IComponent](IComponent.md#'Friflo.Engine.ECS.IComponent') and [Script](Script.md#'Friflo.Engine.ECS.Script') types.<br/><br/>
Having support [Unresolved](Unresolved.md#'Friflo.Engine.ECS.Unresolved') component or tag types:
- Ensures the ability to use an [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore') containing unresolved types without being blocked by a missing fix.
- Prevents data loss of tags or components when storing an [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore') with entities containing unresolved tag or component types.
The reason for unresolved tag or component types can be:<br/>
- Missed to merge C# code containing an [ITag](ITag.md#'Friflo.Engine.ECS.ITag'), an [IComponent](IComponent.md#'Friflo.Engine.ECS.IComponent') or [Script](Script.md#'Friflo.Engine.ECS.Script') type definition.
- Intentionally when creating an [EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore') with external tools without the need to wait for the implementation of new<br/>[ITag](ITag.md#'Friflo.Engine.ECS.ITag'), an [IComponent](IComponent.md#'Friflo.Engine.ECS.IComponent') or [Script](Script.md#'Friflo.Engine.ECS.Script') type definitions.

| Fields | |
| :--- | :--- |
| [components](Unresolved.components.md#'Friflo.Engine.ECS.Unresolved.components') | |
| [tags](Unresolved.tags.md#'Friflo.Engine.ECS.Unresolved.tags') | |

| Methods | |
| :--- | :--- |
| [ToString()](Unresolved.ToString().md#'Friflo.Engine.ECS.Unresolved.ToString()') | |
