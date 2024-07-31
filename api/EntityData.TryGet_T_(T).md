#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityData](EntityData.md 'Friflo.Engine.ECS.EntityData')

## EntityData.TryGet<T>(T) Method

Gets the component of the specififed type.<br/>
Returns true if the entity contains a component of specified type. Otherwise false.

```csharp
public bool TryGet<T>(out T value)
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityData.TryGet_T_(T).T'></a>

`T`
#### Parameters

<a name='Friflo.Engine.ECS.EntityData.TryGet_T_(T).value'></a>

`value` [T](EntityData.TryGet_T_(T).md#Friflo.Engine.ECS.EntityData.TryGet_T_(T).T 'Friflo.Engine.ECS.EntityData.TryGet<T>(T).T')

#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')

#### Exceptions

[System.NullReferenceException](https://docs.microsoft.com/en-us/dotnet/api/System.NullReferenceException 'System.NullReferenceException')  
if the entity is deleted.

### Remarks
Executes in O(1)