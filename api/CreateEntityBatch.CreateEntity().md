#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[CreateEntityBatch](CreateEntityBatch.md#'Friflo.Engine.ECS.CreateEntityBatch')

## CreateEntityBatch.CreateEntity() Method

Creates an entity with the components and tags previously added.<br/>
Added batch components and tags are not cleared.

```csharp
public Friflo.Engine.ECS.Entity CreateEntity();
```

#### Returns
[Entity](Entity.md#'Friflo.Engine.ECS.Entity')

### Remarks
Subsequent use of a batch returned by `Batch(autoReturn: true)` throws [BatchAlreadyReturnedException](BatchAlreadyReturnedException.md#'Friflo.Engine.ECS.BatchAlreadyReturnedException').