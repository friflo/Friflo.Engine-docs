#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[RelationExtensions](RelationExtensions.md 'Friflo.Engine.ECS.RelationExtensions')

## RelationExtensions.GetAllEntityRelations<TRelation>(this EntityStore) Method

Return all entity relations  of the specified [TRelation](RelationExtensions.GetAllEntityRelations_TRelation_(thisEntityStore).md#Friflo.Engine.ECS.RelationExtensions.GetAllEntityRelations_TRelation_(thisFriflo.Engine.ECS.EntityStore).TRelation 'Friflo.Engine.ECS.RelationExtensions.GetAllEntityRelations<TRelation>(this Friflo.Engine.ECS.EntityStore).TRelation') type.<br/>
Executes in O(1).  Most efficient way to iterate all entity relations.

```csharp
public static (Friflo.Engine.ECS.Entities entities,Friflo.Engine.ECS.Chunk<TRelation> relations) GetAllEntityRelations<TRelation>(this Friflo.Engine.ECS.EntityStore store)
    where TRelation : struct, Friflo.Engine.ECS.IRelation, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetAllEntityRelations_TRelation_(thisFriflo.Engine.ECS.EntityStore).TRelation'></a>

`TRelation`
#### Parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetAllEntityRelations_TRelation_(thisFriflo.Engine.ECS.EntityStore).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

#### Returns
[&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.ValueTuple 'System.ValueTuple')[Entities](Entities.md 'Friflo.Engine.ECS.Entities')[,](https://docs.microsoft.com/en-us/dotnet/api/System.ValueTuple 'System.ValueTuple')[Friflo.Engine.ECS.Chunk&lt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>')[TRelation](RelationExtensions.GetAllEntityRelations_TRelation_(thisEntityStore).md#Friflo.Engine.ECS.RelationExtensions.GetAllEntityRelations_TRelation_(thisFriflo.Engine.ECS.EntityStore).TRelation 'Friflo.Engine.ECS.RelationExtensions.GetAllEntityRelations<TRelation>(this Friflo.Engine.ECS.EntityStore).TRelation')[&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.ValueTuple 'System.ValueTuple')