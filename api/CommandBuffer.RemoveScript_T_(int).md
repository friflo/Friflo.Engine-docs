#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[CommandBuffer](CommandBuffer.md 'Friflo.Engine.ECS.CommandBuffer')

## CommandBuffer.RemoveScript<T>(int) Method

Remove the [Script](Script.md 'Friflo.Engine.ECS.Script') of the specified type [T](CommandBuffer.RemoveScript_T_(int).md#Friflo.Engine.ECS.CommandBuffer.RemoveScript_T_(int).T 'Friflo.Engine.ECS.CommandBuffer.RemoveScript<T>(int).T') from the entity with the passed [entityId](CommandBuffer.RemoveScript_T_(int).md#Friflo.Engine.ECS.CommandBuffer.RemoveScript_T_(int).entityId 'Friflo.Engine.ECS.CommandBuffer.RemoveScript<T>(int).entityId').

```csharp
public void RemoveScript<T>(int entityId)
    where T : Friflo.Engine.ECS.Script, new();
```
#### Type parameters

<a name='Friflo.Engine.ECS.CommandBuffer.RemoveScript_T_(int).T'></a>

`T`
#### Parameters

<a name='Friflo.Engine.ECS.CommandBuffer.RemoveScript_T_(int).entityId'></a>

`entityId` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

Implements [RemoveScript&lt;T&gt;(int)](ICommandBuffer.RemoveScript_T_(int).md 'Friflo.Engine.ECS.ICommandBuffer.RemoveScript<T>(int)')