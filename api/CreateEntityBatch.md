#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## CreateEntityBatch Class

A create batch is used to optimize entity creation.<br/>
Components and tags are buffered before creating an entity with [CreateEntity()](CreateEntityBatch.CreateEntity().md 'Friflo.Engine.ECS.CreateEntityBatch.CreateEntity()').

```csharp
public sealed class CreateEntityBatch
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; CreateEntityBatch

### Remarks
Multiple entities can be created using the same batch.<br/><br/>
Creating an entity via a batch stores the entity directly in the target [Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype')<br/>
This prevents any structural changes caused when creating an entity in steps using<br/>[CreateEntity()](EntityStore.CreateEntity().md 'Friflo.Engine.ECS.EntityStore.CreateEntity()') an subsequent calls to [AddComponent&lt;T&gt;()](Entity.AddComponent_T_().md 'Friflo.Engine.ECS.Entity.AddComponent<T>()')
and [AddTag&lt;TTag&gt;()](Entity.AddTag_TTag_().md 'Friflo.Engine.ECS.Entity.AddTag<TTag>()').

| Constructors | |
| :--- | :--- |
| [CreateEntityBatch(EntityStoreBase)](CreateEntityBatch.CreateEntityBatch(EntityStoreBase).md 'Friflo.Engine.ECS.CreateEntityBatch.CreateEntityBatch(Friflo.Engine.ECS.EntityStoreBase)') | Creates a batch used to create entities with components and tags added to the batch.<br/> The created batch instance can be cached. |

| Properties | |
| :--- | :--- |
| [ComponentCount](CreateEntityBatch.ComponentCount.md 'Friflo.Engine.ECS.CreateEntityBatch.ComponentCount') | Return the of components added to the batch. |
| [TagCount](CreateEntityBatch.TagCount.md 'Friflo.Engine.ECS.CreateEntityBatch.TagCount') | Return the of tags added to the batch. |

| Methods | |
| :--- | :--- |
| [Add&lt;T&gt;()](CreateEntityBatch.Add_T_().md 'Friflo.Engine.ECS.CreateEntityBatch.Add<T>()') | Add a component that will be added to the entity when calling [CreateEntity()](CreateEntityBatch.CreateEntity().md 'Friflo.Engine.ECS.CreateEntityBatch.CreateEntity()'). |
| [Add&lt;T&gt;(T)](CreateEntityBatch.Add_T_(T).md 'Friflo.Engine.ECS.CreateEntityBatch.Add<T>(T)') | Add the given [component](CreateEntityBatch.Add_T_(T).md#Friflo.Engine.ECS.CreateEntityBatch.Add_T_(T).component 'Friflo.Engine.ECS.CreateEntityBatch.Add<T>(T).component') that will be added to the entity when calling [CreateEntity()](CreateEntityBatch.CreateEntity().md 'Friflo.Engine.ECS.CreateEntityBatch.CreateEntity()'). |
| [AddTag&lt;T&gt;()](CreateEntityBatch.AddTag_T_().md 'Friflo.Engine.ECS.CreateEntityBatch.AddTag<T>()') | Add a tag that will be added to the entity when calling [CreateEntity()](CreateEntityBatch.CreateEntity().md 'Friflo.Engine.ECS.CreateEntityBatch.CreateEntity()'). |
| [AddTags(Tags)](CreateEntityBatch.AddTags(Tags).md 'Friflo.Engine.ECS.CreateEntityBatch.AddTags(Friflo.Engine.ECS.Tags)') | Adds the given [tags](CreateEntityBatch.AddTags(Tags).md#Friflo.Engine.ECS.CreateEntityBatch.AddTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.CreateEntityBatch.AddTags(Friflo.Engine.ECS.Tags).tags') that will be added to the entity when calling [CreateEntity()](CreateEntityBatch.CreateEntity().md 'Friflo.Engine.ECS.CreateEntityBatch.CreateEntity()'). |
| [Clear()](CreateEntityBatch.Clear().md 'Friflo.Engine.ECS.CreateEntityBatch.Clear()') | Clear all components and tags previously added to the batch. |
| [CreateEntity()](CreateEntityBatch.CreateEntity().md 'Friflo.Engine.ECS.CreateEntityBatch.CreateEntity()') | Creates an entity with the components and tags previously added.<br/> Added batch components and tags are not cleared. |
| [Get&lt;T&gt;()](CreateEntityBatch.Get_T_().md 'Friflo.Engine.ECS.CreateEntityBatch.Get<T>()') | Get a component by reference previously added to the batch.<br/> This enables creation of multiple entities using the same batch. |
| [Return()](CreateEntityBatch.Return().md 'Friflo.Engine.ECS.CreateEntityBatch.Return()') | Return the batch instance to its [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') to prevent memory allocations for future [Batch(bool)](EntityStoreBase.Batch(bool).md 'Friflo.Engine.ECS.EntityStoreBase.Batch(bool)') calls. |
| [ToString()](CreateEntityBatch.ToString().md 'Friflo.Engine.ECS.CreateEntityBatch.ToString()') | |
