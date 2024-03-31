#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ComponentKeyAttribute Class

Assign a custom key used for JSON serialization for annotated [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') and [Script](Script.md 'Friflo.Engine.ECS.Script') types.<br/>
If specified key is null The component type is not serialized.

```csharp
public sealed class ComponentKeyAttribute : System.Attribute
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; [System.Attribute](https://docs.microsoft.com/en-us/dotnet/api/System.Attribute 'System.Attribute') &#129106; ComponentKeyAttribute

### Remarks
The attribute is used for:
- annotated structs implementing [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent').<br/>
- annotated classes extending [Script](Script.md 'Friflo.Engine.ECS.Script').<br/><br/>
This enables changing a struct / class name in code without changing the JSON serialization format.

| Constructors | |
| :--- | :--- |
| [ComponentKeyAttribute(string)](ComponentKeyAttribute.ComponentKeyAttribute(string).md 'Friflo.Engine.ECS.ComponentKeyAttribute.ComponentKeyAttribute(string)') | |
