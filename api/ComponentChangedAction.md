#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ComponentChangedAction Enum

The modification type of a [ComponentChanged](ComponentChanged.md 'Friflo.Engine.ECS.ComponentChanged') event: [Remove](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Remove 'Friflo.Engine.ECS.ComponentChangedAction.Remove'), [Add](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Add 'Friflo.Engine.ECS.ComponentChangedAction.Add') or [Update](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Update 'Friflo.Engine.ECS.ComponentChangedAction.Update') component.

```csharp
public enum ComponentChangedAction
```
### Fields

<a name='Friflo.Engine.ECS.ComponentChangedAction.Add'></a>

`Add` 1

An [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') is added to an [Entity](Entity.md 'Friflo.Engine.ECS.Entity').

<a name='Friflo.Engine.ECS.ComponentChangedAction.Remove'></a>

`Remove` 0

An [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') is removed from an [Entity](Entity.md 'Friflo.Engine.ECS.Entity').

<a name='Friflo.Engine.ECS.ComponentChangedAction.Update'></a>

`Update` 2

An [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') of an [Entity](Entity.md 'Friflo.Engine.ECS.Entity') is updated when calling
           [AddComponent&lt;T&gt;()](Entity.AddComponent_T_().md 'Friflo.Engine.ECS.Entity.AddComponent<T>()') on an entity already having a component of a specific type.