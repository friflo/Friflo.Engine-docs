#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[CommandBufferSynced](CommandBufferSynced.md 'Friflo.Engine.ECS.CommandBufferSynced')

## CommandBufferSynced.SetComponent<T>(int, T) Method

Set the given [component](CommandBufferSynced.SetComponent_T_(int,T).md#Friflo.Engine.ECS.CommandBufferSynced.SetComponent_T_(int,T).component 'Friflo.Engine.ECS.CommandBufferSynced.SetComponent<T>(int, T).component') with type [T](CommandBufferSynced.SetComponent_T_(int,T).md#Friflo.Engine.ECS.CommandBufferSynced.SetComponent_T_(int,T).T 'Friflo.Engine.ECS.CommandBufferSynced.SetComponent<T>(int, T).T') of the entity with the passed [entityId](CommandBufferSynced.SetComponent_T_(int,T).md#Friflo.Engine.ECS.CommandBufferSynced.SetComponent_T_(int,T).entityId 'Friflo.Engine.ECS.CommandBufferSynced.SetComponent<T>(int, T).entityId').

```csharp
public void SetComponent<T>(int entityId, in T component)
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.CommandBufferSynced.SetComponent_T_(int,T).T'></a>

`T`
#### Parameters

<a name='Friflo.Engine.ECS.CommandBufferSynced.SetComponent_T_(int,T).entityId'></a>

`entityId` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

<a name='Friflo.Engine.ECS.CommandBufferSynced.SetComponent_T_(int,T).component'></a>

`component` [T](CommandBufferSynced.SetComponent_T_(int,T).md#Friflo.Engine.ECS.CommandBufferSynced.SetComponent_T_(int,T).T 'Friflo.Engine.ECS.CommandBufferSynced.SetComponent<T>(int, T).T')

Implements [SetComponent&lt;T&gt;(int, T)](ICommandBuffer.SetComponent_T_(int,T).md 'Friflo.Engine.ECS.ICommandBuffer.SetComponent<T>(int, T)')