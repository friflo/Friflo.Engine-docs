#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[CommandBufferSynced](CommandBufferSynced.md 'Friflo.Engine.ECS.CommandBufferSynced')

## CommandBufferSynced.RemoveComponent<T>(int) Method

Remove the [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') with type [T](CommandBufferSynced.RemoveComponent_T_(int).md#Friflo.Engine.ECS.CommandBufferSynced.RemoveComponent_T_(int).T 'Friflo.Engine.ECS.CommandBufferSynced.RemoveComponent<T>(int).T') from the entity with the passed [entityId](CommandBufferSynced.RemoveComponent_T_(int).md#Friflo.Engine.ECS.CommandBufferSynced.RemoveComponent_T_(int).entityId 'Friflo.Engine.ECS.CommandBufferSynced.RemoveComponent<T>(int).entityId').

```csharp
public void RemoveComponent<T>(int entityId)
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.CommandBufferSynced.RemoveComponent_T_(int).T'></a>

`T`
#### Parameters

<a name='Friflo.Engine.ECS.CommandBufferSynced.RemoveComponent_T_(int).entityId'></a>

`entityId` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

Implements [RemoveComponent&lt;T&gt;(int)](ICommandBuffer.RemoveComponent_T_(int).md 'Friflo.Engine.ECS.ICommandBuffer.RemoveComponent<T>(int)')