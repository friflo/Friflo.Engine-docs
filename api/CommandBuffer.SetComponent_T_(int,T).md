#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[CommandBuffer](CommandBuffer.md 'Friflo.Engine.ECS.CommandBuffer')

## CommandBuffer.SetComponent<T>(int, T) Method

Set the given [component](CommandBuffer.SetComponent_T_(int,T).md#Friflo.Engine.ECS.CommandBuffer.SetComponent_T_(int,T).component 'Friflo.Engine.ECS.CommandBuffer.SetComponent<T>(int, T).component') with type [T](CommandBuffer.SetComponent_T_(int,T).md#Friflo.Engine.ECS.CommandBuffer.SetComponent_T_(int,T).T 'Friflo.Engine.ECS.CommandBuffer.SetComponent<T>(int, T).T') of the entity with the passed [entityId](CommandBuffer.SetComponent_T_(int,T).md#Friflo.Engine.ECS.CommandBuffer.SetComponent_T_(int,T).entityId 'Friflo.Engine.ECS.CommandBuffer.SetComponent<T>(int, T).entityId').

```csharp
public void SetComponent<T>(int entityId, in T component)
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.CommandBuffer.SetComponent_T_(int,T).T'></a>

`T`
#### Parameters

<a name='Friflo.Engine.ECS.CommandBuffer.SetComponent_T_(int,T).entityId'></a>

`entityId` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

<a name='Friflo.Engine.ECS.CommandBuffer.SetComponent_T_(int,T).component'></a>

`component` [T](CommandBuffer.SetComponent_T_(int,T).md#Friflo.Engine.ECS.CommandBuffer.SetComponent_T_(int,T).T 'Friflo.Engine.ECS.CommandBuffer.SetComponent<T>(int, T).T')