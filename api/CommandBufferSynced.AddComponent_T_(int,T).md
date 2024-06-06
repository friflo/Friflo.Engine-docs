#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[CommandBufferSynced](CommandBufferSynced.md 'Friflo.Engine.ECS.CommandBufferSynced')

## CommandBufferSynced.AddComponent<T>(int, T) Method

Add the given [component](CommandBufferSynced.AddComponent_T_(int,T).md#Friflo.Engine.ECS.CommandBufferSynced.AddComponent_T_(int,T).component 'Friflo.Engine.ECS.CommandBufferSynced.AddComponent<T>(int, T).component') with type [T](CommandBufferSynced.AddComponent_T_(int,T).md#Friflo.Engine.ECS.CommandBufferSynced.AddComponent_T_(int,T).T 'Friflo.Engine.ECS.CommandBufferSynced.AddComponent<T>(int, T).T') to the entity with the passed [entityId](CommandBufferSynced.AddComponent_T_(int,T).md#Friflo.Engine.ECS.CommandBufferSynced.AddComponent_T_(int,T).entityId 'Friflo.Engine.ECS.CommandBufferSynced.AddComponent<T>(int, T).entityId').

```csharp
public void AddComponent<T>(int entityId, in T component)
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.CommandBufferSynced.AddComponent_T_(int,T).T'></a>

`T`
#### Parameters

<a name='Friflo.Engine.ECS.CommandBufferSynced.AddComponent_T_(int,T).entityId'></a>

`entityId` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

<a name='Friflo.Engine.ECS.CommandBufferSynced.AddComponent_T_(int,T).component'></a>

`component` [T](CommandBufferSynced.AddComponent_T_(int,T).md#Friflo.Engine.ECS.CommandBufferSynced.AddComponent_T_(int,T).T 'Friflo.Engine.ECS.CommandBufferSynced.AddComponent<T>(int, T).T')

Implements [AddComponent&lt;T&gt;(int, T)](ICommandBuffer.AddComponent_T_(int,T).md 'Friflo.Engine.ECS.ICommandBuffer.AddComponent<T>(int, T)')