#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[SchemaType](SchemaType.md 'Friflo.Engine.ECS.SchemaType')

## SchemaType.Type Field

If [Kind](SchemaType.Kind.md 'Friflo.Engine.ECS.SchemaType.Kind') == [Tag](SchemaTypeKind.md#Friflo.Engine.ECS.SchemaTypeKind.Tag 'Friflo.Engine.ECS.SchemaTypeKind.Tag') the type of a <b>tag</b> struct implementing [ITag](ITag.md 'Friflo.Engine.ECS.ITag').<br/>
If [Kind](SchemaType.Kind.md 'Friflo.Engine.ECS.SchemaType.Kind') == [Component](SchemaTypeKind.md#Friflo.Engine.ECS.SchemaTypeKind.Component 'Friflo.Engine.ECS.SchemaTypeKind.Component') the type of a <b>component</b> struct implementing [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent').<br/>
If [Kind](SchemaType.Kind.md 'Friflo.Engine.ECS.SchemaType.Kind') == [Script](Script.md 'Friflo.Engine.ECS.Script') the type of a <b>script</b> class extending [Script](Script.md 'Friflo.Engine.ECS.Script').<br/>

```csharp
public readonly Type Type;
```

#### Field Value
[System.Type](https://docs.microsoft.com/en-us/dotnet/api/System.Type 'System.Type')