#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## GenericInstanceTypeAttribute Class

The attribute is required to register specific type instances of generic component and tags types.
See example in remarks.

```csharp
public sealed class GenericInstanceTypeAttribute : System.Attribute
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; [System.Attribute](https://docs.microsoft.com/en-us/dotnet/api/System.Attribute 'System.Attribute') &#129106; GenericInstanceTypeAttribute

### Remarks
The following example registers a specific generic component instance `GenericComponent<int>`.<br/>
The key used for JSON serialization is `"comp-int"`.

```csharp
[GenericInstanceType("comp-int", typeof(int))] 
public struct GenericComponent<T> : IComponent {
    public T Value;
}
```

| Constructors | |
| :--- | :--- |
| [GenericInstanceTypeAttribute(string, Type, Type, Type)](GenericInstanceTypeAttribute.GenericInstanceTypeAttribute(string,Type,Type,Type).md 'Friflo.Engine.ECS.GenericInstanceTypeAttribute.GenericInstanceTypeAttribute(string, System.Type, System.Type, System.Type)') | Register generic component / tag type with three generic parameters. |
| [GenericInstanceTypeAttribute(string, Type, Type)](GenericInstanceTypeAttribute.GenericInstanceTypeAttribute(string,Type,Type).md 'Friflo.Engine.ECS.GenericInstanceTypeAttribute.GenericInstanceTypeAttribute(string, System.Type, System.Type)') | Register generic component / tag type with two generic parameters. |
| [GenericInstanceTypeAttribute(string, Type)](GenericInstanceTypeAttribute.GenericInstanceTypeAttribute(string,Type).md 'Friflo.Engine.ECS.GenericInstanceTypeAttribute.GenericInstanceTypeAttribute(string, System.Type)') | Register generic component / tag type with one generic parameter. |
