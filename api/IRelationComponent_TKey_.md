#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## IRelationComponent<TKey> Interface

A relation component enables adding multiple components of the same type to an entity.<br/>
The components added to a single entity build a set of components using the relation [TKey](IRelationComponent_TKey_.md#Friflo.Engine.ECS.IRelationComponent_TKey_.TKey 'Friflo.Engine.ECS.IRelationComponent<TKey>.TKey') as unique identifier.

```csharp
public interface IRelationComponent<out TKey> :
Friflo.Engine.ECS.IRelationComponent,
Friflo.Engine.ECS.IComponent
```
#### Type parameters

<a name='Friflo.Engine.ECS.IRelationComponent_TKey_.TKey'></a>

`TKey`

The key defining a unique relation component.

Derived  
&#8627; [ILinkRelation](ILinkRelation.md 'Friflo.Engine.ECS.ILinkRelation')

Implements [IRelationComponent](IRelationComponent.md 'Friflo.Engine.ECS.IRelationComponent'), [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')

### Remarks
A relation component enables:
- Add multiple relation components to an entity using [AddComponent&lt;T&gt;()](Entity.AddComponent_T_().md 'Friflo.Engine.ECS.Entity.AddComponent<T>()').
- Return all relation components of an entity using [GetRelations&lt;TComponent&gt;(this Entity)](RelationExtensions.GetRelations_TComponent_(thisEntity).md 'Friflo.Engine.ECS.RelationExtensions.GetRelations<TComponent>(this Friflo.Engine.ECS.Entity)').
- Return a specific relation by key using  [GetRelation&lt;TComponent,TKey&gt;(this Entity, TKey)](RelationExtensions.GetRelation_TComponent,TKey_(thisEntity,TKey).md 'Friflo.Engine.ECS.RelationExtensions.GetRelation<TComponent,TKey>(this Friflo.Engine.ECS.Entity, TKey)')<br/>
  or [TryGetRelation&lt;TComponent,TKey&gt;(this Entity, TKey, TComponent)](RelationExtensions.TryGetRelation_TComponent,TKey_(thisEntity,TKey,TComponent).md 'Friflo.Engine.ECS.RelationExtensions.TryGetRelation<TComponent,TKey>(this Friflo.Engine.ECS.Entity, TKey, TComponent)').
- Remove a specific relation component by key using [RemoveRelation&lt;T,TKey&gt;(this Entity, TKey)](RelationExtensions.RemoveRelation_T,TKey_(thisEntity,TKey).md 'Friflo.Engine.ECS.RelationExtensions.RemoveRelation<T,TKey>(this Friflo.Engine.ECS.Entity, TKey)').

| Methods | |
| :--- | :--- |
| [GetRelationKey()](IRelationComponent_TKey_.GetRelationKey().md 'Friflo.Engine.ECS.IRelationComponent<TKey>.GetRelationKey()') | Returns the key of a unique relation component. |
