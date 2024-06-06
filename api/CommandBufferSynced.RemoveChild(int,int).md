#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[CommandBufferSynced](CommandBufferSynced.md 'Friflo.Engine.ECS.CommandBufferSynced')

## CommandBufferSynced.RemoveChild(int, int) Method

Remove the child entity with given [childId](CommandBufferSynced.RemoveChild(int,int).md#Friflo.Engine.ECS.CommandBufferSynced.RemoveChild(int,int).childId 'Friflo.Engine.ECS.CommandBufferSynced.RemoveChild(int, int).childId') from the parent entity with the the passed [parentId](CommandBufferSynced.RemoveChild(int,int).md#Friflo.Engine.ECS.CommandBufferSynced.RemoveChild(int,int).parentId 'Friflo.Engine.ECS.CommandBufferSynced.RemoveChild(int, int).parentId').

```csharp
public void RemoveChild(int parentId, int childId);
```
#### Parameters

<a name='Friflo.Engine.ECS.CommandBufferSynced.RemoveChild(int,int).parentId'></a>

`parentId` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

<a name='Friflo.Engine.ECS.CommandBufferSynced.RemoveChild(int,int).childId'></a>

`childId` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

Implements [RemoveChild(int, int)](ICommandBuffer.RemoveChild(int,int).md 'Friflo.Engine.ECS.ICommandBuffer.RemoveChild(int, int)')