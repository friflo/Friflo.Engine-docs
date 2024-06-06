#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[CommandBuffer](CommandBuffer.md 'Friflo.Engine.ECS.CommandBuffer')

## CommandBuffer.AddTag<T>(int) Method

Add the [ITag](ITag.md 'Friflo.Engine.ECS.ITag') with type [T](CommandBuffer.AddTag_T_(int).md#Friflo.Engine.ECS.CommandBuffer.AddTag_T_(int).T 'Friflo.Engine.ECS.CommandBuffer.AddTag<T>(int).T') to the entity with the passed [entityId](CommandBuffer.AddTag_T_(int).md#Friflo.Engine.ECS.CommandBuffer.AddTag_T_(int).entityId 'Friflo.Engine.ECS.CommandBuffer.AddTag<T>(int).entityId').

```csharp
public void AddTag<T>(int entityId)
    where T : struct, Friflo.Engine.ECS.ITag, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.CommandBuffer.AddTag_T_(int).T'></a>

`T`
#### Parameters

<a name='Friflo.Engine.ECS.CommandBuffer.AddTag_T_(int).entityId'></a>

`entityId` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

Implements [AddTag&lt;T&gt;(int)](ICommandBuffer.AddTag_T_(int).md 'Friflo.Engine.ECS.ICommandBuffer.AddTag<T>(int)')