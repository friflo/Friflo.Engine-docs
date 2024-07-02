#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[RelationExtensions](RelationExtensions.md 'Friflo.Engine.ECS.RelationExtensions')

## RelationExtensions.GetAllEntityRelations<TComponent>(this EntityStore) Method

Return all entity relations  of the specified [TComponent](RelationExtensions.GetAllEntityRelations_TComponent_(thisEntityStore).md#Friflo.Engine.ECS.RelationExtensions.GetAllEntityRelations_TComponent_(thisFriflo.Engine.ECS.EntityStore).TComponent 'Friflo.Engine.ECS.RelationExtensions.GetAllEntityRelations<TComponent>(this Friflo.Engine.ECS.EntityStore).TComponent') type.<br/>
Executes in O(1).  Most efficient way to iterate all entity relations.

```csharp
public static (Friflo.Engine.ECS.Entities entities,Friflo.Engine.ECS.Chunk<TComponent> relations) GetAllEntityRelations<TComponent>(this Friflo.Engine.ECS.EntityStore store)
    where TComponent : struct, Friflo.Engine.ECS.IRelationComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetAllEntityRelations_TComponent_(thisFriflo.Engine.ECS.EntityStore).TComponent'></a>

`TComponent`
#### Parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetAllEntityRelations_TComponent_(thisFriflo.Engine.ECS.EntityStore).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

#### Returns
[&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.ValueTuple 'System.ValueTuple')[Entities](Entities.md 'Friflo.Engine.ECS.Entities')[,](https://docs.microsoft.com/en-us/dotnet/api/System.ValueTuple 'System.ValueTuple')[Friflo.Engine.ECS.Chunk&lt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>')[TComponent](RelationExtensions.GetAllEntityRelations_TComponent_(thisEntityStore).md#Friflo.Engine.ECS.RelationExtensions.GetAllEntityRelations_TComponent_(thisFriflo.Engine.ECS.EntityStore).TComponent 'Friflo.Engine.ECS.RelationExtensions.GetAllEntityRelations<TComponent>(this Friflo.Engine.ECS.EntityStore).TComponent')[&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.ValueTuple 'System.ValueTuple')