#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[CommandBuffer](CommandBuffer.md 'Friflo.Engine.ECS.CommandBuffer')

## CommandBuffer.AddComponent<T>(int) Method

Add the [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') with type [T](CommandBuffer.AddComponent_T_(int).md#Friflo.Engine.ECS.CommandBuffer.AddComponent_T_(int).T 'Friflo.Engine.ECS.CommandBuffer.AddComponent<T>(int).T') to the entity with the passed [entityId](CommandBuffer.AddComponent_T_(int).md#Friflo.Engine.ECS.CommandBuffer.AddComponent_T_(int).entityId 'Friflo.Engine.ECS.CommandBuffer.AddComponent<T>(int).entityId').

```csharp
public void AddComponent<T>(int entityId)
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.CommandBuffer.AddComponent_T_(int).T'></a>

`T`
#### Parameters

<a name='Friflo.Engine.ECS.CommandBuffer.AddComponent_T_(int).entityId'></a>

`entityId` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')