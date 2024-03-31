#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

## EntityStore.GetEntityById(int) Method

Returns the [Entity](Entity.md 'Friflo.Engine.ECS.Entity') with the passed [id](EntityStore.GetEntityById(int).md#Friflo.Engine.ECS.EntityStore.GetEntityById(int).id 'Friflo.Engine.ECS.EntityStore.GetEntityById(int).id').<br/>
The returned entity can be null ([IsNull](Entity.IsNull.md 'Friflo.Engine.ECS.Entity.IsNull') == true).

```csharp
public Friflo.Engine.ECS.Entity GetEntityById(int id);
```
#### Parameters

<a name='Friflo.Engine.ECS.EntityStore.GetEntityById(int).id'></a>

`id` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

#### Returns
[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

#### Exceptions

[System.IndexOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/System.IndexOutOfRangeException 'System.IndexOutOfRangeException')  
In case passed [id](EntityStore.GetEntityById(int).md#Friflo.Engine.ECS.EntityStore.GetEntityById(int).id 'Friflo.Engine.ECS.EntityStore.GetEntityById(int).id') invalid (id >= [Capacity](EntityStore.Capacity.md 'Friflo.Engine.ECS.EntityStore.Capacity')).