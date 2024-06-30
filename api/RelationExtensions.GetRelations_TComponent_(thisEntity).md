#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[RelationExtensions](RelationExtensions.md 'Friflo.Engine.ECS.RelationExtensions')

## RelationExtensions.GetRelations<TComponent>(this Entity) Method

Returns all unique relation components of the passed [entity](RelationExtensions.GetRelations_TComponent_(thisEntity).md#Friflo.Engine.ECS.RelationExtensions.GetRelations_TComponent_(thisFriflo.Engine.ECS.Entity).entity 'Friflo.Engine.ECS.RelationExtensions.GetRelations<TComponent>(this Friflo.Engine.ECS.Entity).entity').<br/>
Executes in O(1). In case [TComponent](RelationExtensions.GetRelations_TComponent_(thisEntity).md#Friflo.Engine.ECS.RelationExtensions.GetRelations_TComponent_(thisFriflo.Engine.ECS.Entity).TComponent 'Friflo.Engine.ECS.RelationExtensions.GetRelations<TComponent>(this Friflo.Engine.ECS.Entity).TComponent') is a [ILinkRelation](ILinkRelation.md 'Friflo.Engine.ECS.ILinkRelation') it returns all linked entities.

```csharp
public static Friflo.Engine.ECS.RelationComponents<TComponent> GetRelations<TComponent>(this Friflo.Engine.ECS.Entity entity)
    where TComponent : struct, Friflo.Engine.ECS.IRelationComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetRelations_TComponent_(thisFriflo.Engine.ECS.Entity).TComponent'></a>

`TComponent`
#### Parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetRelations_TComponent_(thisFriflo.Engine.ECS.Entity).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

#### Returns
[Friflo.Engine.ECS.RelationComponents&lt;](RelationComponents_TComponent_.md 'Friflo.Engine.ECS.RelationComponents<TComponent>')[TComponent](RelationExtensions.GetRelations_TComponent_(thisEntity).md#Friflo.Engine.ECS.RelationExtensions.GetRelations_TComponent_(thisFriflo.Engine.ECS.Entity).TComponent 'Friflo.Engine.ECS.RelationExtensions.GetRelations<TComponent>(this Friflo.Engine.ECS.Entity).TComponent')[&gt;](RelationComponents_TComponent_.md 'Friflo.Engine.ECS.RelationComponents<TComponent>')