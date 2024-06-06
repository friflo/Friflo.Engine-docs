#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[CommandBuffer](CommandBuffer.md 'Friflo.Engine.ECS.CommandBuffer')

## CommandBuffer.AddChild(int, int) Method

Add the entity with the given [childId](CommandBuffer.AddChild(int,int).md#Friflo.Engine.ECS.CommandBuffer.AddChild(int,int).childId 'Friflo.Engine.ECS.CommandBuffer.AddChild(int, int).childId') as a child to the entity with the passed [parentId](CommandBuffer.AddChild(int,int).md#Friflo.Engine.ECS.CommandBuffer.AddChild(int,int).parentId 'Friflo.Engine.ECS.CommandBuffer.AddChild(int, int).parentId').

```csharp
public void AddChild(int parentId, int childId);
```
#### Parameters

<a name='Friflo.Engine.ECS.CommandBuffer.AddChild(int,int).parentId'></a>

`parentId` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

<a name='Friflo.Engine.ECS.CommandBuffer.AddChild(int,int).childId'></a>

`childId` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

Implements [AddChild(int, int)](ICommandBuffer.AddChild(int,int).md 'Friflo.Engine.ECS.ICommandBuffer.AddChild(int, int)')