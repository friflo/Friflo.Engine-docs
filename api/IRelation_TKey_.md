#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## IRelation<TKey> Interface

A relation enables adding multiple components of the same type to an entity.<br/>
The components added to a single entity build a set of components using the relation [TKey](IRelation_TKey_.md#Friflo.Engine.ECS.IRelation_TKey_.TKey 'Friflo.Engine.ECS.IRelation<TKey>.TKey') as unique identifier.

```csharp
public interface IRelation<out TKey> :
Friflo.Engine.ECS.IRelation
```
#### Type parameters

<a name='Friflo.Engine.ECS.IRelation_TKey_.TKey'></a>

`TKey`

The key defining a unique relation.

Derived  
&#8627; [ILinkRelation](ILinkRelation.md 'Friflo.Engine.ECS.ILinkRelation')

Implements [IRelation](IRelation.md 'Friflo.Engine.ECS.IRelation')

### Remarks
A relation enables:
- Add multiple relations to an entity using [AddRelation&lt;TRelation&gt;(this Entity, TRelation)](RelationExtensions.AddRelation_TRelation_(thisEntity,TRelation).md 'Friflo.Engine.ECS.RelationExtensions.AddRelation<TRelation>(this Friflo.Engine.ECS.Entity, TRelation)').
- Return all relations of an entity using [GetRelations&lt;TRelation&gt;(this Entity)](RelationExtensions.GetRelations_TRelation_(thisEntity).md 'Friflo.Engine.ECS.RelationExtensions.GetRelations<TRelation>(this Friflo.Engine.ECS.Entity)').
- Return a specific relation by key using  [GetRelation&lt;TRelation,TKey&gt;(this Entity, TKey)](RelationExtensions.GetRelation_TRelation,TKey_(thisEntity,TKey).md 'Friflo.Engine.ECS.RelationExtensions.GetRelation<TRelation,TKey>(this Friflo.Engine.ECS.Entity, TKey)')<br/>
  or [TryGetRelation&lt;TRelation,TKey&gt;(this Entity, TKey, TRelation)](RelationExtensions.TryGetRelation_TRelation,TKey_(thisEntity,TKey,TRelation).md 'Friflo.Engine.ECS.RelationExtensions.TryGetRelation<TRelation,TKey>(this Friflo.Engine.ECS.Entity, TKey, TRelation)').
- Remove a specific relation by key using [RemoveRelation&lt;TRelation,TKey&gt;(this Entity, TKey)](RelationExtensions.RemoveRelation_TRelation,TKey_(thisEntity,TKey).md 'Friflo.Engine.ECS.RelationExtensions.RemoveRelation<TRelation,TKey>(this Friflo.Engine.ECS.Entity, TKey)').

| Methods | |
| :--- | :--- |
| [GetRelationKey()](IRelation_TKey_.GetRelationKey().md 'Friflo.Engine.ECS.IRelation<TKey>.GetRelationKey()') | Returns the key of a unique relation. |
