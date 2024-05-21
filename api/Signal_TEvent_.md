#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## Signal<TEvent> Struct

[Signal&lt;TEvent&gt;](Signal_TEvent_.md 'Friflo.Engine.ECS.Signal<TEvent>')'s are used to emit custom events from an entity to custom [Signal&lt;TEvent&gt;](Signal_TEvent_.md 'Friflo.Engine.ECS.Signal<TEvent>') handlers.<br/>
            See <a href="https://github.com/friflo/Friflo.Json.Fliox/wiki/Examples-~-General#signal">Example.</a>

```csharp
public readonly struct Signal<TEvent>
    where TEvent : struct, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.Signal_TEvent_.TEvent'></a>

`TEvent`

The event type containing the fields of a custom event.

### Remarks
[Signal&lt;TEvent&gt;](Signal_TEvent_.md 'Friflo.Engine.ECS.Signal<TEvent>') handlers are added with [AddSignalHandler&lt;TEvent&gt;(Action&lt;Signal&lt;TEvent&gt;&gt;)](Entity.AddSignalHandler_TEvent_(Action_Signal_TEvent__).md 'Friflo.Engine.ECS.Entity.AddSignalHandler<TEvent>(System.Action<Friflo.Engine.ECS.Signal<TEvent>>)').<br/>
            They are used to implement the <a href="https://en.wikipedia.org/wiki/Observer_pattern">Observer pattern</a>
            on entity level in the engine.<br/><br/>
            It enables decoupling the code used for emitting events from a specific entity (aka subject / publisher)<br/>
            to multiple subscribers (aka observers) consuming the event by their [Signal&lt;TEvent&gt;](Signal_TEvent_.md 'Friflo.Engine.ECS.Signal<TEvent>') handlers.

| Fields | |
| :--- | :--- |
| [EntityId](Signal_TEvent_.EntityId.md 'Friflo.Engine.ECS.Signal<TEvent>.EntityId') | The id of the [Entity](Signal_TEvent_.Entity.md 'Friflo.Engine.ECS.Signal<TEvent>.Entity') that emitted the [Event](Signal_TEvent_.Event.md 'Friflo.Engine.ECS.Signal<TEvent>.Event') with [EmitSignal&lt;TEvent&gt;(TEvent)](Entity.EmitSignal_TEvent_(TEvent).md 'Friflo.Engine.ECS.Entity.EmitSignal<TEvent>(TEvent)'). |
| [Event](Signal_TEvent_.Event.md 'Friflo.Engine.ECS.Signal<TEvent>.Event') | The [Event](Signal_TEvent_.Event.md 'Friflo.Engine.ECS.Signal<TEvent>.Event') containing event specific data passed to [EmitSignal&lt;TEvent&gt;(TEvent)](Entity.EmitSignal_TEvent_(TEvent).md 'Friflo.Engine.ECS.Entity.EmitSignal<TEvent>(TEvent)'). |
| [Store](Signal_TEvent_.Store.md 'Friflo.Engine.ECS.Signal<TEvent>.Store') | The [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') containing the [Entity](Signal_TEvent_.Entity.md 'Friflo.Engine.ECS.Signal<TEvent>.Entity') that emitted the [Event](Signal_TEvent_.Event.md 'Friflo.Engine.ECS.Signal<TEvent>.Event'). |

| Properties | |
| :--- | :--- |
| [Entity](Signal_TEvent_.Entity.md 'Friflo.Engine.ECS.Signal<TEvent>.Entity') | The [Entity](Signal_TEvent_.Entity.md 'Friflo.Engine.ECS.Signal<TEvent>.Entity') that emitted the [Event](Signal_TEvent_.Event.md 'Friflo.Engine.ECS.Signal<TEvent>.Event') with [EmitSignal&lt;TEvent&gt;(TEvent)](Entity.EmitSignal_TEvent_(TEvent).md 'Friflo.Engine.ECS.Entity.EmitSignal<TEvent>(TEvent)') - aka the publisher. |

| Methods | |
| :--- | :--- |
| [ToString()](Signal_TEvent_.ToString().md 'Friflo.Engine.ECS.Signal<TEvent>.ToString()') | |
