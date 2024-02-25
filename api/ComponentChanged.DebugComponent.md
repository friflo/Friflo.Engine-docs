#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[ComponentChanged](ComponentChanged.md#'Friflo.Engine.ECS.ComponentChanged')

## ComponentChanged.DebugComponent Property

Return the current [IComponent](IComponent.md#'Friflo.Engine.ECS.IComponent') for debugging.<br/><b>Note</b>: It degrades performance as it boxes the returned component.

```csharp
public Friflo.Engine.ECS.IComponent DebugComponent { get; }
```

#### Property Value
[IComponent](IComponent.md#'Friflo.Engine.ECS.IComponent')

### Remarks
To access the current component use [Component&lt;T&gt;()](ComponentChanged.Component_T_().md#'Friflo.Engine.ECS.ComponentChanged.Component<T>()')