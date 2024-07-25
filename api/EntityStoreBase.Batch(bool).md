#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStoreBase](EntityStoreBase.md 'Friflo.Engine.ECS.EntityStoreBase')

## EntityStoreBase.Batch(bool) Method

Returns a [CreateEntityBatch](CreateEntityBatch.md 'Friflo.Engine.ECS.CreateEntityBatch') used to create entities with components and tags added to the batch.<br/>
See <a href="https://friflo.gitbook.io/friflo.engine.ecs/examples/optimization#batch---create-entity">Example.</a>

```csharp
public Friflo.Engine.ECS.CreateEntityBatch Batch(bool autoReturn=true);
```
#### Parameters

<a name='Friflo.Engine.ECS.EntityStoreBase.Batch(bool).autoReturn'></a>

`autoReturn` [System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')

#### Returns
[CreateEntityBatch](CreateEntityBatch.md 'Friflo.Engine.ECS.CreateEntityBatch')

### Remarks
The returned batch creates an entity with previously added components and tags when calling
[CreateEntity()](CreateEntityBatch.CreateEntity().md 'Friflo.Engine.ECS.CreateEntityBatch.CreateEntity()').<br/><br/>
If [autoReturn](EntityStoreBase.Batch(bool).md#Friflo.Engine.ECS.EntityStoreBase.Batch(bool).autoReturn 'Friflo.Engine.ECS.EntityStoreBase.Batch(bool).autoReturn') == true the batch is returned to the EntityStore when
calling [CreateEntity()](CreateEntityBatch.CreateEntity().md 'Friflo.Engine.ECS.CreateEntityBatch.CreateEntity()').<br/>
Subsequent use of the batch throws [BatchAlreadyReturnedException](BatchAlreadyReturnedException.md 'Friflo.Engine.ECS.BatchAlreadyReturnedException').<br/><br/>
If [autoReturn](EntityStoreBase.Batch(bool).md#Friflo.Engine.ECS.EntityStoreBase.Batch(bool).autoReturn 'Friflo.Engine.ECS.EntityStoreBase.Batch(bool).autoReturn') == false [CreateEntity()](CreateEntityBatch.CreateEntity().md 'Friflo.Engine.ECS.CreateEntityBatch.CreateEntity()') can be called
multiple times to create multiple entities.<br/>
The caller should call [Return()](CreateEntityBatch.Return().md 'Friflo.Engine.ECS.CreateEntityBatch.Return()') after usage to prevent unnecessary memory allocations.<br/><br/>
When calling [CreateEntity()](CreateEntityBatch.CreateEntity().md 'Friflo.Engine.ECS.CreateEntityBatch.CreateEntity()') or [Return()](CreateEntityBatch.Return().md 'Friflo.Engine.ECS.CreateEntityBatch.Return()')
the batch executes without memory allocations.