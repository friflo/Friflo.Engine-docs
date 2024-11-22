#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityComponent](EntityComponent.md 'Friflo.Engine.ECS.EntityComponent')

## EntityComponent.Value Property

Property is mainly used to display a component value in the Debugger.<br/>
It has poor performance as is boxes the returned component.

```csharp
public object Value { get; }
```

#### Property Value
[System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object')

### Remarks
To access a component use [GetComponent&lt;T&gt;()](Entity.GetComponent_T_().md 'Friflo.Engine.ECS.Entity.GetComponent<T>()')