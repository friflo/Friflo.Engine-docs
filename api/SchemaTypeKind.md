#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS')

## SchemaTypeKind Enum

Declares the [Kind](SchemaType.Kind.md#'Friflo.Engine.ECS.SchemaType.Kind') of a [SchemaType](SchemaType.md#'Friflo.Engine.ECS.SchemaType')

```csharp
public enum SchemaTypeKind : System.Byte
```
### Fields

<a name='Friflo.Engine.ECS.SchemaTypeKind.Component'></a>

`Component` 0

Declare a [ComponentType](ComponentType.md#'Friflo.Engine.ECS.ComponentType') is an [IComponent](IComponent.md#'Friflo.Engine.ECS.IComponent').

<a name='Friflo.Engine.ECS.SchemaTypeKind.Script'></a>

`Script` 1

Declare a [ScriptType](ScriptType.md#'Friflo.Engine.ECS.ScriptType') is a [Script](SchemaTypeKind.md#Friflo.Engine.ECS.SchemaTypeKind.Script#'Friflo.Engine.ECS.SchemaTypeKind.Script').

<a name='Friflo.Engine.ECS.SchemaTypeKind.Tag'></a>

`Tag` 2

Declare a [TagType](TagType.md#'Friflo.Engine.ECS.TagType') is an [ITag](ITag.md#'Friflo.Engine.ECS.ITag').

### Remarks
A <b>Tag</b> is defined by struct definition without fields / properties extending [ITag](ITag.md#'Friflo.Engine.ECS.ITag').