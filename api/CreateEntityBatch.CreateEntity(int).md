#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[CreateEntityBatch](CreateEntityBatch.md 'Friflo.Engine.ECS.CreateEntityBatch')

## CreateEntityBatch.CreateEntity(int) Method

Creates an entity with the specified [id](CreateEntityBatch.CreateEntity(int).md#Friflo.Engine.ECS.CreateEntityBatch.CreateEntity(int).id 'Friflo.Engine.ECS.CreateEntityBatch.CreateEntity(int).id') and the components and tags previously added.<br/>
Added batch components and tags are not cleared.

```csharp
public Friflo.Engine.ECS.Entity CreateEntity(int id);
```
#### Parameters

<a name='Friflo.Engine.ECS.CreateEntityBatch.CreateEntity(int).id'></a>

`id` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

#### Returns
[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

### Remarks
Subsequent use of a batch returned by `Batch(autoReturn: true)` throws [BatchAlreadyReturnedException](BatchAlreadyReturnedException.md 'Friflo.Engine.ECS.BatchAlreadyReturnedException').