#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[SchemaType](SchemaType.md 'Friflo.Engine.ECS.SchemaType')

## SchemaType.ComponentKey Field

If [Kind](SchemaType.Kind.md 'Friflo.Engine.ECS.SchemaType.Kind') is a [Component](SchemaTypeKind.md#Friflo.Engine.ECS.SchemaTypeKind.Component 'Friflo.Engine.ECS.SchemaTypeKind.Component') or a [Script](Script.md 'Friflo.Engine.ECS.Script') the key assigned
with [ComponentKeyAttribute](ComponentKeyAttribute.md 'Friflo.Engine.ECS.ComponentKeyAttribute').<br/>
If null the component is not serialized.

```csharp
public readonly string ComponentKey;
```

#### Field Value
[System.String](https://docs.microsoft.com/en-us/dotnet/api/System.String 'System.String')