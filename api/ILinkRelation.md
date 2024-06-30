#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ILinkRelation Interface

A link relation is a component type used to create multiple links from one entity to other entities.

```csharp
public interface ILinkRelation :
Friflo.Engine.ECS.IRelationComponent<Friflo.Engine.ECS.Entity>,
Friflo.Engine.ECS.IRelationComponent,
Friflo.Engine.ECS.IComponent
```

Implements [Friflo.Engine.ECS.IRelationComponent&lt;](IRelationComponent_TKey_.md 'Friflo.Engine.ECS.IRelationComponent<TKey>')[Entity](Entity.md 'Friflo.Engine.ECS.Entity')[&gt;](IRelationComponent_TKey_.md 'Friflo.Engine.ECS.IRelationComponent<TKey>'), [IRelationComponent](IRelationComponent.md 'Friflo.Engine.ECS.IRelationComponent'), [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')

### Remarks
A link relation enables:
- Add multiple link relations to an entity using [AddComponent&lt;T&gt;()](Entity.AddComponent_T_().md 'Friflo.Engine.ECS.Entity.AddComponent<T>()').
- Return all links of an entity to other entities using [GetRelations&lt;TComponent&gt;(this Entity)](RelationExtensions.GetRelations_TComponent_(thisEntity).md 'Friflo.Engine.ECS.RelationExtensions.GetRelations<TComponent>(this Friflo.Engine.ECS.Entity)').
- Remove a specific link to another entity with [RemoveLinkRelation&lt;T&gt;(this Entity, Entity)](RelationExtensions.RemoveLinkRelation_T_(thisEntity,Entity).md 'Friflo.Engine.ECS.RelationExtensions.RemoveLinkRelation<T>(this Friflo.Engine.ECS.Entity, Friflo.Engine.ECS.Entity)').