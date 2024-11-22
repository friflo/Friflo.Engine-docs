#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[RelationExtensions](RelationExtensions.md 'Friflo.Engine.ECS.RelationExtensions')

## RelationExtensions.GetAllEntitiesWithRelations<TRelation>(this EntityStore) Method

Returns a collection of entities having one or more relations of the specified [TRelation](RelationExtensions.GetAllEntitiesWithRelations_TRelation_(thisEntityStore).md#Friflo.Engine.ECS.RelationExtensions.GetAllEntitiesWithRelations_TRelation_(thisFriflo.Engine.ECS.EntityStore).TRelation 'Friflo.Engine.ECS.RelationExtensions.GetAllEntitiesWithRelations<TRelation>(this Friflo.Engine.ECS.EntityStore).TRelation') type.<br/>
Executes in O(1).

```csharp
public static Friflo.Engine.ECS.EntityReadOnlyCollection GetAllEntitiesWithRelations<TRelation>(this Friflo.Engine.ECS.EntityStore store)
    where TRelation : struct, Friflo.Engine.ECS.IRelation, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetAllEntitiesWithRelations_TRelation_(thisFriflo.Engine.ECS.EntityStore).TRelation'></a>

`TRelation`
#### Parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetAllEntitiesWithRelations_TRelation_(thisFriflo.Engine.ECS.EntityStore).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

#### Returns
[EntityReadOnlyCollection](EntityReadOnlyCollection.md 'Friflo.Engine.ECS.EntityReadOnlyCollection')

### Remarks
- The returned collection changes when relations are updated, removed or added.
- To get all entities including their relations (the cartesian product aka CROSS JOIN) use<br/>[GetAllEntityRelations&lt;TRelation&gt;(this EntityStore)](RelationExtensions.GetAllEntityRelations_TRelation_(thisEntityStore).md 'Friflo.Engine.ECS.RelationExtensions.GetAllEntityRelations<TRelation>(this Friflo.Engine.ECS.EntityStore)')