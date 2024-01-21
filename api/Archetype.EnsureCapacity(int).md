#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype')

## Archetype.EnsureCapacity(int) Method

Allocates memory for entity components to enable adding / creating entities without reallocation.

```csharp
public int EnsureCapacity(int capacity);
```
#### Parameters

<a name='Friflo.Engine.ECS.Archetype.EnsureCapacity(int).capacity'></a>

`capacity` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

#### Returns
[System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')  
the number of entities that can be added without reallocation