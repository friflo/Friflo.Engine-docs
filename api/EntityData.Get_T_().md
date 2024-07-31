#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityData](EntityData.md 'Friflo.Engine.ECS.EntityData')

## EntityData.Get<T>() Method

Return the component of the given type as a reference.

```csharp
public ref T Get<T>()
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityData.Get_T_().T'></a>

`T`

#### Returns
[T](EntityData.Get_T_().md#Friflo.Engine.ECS.EntityData.Get_T_().T 'Friflo.Engine.ECS.EntityData.Get<T>().T')

#### Exceptions

[System.NullReferenceException](https://docs.microsoft.com/en-us/dotnet/api/System.NullReferenceException 'System.NullReferenceException')  
if the entity is deleted or has no component of Type [T](EntityData.Get_T_().md#Friflo.Engine.ECS.EntityData.Get_T_().T 'Friflo.Engine.ECS.EntityData.Get<T>().T')

### Remarks
Executes in O(1)