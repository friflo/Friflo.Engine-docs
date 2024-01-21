#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## SchemaType Class

```csharp
public abstract class SchemaType
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; SchemaType

Derived  
&#8627; [ComponentType](ComponentType.md 'Friflo.Engine.ECS.ComponentType')  
&#8627; [ScriptType](ScriptType.md 'Friflo.Engine.ECS.ScriptType')  
&#8627; [TagType](TagType.md 'Friflo.Engine.ECS.TagType')

| Fields | |
| :--- | :--- |
| [ComponentKey](SchemaType.ComponentKey.md 'Friflo.Engine.ECS.SchemaType.ComponentKey') | If [Kind](SchemaType.Kind.md 'Friflo.Engine.ECS.SchemaType.Kind') is a [Component](SchemaTypeKind.md#Friflo.Engine.ECS.SchemaTypeKind.Component 'Friflo.Engine.ECS.SchemaTypeKind.Component') or a [Script](Script.md 'Friflo.Engine.ECS.Script') the key assigned in [ComponentKeyAttribute](ComponentKeyAttribute.md 'Friflo.Engine.ECS.ComponentKeyAttribute') |
| [Kind](SchemaType.Kind.md 'Friflo.Engine.ECS.SchemaType.Kind') | |
| [Name](SchemaType.Name.md 'Friflo.Engine.ECS.SchemaType.Name') | |
| [Type](SchemaType.Type.md 'Friflo.Engine.ECS.SchemaType.Type') | If [Kind](SchemaType.Kind.md 'Friflo.Engine.ECS.SchemaType.Kind') == [Tag](SchemaTypeKind.md#Friflo.Engine.ECS.SchemaTypeKind.Tag 'Friflo.Engine.ECS.SchemaTypeKind.Tag') the type of a component struct implementing [ITag](ITag.md 'Friflo.Engine.ECS.ITag')<br/> If [Kind](SchemaType.Kind.md 'Friflo.Engine.ECS.SchemaType.Kind') == [Component](SchemaTypeKind.md#Friflo.Engine.ECS.SchemaTypeKind.Component 'Friflo.Engine.ECS.SchemaTypeKind.Component') the type of a component struct implementing [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')<br/> If [Kind](SchemaType.Kind.md 'Friflo.Engine.ECS.SchemaType.Kind') == [Script](Script.md 'Friflo.Engine.ECS.Script') the type of a script class extending [Script](Script.md 'Friflo.Engine.ECS.Script')<br/> |
