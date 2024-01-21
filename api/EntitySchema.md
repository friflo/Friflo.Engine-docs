#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## EntitySchema Class

```csharp
public sealed class EntitySchema
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; EntitySchema

| Properties | |
| :--- | :--- |
| [Components](EntitySchema.Components.md 'Friflo.Engine.ECS.EntitySchema.Components') | return all <b>component</b> types - structs implementing [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') |
| [ComponentTypeByType](EntitySchema.ComponentTypeByType.md 'Friflo.Engine.ECS.EntitySchema.ComponentTypeByType') | |
| [EngineDependants](EntitySchema.EngineDependants.md 'Friflo.Engine.ECS.EntitySchema.EngineDependants') | List of [System.Reflection.Assembly](https://docs.microsoft.com/en-us/dotnet/api/System.Reflection.Assembly 'System.Reflection.Assembly')'s referencing the <b>Fliox.Engine</b> assembly as dependency. |
| [SchemaTypeByKey](EntitySchema.SchemaTypeByKey.md 'Friflo.Engine.ECS.EntitySchema.SchemaTypeByKey') | |
| [Scripts](EntitySchema.Scripts.md 'Friflo.Engine.ECS.EntitySchema.Scripts') | return all [Script](Script.md 'Friflo.Engine.ECS.Script') types - classes extending [Script](Script.md 'Friflo.Engine.ECS.Script') |
| [ScriptTypeByType](EntitySchema.ScriptTypeByType.md 'Friflo.Engine.ECS.EntitySchema.ScriptTypeByType') | |
| [Tags](EntitySchema.Tags.md 'Friflo.Engine.ECS.EntitySchema.Tags') | return all <b>Tag</b> types - structs implementing [ITag](ITag.md 'Friflo.Engine.ECS.ITag') |
| [TagTypeByName](EntitySchema.TagTypeByName.md 'Friflo.Engine.ECS.EntitySchema.TagTypeByName') | |
| [TagTypeByType](EntitySchema.TagTypeByType.md 'Friflo.Engine.ECS.EntitySchema.TagTypeByType') | |

| Methods | |
| :--- | :--- |
| [GetComponentType&lt;T&gt;()](EntitySchema.GetComponentType_T_().md 'Friflo.Engine.ECS.EntitySchema.GetComponentType<T>()') | return teh [ComponentType](ComponentType.md 'Friflo.Engine.ECS.ComponentType') of a struct implementing [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent'). |
| [GetScriptType&lt;T&gt;()](EntitySchema.GetScriptType_T_().md 'Friflo.Engine.ECS.EntitySchema.GetScriptType<T>()') | return the [ScriptType](ScriptType.md 'Friflo.Engine.ECS.ScriptType') of a class extending [Script](Script.md 'Friflo.Engine.ECS.Script'). |
| [GetTagType&lt;T&gt;()](EntitySchema.GetTagType_T_().md 'Friflo.Engine.ECS.EntitySchema.GetTagType<T>()') | return the [TagType](TagType.md 'Friflo.Engine.ECS.TagType') of a struct implementing [ITag](ITag.md 'Friflo.Engine.ECS.ITag'). |
| [ToString()](EntitySchema.ToString().md 'Friflo.Engine.ECS.EntitySchema.ToString()') | |
