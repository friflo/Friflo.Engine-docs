#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[RelationExtensions](RelationExtensions.md 'Friflo.Engine.ECS.RelationExtensions')

## RelationExtensions.GetAllEntitiesWithRelations<TComponent>(this EntityStore) Method

Returns a collection of entities having one or more relations of the specified [TComponent](RelationExtensions.GetAllEntitiesWithRelations_TComponent_(thisEntityStore).md#Friflo.Engine.ECS.RelationExtensions.GetAllEntitiesWithRelations_TComponent_(thisFriflo.Engine.ECS.EntityStore).TComponent 'Friflo.Engine.ECS.RelationExtensions.GetAllEntitiesWithRelations<TComponent>(this Friflo.Engine.ECS.EntityStore).TComponent') type.<br/>
Executes in O(1).

```csharp
public static Friflo.Engine.ECS.EntityReadOnlyCollection GetAllEntitiesWithRelations<TComponent>(this Friflo.Engine.ECS.EntityStore store)
    where TComponent : struct, Friflo.Engine.ECS.IRelationComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetAllEntitiesWithRelations_TComponent_(thisFriflo.Engine.ECS.EntityStore).TComponent'></a>

`TComponent`
#### Parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetAllEntitiesWithRelations_TComponent_(thisFriflo.Engine.ECS.EntityStore).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

#### Returns
[EntityReadOnlyCollection](EntityReadOnlyCollection.md 'Friflo.Engine.ECS.EntityReadOnlyCollection')

### Remarks
- The returned collection changes when relations are updated, removed or added.
- To get all entities including their relations (the cartesian product aka CROSS JOIN) use<br/>[GetAllEntityRelations&lt;TComponent&gt;(this EntityStore)](RelationExtensions.GetAllEntityRelations_TComponent_(thisEntityStore).md 'Friflo.Engine.ECS.RelationExtensions.GetAllEntityRelations<TComponent>(this Friflo.Engine.ECS.EntityStore)')