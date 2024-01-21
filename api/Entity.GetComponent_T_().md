#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.GetComponent<T>() Method

Return the component of the given type as a reference.

```csharp
public ref T GetComponent<T>()
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Entity.GetComponent_T_().T'></a>

`T`

#### Returns
[T](Entity.GetComponent_T_().md#Friflo.Engine.ECS.Entity.GetComponent_T_().T 'Friflo.Engine.ECS.Entity.GetComponent<T>().T')

#### Exceptions

[System.NullReferenceException](https://docs.microsoft.com/en-us/dotnet/api/System.NullReferenceException 'System.NullReferenceException')  
if entity has no component of Type [T](Entity.GetComponent_T_().md#Friflo.Engine.ECS.Entity.GetComponent_T_().T 'Friflo.Engine.ECS.Entity.GetComponent<T>().T')

### Remarks
Executes in O(1)