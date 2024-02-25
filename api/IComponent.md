#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS')

## IComponent Interface

To enable adding a struct component to an [Entity](Entity.md#'Friflo.Engine.ECS.Entity') it need to implement [IComponent](IComponent.md#'Friflo.Engine.ECS.IComponent').<br/>[IComponent](IComponent.md#'Friflo.Engine.ECS.IComponent') types are <b>struct</b>s which only contains data <b>but no</b> script / methods.<br/>
See <a href="https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md#component">Example.</a>

```csharp
public interface IComponent
```

Derived  
&#8627; [EntityName](EntityName.md#'Friflo.Engine.ECS.EntityName')  
&#8627; [Position](Position.md#'Friflo.Engine.ECS.Position')  
&#8627; [Rotation](Rotation.md#'Friflo.Engine.ECS.Rotation')  
&#8627; [Scale3](Scale3.md#'Friflo.Engine.ECS.Scale3')  
&#8627; [Transform](Transform.md#'Friflo.Engine.ECS.Transform')  
&#8627; [UniqueEntity](UniqueEntity.md#'Friflo.Engine.ECS.UniqueEntity')  
&#8627; [Unresolved](Unresolved.md#'Friflo.Engine.ECS.Unresolved')

### Remarks
An [Entity](Entity.md#'Friflo.Engine.ECS.Entity') can contain multiple components but only one of each type.<br/><br/>
Optionally attribute the implementing struct with [ComponentKeyAttribute](ComponentKeyAttribute.md#'Friflo.Engine.ECS.ComponentKeyAttribute')<br/>
to assign a custom component key name used for JSON serialization.<br/><br/>
Common game specific [IComponent](IComponent.md#'Friflo.Engine.ECS.IComponent') types defined by the Engine:
- [EntityName](EntityName.md#'Friflo.Engine.ECS.EntityName')
- [UniqueEntity](UniqueEntity.md#'Friflo.Engine.ECS.UniqueEntity')
- [Position](Position.md#'Friflo.Engine.ECS.Position')
- [Rotation](Rotation.md#'Friflo.Engine.ECS.Rotation')
- [Scale3](Scale3.md#'Friflo.Engine.ECS.Scale3')
- [Transform](Transform.md#'Friflo.Engine.ECS.Transform')