#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityBatch](EntityBatch.md 'Friflo.Engine.ECS.EntityBatch')

## EntityBatch.Apply() Method

Apply added batch commands to the entity the preceding [Batch()](Entity.Batch().md 'Friflo.Engine.ECS.Entity.Batch()') operates.<br/><br/>
Subsequent use of the batch throws [BatchAlreadyAppliedException](BatchAlreadyAppliedException.md 'Friflo.Engine.ECS.BatchAlreadyAppliedException').

```csharp
public void Apply();
```