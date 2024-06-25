#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ComponentType Class

Provide meta data for an [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') struct.

```csharp
public abstract class ComponentType : Friflo.Engine.ECS.SchemaType
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; [SchemaType](SchemaType.md 'Friflo.Engine.ECS.SchemaType') &#129106; ComponentType

| Constructors | |
| :--- | :--- |
| [ComponentType(string, int, Type, Type, int)](ComponentType.ComponentType(string,int,Type,Type,int).md 'Friflo.Engine.ECS.ComponentType.ComponentType(string, int, System.Type, System.Type, int)') | |

| Fields | |
| :--- | :--- |
| [IndexType](ComponentType.IndexType.md 'Friflo.Engine.ECS.ComponentType.IndexType') | |
| [IsBlittable](ComponentType.IsBlittable.md 'Friflo.Engine.ECS.ComponentType.IsBlittable') | Return true if [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')'s of this type can be copied. |
| [StructIndex](ComponentType.StructIndex.md 'Friflo.Engine.ECS.ComponentType.StructIndex') | The index in [EntitySchema](EntitySchema.md 'Friflo.Engine.ECS.EntitySchema').[Components](EntitySchema.Components.md 'Friflo.Engine.ECS.EntitySchema.Components'). |
| [StructSize](ComponentType.StructSize.md 'Friflo.Engine.ECS.ComponentType.StructSize') | The size in bytes of the [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') struct. |
