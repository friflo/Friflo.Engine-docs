#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.EmitSignal<TEvent>(TEvent) Method

Emits the passed signal event to all signal handlers added with [AddSignalHandler&lt;TEvent&gt;(Action&lt;Signal&lt;TEvent&gt;&gt;)](Entity.AddSignalHandler_TEvent_(Action_Signal_TEvent__).md 'Friflo.Engine.ECS.Entity.AddSignalHandler<TEvent>(System.Action<Friflo.Engine.ECS.Signal<TEvent>>)').

```csharp
public void EmitSignal<TEvent>(in TEvent ev)
    where TEvent : struct, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Entity.EmitSignal_TEvent_(TEvent).TEvent'></a>

`TEvent`
#### Parameters

<a name='Friflo.Engine.ECS.Entity.EmitSignal_TEvent_(TEvent).ev'></a>

`ev` [TEvent](Entity.EmitSignal_TEvent_(TEvent).md#Friflo.Engine.ECS.Entity.EmitSignal_TEvent_(TEvent).TEvent 'Friflo.Engine.ECS.Entity.EmitSignal<TEvent>(TEvent).TEvent')

### Remarks
It executes in ~10 nano seconds per signal handler.