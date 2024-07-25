#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.Batch() Method

Returns an [EntityBatch](EntityBatch.md 'Friflo.Engine.ECS.EntityBatch') to add/remove components or tags to/from this entity using the batch.<br/>
See <a href="https://friflo.gitbook.io/friflo.engine.ecs/examples/optimization#batch---entity">Example.</a>

```csharp
public Friflo.Engine.ECS.EntityBatch Batch();
```

#### Returns
[EntityBatch](EntityBatch.md 'Friflo.Engine.ECS.EntityBatch')

### Remarks
The returned batch is used to add/removed components and tags.<br/>
These changes are applied to the entity when calling [Apply()](EntityBatch.Apply().md 'Friflo.Engine.ECS.EntityBatch.Apply()').<br/><br/>
Subsequent use of the batch throws [BatchAlreadyAppliedException](BatchAlreadyAppliedException.md 'Friflo.Engine.ECS.BatchAlreadyAppliedException').<br/><br/>
If missing the [Apply()](EntityBatch.Apply().md 'Friflo.Engine.ECS.EntityBatch.Apply()') call:<br/>
- Entity changes are not applied.<br/>
- Some unnecessary memory allocations.<br/><br/>
When calling [Apply()](EntityBatch.Apply().md 'Friflo.Engine.ECS.EntityBatch.Apply()') the batch executes without memory allocations.