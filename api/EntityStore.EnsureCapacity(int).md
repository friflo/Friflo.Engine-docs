#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[EntityStore](EntityStore.md#'Friflo.Engine.ECS.EntityStore')

## EntityStore.EnsureCapacity(int) Method

Allocates memory for entities in the store to enable creating entities without reallocation.

```csharp
public int EnsureCapacity(int capacity);
```
#### Parameters

<a name='Friflo.Engine.ECS.EntityStore.EnsureCapacity(int).capacity'></a>

`capacity` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32#'System.Int32')

#### Returns
[System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32#'System.Int32')  
The number of entities that can be added without reallocation.