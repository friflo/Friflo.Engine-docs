#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[CommandBufferSynced](CommandBufferSynced.md 'Friflo.Engine.ECS.CommandBufferSynced')

## CommandBufferSynced.AddScript<T>(int, T) Method

Add the given [script](CommandBufferSynced.AddScript_T_(int,T).md#Friflo.Engine.ECS.CommandBufferSynced.AddScript_T_(int,T).script 'Friflo.Engine.ECS.CommandBufferSynced.AddScript<T>(int, T).script') to the entity with the passed [entityId](CommandBufferSynced.AddScript_T_(int,T).md#Friflo.Engine.ECS.CommandBufferSynced.AddScript_T_(int,T).entityId 'Friflo.Engine.ECS.CommandBufferSynced.AddScript<T>(int, T).entityId').

```csharp
public void AddScript<T>(int entityId, T script)
    where T : Friflo.Engine.ECS.Script, new();
```
#### Type parameters

<a name='Friflo.Engine.ECS.CommandBufferSynced.AddScript_T_(int,T).T'></a>

`T`
#### Parameters

<a name='Friflo.Engine.ECS.CommandBufferSynced.AddScript_T_(int,T).entityId'></a>

`entityId` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

<a name='Friflo.Engine.ECS.CommandBufferSynced.AddScript_T_(int,T).script'></a>

`script` [T](CommandBufferSynced.AddScript_T_(int,T).md#Friflo.Engine.ECS.CommandBufferSynced.AddScript_T_(int,T).T 'Friflo.Engine.ECS.CommandBufferSynced.AddScript<T>(int, T).T')

Implements [AddScript&lt;T&gt;(int, T)](ICommandBuffer.AddScript_T_(int,T).md 'Friflo.Engine.ECS.ICommandBuffer.AddScript<T>(int, T)')