#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.DebugEventHandlers Property

Return event and signal handlers added to the entity.

```csharp
public Friflo.Engine.ECS.DebugEventHandlers DebugEventHandlers { get; }
```

#### Property Value
[DebugEventHandlers](DebugEventHandlers.md 'Friflo.Engine.ECS.DebugEventHandlers')

### Remarks
<b>Note</b>:
            Should be used only for debugging as it allocates arrays and do multiple Dictionary lookups.<br/>
            No allocations or lookups are made in case [TypeCount](DebugEventHandlers.TypeCount.md 'Friflo.Engine.ECS.DebugEventHandlers.TypeCount') is 0.