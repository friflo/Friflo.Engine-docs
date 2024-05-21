#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Systems](Friflo.Engine.ECS.Systems.md 'Friflo.Engine.ECS.Systems')

## SystemChanged Struct

The event for event handlers added to [OnSystemChanged](BaseSystem.OnSystemChanged.md 'Friflo.Engine.ECS.Systems.BaseSystem.OnSystemChanged').

```csharp
public readonly struct SystemChanged
```

### Remarks
These events are fired on:
- [Add(BaseSystem)](SystemGroup.Add(BaseSystem).md 'Friflo.Engine.ECS.Systems.SystemGroup.Add(Friflo.Engine.ECS.Systems.BaseSystem)')
- [Insert(int, BaseSystem)](SystemGroup.Insert(int,BaseSystem).md 'Friflo.Engine.ECS.Systems.SystemGroup.Insert(int, Friflo.Engine.ECS.Systems.BaseSystem)')
- [Remove(BaseSystem)](SystemGroup.Remove(BaseSystem).md 'Friflo.Engine.ECS.Systems.SystemGroup.Remove(Friflo.Engine.ECS.Systems.BaseSystem)')
- [MoveSystemTo(SystemGroup, int)](BaseSystem.MoveSystemTo(SystemGroup,int).md 'Friflo.Engine.ECS.Systems.BaseSystem.MoveSystemTo(Friflo.Engine.ECS.Systems.SystemGroup, int)')
- [CastSystemUpdate(string, object)](BaseSystem.CastSystemUpdate(string,object).md 'Friflo.Engine.ECS.Systems.BaseSystem.CastSystemUpdate(string, object)')

| Fields | |
| :--- | :--- |
| [action](SystemChanged.action.md 'Friflo.Engine.ECS.Systems.SystemChanged.action') | The [SystemChangedAction](SystemChangedAction.md 'Friflo.Engine.ECS.Systems.SystemChangedAction') type of the system change. |
| [field](SystemChanged.field.md 'Friflo.Engine.ECS.Systems.SystemChanged.field') | The name of the changed system field. |
| [system](SystemChanged.system.md 'Friflo.Engine.ECS.Systems.SystemChanged.system') | The changed system. |
| [value](SystemChanged.value.md 'Friflo.Engine.ECS.Systems.SystemChanged.value') | The value of a changed system field. |

| Methods | |
| :--- | :--- |
| [ToString()](SystemChanged.ToString().md 'Friflo.Engine.ECS.Systems.SystemChanged.ToString()') | |
