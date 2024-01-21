#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[ComponentChanged](ComponentChanged.md 'Friflo.Engine.ECS.ComponentChanged')

## ComponentChanged.DebugOldComponent Property

Return the old [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') for debugging.<br/><b>Note</b>: It degrades performance as it boxes the returned component.

```csharp
public Friflo.Engine.ECS.IComponent DebugOldComponent { get; }
```

#### Property Value
[IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')

### Remarks
To access the old component use [OldComponent&lt;T&gt;()](ComponentChanged.OldComponent_T_().md 'Friflo.Engine.ECS.ComponentChanged.OldComponent<T>()')