#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ILinkRelation Interface

A link relation is a component type used to create multiple links from one entity to other entities.

```csharp
public interface ILinkRelation :
Friflo.Engine.ECS.IRelation<Friflo.Engine.ECS.Entity>,
Friflo.Engine.ECS.IRelation
```

Implements [Friflo.Engine.ECS.IRelation&lt;](IRelation_TKey_.md 'Friflo.Engine.ECS.IRelation<TKey>')[Entity](Entity.md 'Friflo.Engine.ECS.Entity')[&gt;](IRelation_TKey_.md 'Friflo.Engine.ECS.IRelation<TKey>'), [IRelation](IRelation.md 'Friflo.Engine.ECS.IRelation')

### Remarks
A link relation enables:
- Add multiple link relations to an entity using [AddComponent&lt;T&gt;()](Entity.AddComponent_T_().md 'Friflo.Engine.ECS.Entity.AddComponent<T>()').
- Return all links of an entity to other entities using [GetRelations&lt;TRelation&gt;(this Entity)](RelationExtensions.GetRelations_TRelation_(thisEntity).md 'Friflo.Engine.ECS.RelationExtensions.GetRelations<TRelation>(this Friflo.Engine.ECS.Entity)').
- Remove a specific link to another entity with [RemoveRelation&lt;TRelation&gt;(this Entity, Entity)](RelationExtensions.RemoveRelation_TRelation_(thisEntity,Entity).md 'Friflo.Engine.ECS.RelationExtensions.RemoveRelation<TRelation>(this Friflo.Engine.ECS.Entity, Friflo.Engine.ECS.Entity)').