#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[Entity](Entity.md#'Friflo.Engine.ECS.Entity')

## Entity.TryGetComponent<T>(T) Method

```csharp
public bool TryGetComponent<T>(out T result)
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Entity.TryGetComponent_T_(T).T'></a>

`T`
#### Parameters

<a name='Friflo.Engine.ECS.Entity.TryGetComponent_T_(T).result'></a>

`result` [T](Entity.TryGetComponent_T_(T).md#Friflo.Engine.ECS.Entity.TryGetComponent_T_(T).T#'Friflo.Engine.ECS.Entity.TryGetComponent<T>(T).T')

#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean#'System.Boolean')

### Remarks
Executes in O(1)