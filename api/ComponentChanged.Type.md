#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[ComponentChanged](ComponentChanged.md#'Friflo.Engine.ECS.ComponentChanged')

## ComponentChanged.Type Property

The [System.Type](https://docs.microsoft.com/en-us/dotnet/api/System.Type#'System.Type') of the added / removed component.

```csharp
public System.Type Type { get; }
```

#### Property Value
[System.Type](https://docs.microsoft.com/en-us/dotnet/api/System.Type#'System.Type')

### Remarks
Use the following code snippet to switch on [Type](ComponentChanged.Type.md#'Friflo.Engine.ECS.ComponentChanged.Type'):
<br/>

```csharp
var type = args.Type;
switch (true) {
    case true when type == typeof(EntityName):
        break;
    case true when type == typeof(Position):
        break;
}
```