#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.RemoveSignalHandler<TEvent>(Action<Signal<TEvent>>) Method

Remove the given [Signal&lt;TEvent&gt;](Signal_TEvent_.md 'Friflo.Engine.ECS.Signal<TEvent>') handler from the entity.

```csharp
public bool RemoveSignalHandler<TEvent>(System.Action<Friflo.Engine.ECS.Signal<TEvent>> handler)
    where TEvent : struct, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Entity.RemoveSignalHandler_TEvent_(System.Action_Friflo.Engine.ECS.Signal_TEvent__).TEvent'></a>

`TEvent`
#### Parameters

<a name='Friflo.Engine.ECS.Entity.RemoveSignalHandler_TEvent_(System.Action_Friflo.Engine.ECS.Signal_TEvent__).handler'></a>

`handler` [System.Action&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')[Friflo.Engine.ECS.Signal&lt;](Signal_TEvent_.md 'Friflo.Engine.ECS.Signal<TEvent>')[TEvent](Entity.RemoveSignalHandler_TEvent_(Action_Signal_TEvent__).md#Friflo.Engine.ECS.Entity.RemoveSignalHandler_TEvent_(System.Action_Friflo.Engine.ECS.Signal_TEvent__).TEvent 'Friflo.Engine.ECS.Entity.RemoveSignalHandler<TEvent>(System.Action<Friflo.Engine.ECS.Signal<TEvent>>).TEvent')[&gt;](Signal_TEvent_.md 'Friflo.Engine.ECS.Signal<TEvent>')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')

#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
`true` in case the the passed signal handler was found.