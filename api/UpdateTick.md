#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## UpdateTick Struct

Specify [deltaTime](UpdateTick.deltaTime.md 'Friflo.Engine.ECS.UpdateTick.deltaTime') and [time](UpdateTick.time.md 'Friflo.Engine.ECS.UpdateTick.time') for system execution in [Update(UpdateTick)](SystemGroup.Update(UpdateTick).md 'Friflo.Engine.ECS.Systems.SystemGroup.Update(Friflo.Engine.ECS.UpdateTick)').

```csharp
public readonly struct UpdateTick
```

### Remarks
In case of Unity:<br/>`MonoBehaviour.Update()`:      `Time.deltaTime`,      `Time.time`<br/>`MonoBehaviour.LateUpdate()`:  `Time.deltaTime`,      `Time.time`<br/>`MonoBehaviour.FixedUpdate()`: `Time.fixedDeltaTime`, `Time.fixedTime`<br/>

| Constructors | |
| :--- | :--- |
| [UpdateTick(float, float)](UpdateTick.UpdateTick(float,float).md 'Friflo.Engine.ECS.UpdateTick.UpdateTick(float, float)') | Create a [UpdateTick](UpdateTick.md 'Friflo.Engine.ECS.UpdateTick') with the given [deltaTime](UpdateTick.UpdateTick(float,float).md#Friflo.Engine.ECS.UpdateTick.UpdateTick(float,float).deltaTime 'Friflo.Engine.ECS.UpdateTick.UpdateTick(float, float).deltaTime') and [time](UpdateTick.UpdateTick(float,float).md#Friflo.Engine.ECS.UpdateTick.UpdateTick(float,float).time 'Friflo.Engine.ECS.UpdateTick.UpdateTick(float, float).time'). |

| Fields | |
| :--- | :--- |
| [deltaTime](UpdateTick.deltaTime.md 'Friflo.Engine.ECS.UpdateTick.deltaTime') | The elapsed time since previous [Update(UpdateTick)](SystemGroup.Update(UpdateTick).md 'Friflo.Engine.ECS.Systems.SystemGroup.Update(Friflo.Engine.ECS.UpdateTick)') execution. |
| [time](UpdateTick.time.md 'Friflo.Engine.ECS.UpdateTick.time') | The time at the beginning of the current frame. |

| Methods | |
| :--- | :--- |
| [ToString()](UpdateTick.ToString().md 'Friflo.Engine.ECS.UpdateTick.ToString()') | |
