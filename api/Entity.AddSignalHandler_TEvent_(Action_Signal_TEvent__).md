#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.AddSignalHandler<TEvent>(Action<Signal<TEvent>>) Method

Add the given [Signal&lt;TEvent&gt;](Signal_TEvent_.md 'Friflo.Engine.ECS.Signal<TEvent>') handler to the entity.<br/>
See <a href="https://friflo.gitbook.io/friflo.engine.ecs/examples/general#signal">Example.</a>

```csharp
public System.Action<Friflo.Engine.ECS.Signal<TEvent>> AddSignalHandler<TEvent>(System.Action<Friflo.Engine.ECS.Signal<TEvent>> handler)
    where TEvent : struct, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Entity.AddSignalHandler_TEvent_(System.Action_Friflo.Engine.ECS.Signal_TEvent__).TEvent'></a>

`TEvent`
#### Parameters

<a name='Friflo.Engine.ECS.Entity.AddSignalHandler_TEvent_(System.Action_Friflo.Engine.ECS.Signal_TEvent__).handler'></a>

`handler` [System.Action&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')[Friflo.Engine.ECS.Signal&lt;](Signal_TEvent_.md 'Friflo.Engine.ECS.Signal<TEvent>')[TEvent](Entity.AddSignalHandler_TEvent_(Action_Signal_TEvent__).md#Friflo.Engine.ECS.Entity.AddSignalHandler_TEvent_(System.Action_Friflo.Engine.ECS.Signal_TEvent__).TEvent 'Friflo.Engine.ECS.Entity.AddSignalHandler<TEvent>(System.Action<Friflo.Engine.ECS.Signal<TEvent>>).TEvent')[&gt;](Signal_TEvent_.md 'Friflo.Engine.ECS.Signal<TEvent>')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')

#### Returns
[System.Action&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')[Friflo.Engine.ECS.Signal&lt;](Signal_TEvent_.md 'Friflo.Engine.ECS.Signal<TEvent>')[TEvent](Entity.AddSignalHandler_TEvent_(Action_Signal_TEvent__).md#Friflo.Engine.ECS.Entity.AddSignalHandler_TEvent_(System.Action_Friflo.Engine.ECS.Signal_TEvent__).TEvent 'Friflo.Engine.ECS.Entity.AddSignalHandler<TEvent>(System.Action<Friflo.Engine.ECS.Signal<TEvent>>).TEvent')[&gt;](Signal_TEvent_.md 'Friflo.Engine.ECS.Signal<TEvent>')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Action-1 'System.Action`1')  
The the signal handler added to the entity.<br/>
            Practical when passing a lambda that can be removed later with [RemoveSignalHandler&lt;TEvent&gt;(Action&lt;Signal&lt;TEvent&gt;&gt;)](Entity.RemoveSignalHandler_TEvent_(Action_Signal_TEvent__).md 'Friflo.Engine.ECS.Entity.RemoveSignalHandler<TEvent>(System.Action<Friflo.Engine.ECS.Signal<TEvent>>)').