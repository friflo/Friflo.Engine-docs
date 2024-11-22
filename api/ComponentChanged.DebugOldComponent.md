#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[ComponentChanged](ComponentChanged.md 'Friflo.Engine.ECS.ComponentChanged')

## ComponentChanged.DebugOldComponent Property

Return the old [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') for debugging.<br/><b>Note</b>: It degrades performance as it boxes the returned component.

```csharp
public object DebugOldComponent { get; }
```

#### Property Value
[System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object')

### Remarks
To access the old component use [OldComponent&lt;T&gt;()](ComponentChanged.OldComponent_T_().md 'Friflo.Engine.ECS.ComponentChanged.OldComponent<T>()')