#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## EntityRelations<TRelation> Struct

Storage for all entity relations of the specified [TRelation](EntityRelations_TRelation_.md#Friflo.Engine.ECS.EntityRelations_TRelation_.TRelation 'Friflo.Engine.ECS.EntityRelations<TRelation>.TRelation') type.<br/>
An instance is returned via [EntityRelations&lt;TRelation&gt;(this EntityStore)](RelationExtensions.EntityRelations_TRelation_(thisEntityStore).md 'Friflo.Engine.ECS.RelationExtensions.EntityRelations<TRelation>(this Friflo.Engine.ECS.EntityStore)').

```csharp
public readonly struct EntityRelations<TRelation>
    where TRelation : struct, Friflo.Engine.ECS.IRelation, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityRelations_TRelation_.TRelation'></a>

`TRelation`

| Properties | |
| :--- | :--- |
| [Entities](EntityRelations_TRelation_.Entities.md 'Friflo.Engine.ECS.EntityRelations<TRelation>.Entities') | Returns a collection of entities having one or more relation.<br/> Executes in O(1). |
| [Pairs](EntityRelations_TRelation_.Pairs.md 'Friflo.Engine.ECS.EntityRelations<TRelation>.Pairs') | Return all entity relations as pairs. A pair is `(entities[i], relations[i])`<br/> Executes in O(1).  Most efficient way to iterate all entity relations. |

| Methods | |
| :--- | :--- |
| [For(ForEachEntity&lt;TRelation&gt;)](EntityRelations_TRelation_.For(ForEachEntity_TRelation_).md 'Friflo.Engine.ECS.EntityRelations<TRelation>.For(Friflo.Engine.ECS.ForEachEntity<TRelation>)') | Iterates all entity relations.<br/> Executes in O(N) N: number of all entity relations. |
