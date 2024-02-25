#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ComponentChanged Struct

Is the event for event handlers added to [OnComponentChanged](Entity.OnComponentChanged.md 'Friflo.Engine.ECS.Entity.OnComponentChanged'),
[OnComponentAdded](EntityStoreBase.OnComponentAdded.md 'Friflo.Engine.ECS.EntityStoreBase.OnComponentAdded') or [OnComponentRemoved](EntityStoreBase.OnComponentRemoved.md 'Friflo.Engine.ECS.EntityStoreBase.OnComponentRemoved').

```csharp
public readonly struct ComponentChanged
```

### Remarks
These events are fired on:
- [AddComponent&lt;T&gt;()](Entity.AddComponent_T_().md 'Friflo.Engine.ECS.Entity.AddComponent<T>()')
- [RemoveComponent&lt;T&gt;()](Entity.RemoveComponent_T_().md 'Friflo.Engine.ECS.Entity.RemoveComponent<T>()')

| Fields | |
| :--- | :--- |
| [Action](ComponentChanged.Action.md 'Friflo.Engine.ECS.ComponentChanged.Action') | The executed entity change: [Remove](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Remove 'Friflo.Engine.ECS.ComponentChangedAction.Remove'),             [Add](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Add 'Friflo.Engine.ECS.ComponentChangedAction.Add') or [Remove](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Remove 'Friflo.Engine.ECS.ComponentChangedAction.Remove') component. |
| [EntityId](ComponentChanged.EntityId.md 'Friflo.Engine.ECS.ComponentChanged.EntityId') | The `Id` of the [Entity](ComponentChanged.Entity.md 'Friflo.Engine.ECS.ComponentChanged.Entity') that emitted the event. |
| [Store](ComponentChanged.Store.md 'Friflo.Engine.ECS.ComponentChanged.Store') | The [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') containing the [Entity](ComponentChanged.Entity.md 'Friflo.Engine.ECS.ComponentChanged.Entity') that emitted the event. |
| [StructIndex](ComponentChanged.StructIndex.md 'Friflo.Engine.ECS.ComponentChanged.StructIndex') | |

| Properties | |
| :--- | :--- |
| [ComponentType](ComponentChanged.ComponentType.md 'Friflo.Engine.ECS.ComponentChanged.ComponentType') | The [ComponentType](ComponentType.md 'Friflo.Engine.ECS.ComponentType') of the added / removed component. |
| [DebugComponent](ComponentChanged.DebugComponent.md 'Friflo.Engine.ECS.ComponentChanged.DebugComponent') | Return the current [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') for debugging.<br/><b>Note</b>: It degrades performance as it boxes the returned component. |
| [DebugOldComponent](ComponentChanged.DebugOldComponent.md 'Friflo.Engine.ECS.ComponentChanged.DebugOldComponent') | Return the old [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') for debugging.<br/><b>Note</b>: It degrades performance as it boxes the returned component. |
| [Entity](ComponentChanged.Entity.md 'Friflo.Engine.ECS.ComponentChanged.Entity') | The [Entity](ComponentChanged.Entity.md 'Friflo.Engine.ECS.ComponentChanged.Entity') that emitted the event - aka the publisher. |
| [Type](ComponentChanged.Type.md 'Friflo.Engine.ECS.ComponentChanged.Type') | The [System.Type](https://docs.microsoft.com/en-us/dotnet/api/System.Type 'System.Type') of the added / removed component. |

| Methods | |
| :--- | :--- |
| [Component&lt;T&gt;()](ComponentChanged.Component_T_().md 'Friflo.Engine.ECS.ComponentChanged.Component<T>()') | Returns the current component value after executing the [Add](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Add 'Friflo.Engine.ECS.ComponentChangedAction.Add') or [Update](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Update 'Friflo.Engine.ECS.ComponentChangedAction.Update') component.<br/> |
| [OldComponent&lt;T&gt;()](ComponentChanged.OldComponent_T_().md 'Friflo.Engine.ECS.ComponentChanged.OldComponent<T>()') | Returns the old component value before executing [Update](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Update 'Friflo.Engine.ECS.ComponentChangedAction.Update') or [Remove](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Remove 'Friflo.Engine.ECS.ComponentChangedAction.Remove') component.<br/><b>Note</b>: See Remarks for restrictions. |
| [ToString()](ComponentChanged.ToString().md 'Friflo.Engine.ECS.ComponentChanged.ToString()') | |
