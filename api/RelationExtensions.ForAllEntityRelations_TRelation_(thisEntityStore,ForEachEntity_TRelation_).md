#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[RelationExtensions](RelationExtensions.md 'Friflo.Engine.ECS.RelationExtensions')

## RelationExtensions.ForAllEntityRelations<TRelation>(this EntityStore, ForEachEntity<TRelation>) Method

Obsolete: Use [For(ForEachEntity&lt;TRelation&gt;)](EntityRelations_TRelation_.For(ForEachEntity_TRelation_).md 'Friflo.Engine.ECS.EntityRelations<TRelation>.For(Friflo.Engine.ECS.ForEachEntity<TRelation>)')<br/>
Iterates all entity relations of the specified [TRelation](RelationExtensions.ForAllEntityRelations_TRelation_(thisEntityStore,ForEachEntity_TRelation_).md#Friflo.Engine.ECS.RelationExtensions.ForAllEntityRelations_TRelation_(thisFriflo.Engine.ECS.EntityStore,Friflo.Engine.ECS.ForEachEntity_TRelation_).TRelation 'Friflo.Engine.ECS.RelationExtensions.ForAllEntityRelations<TRelation>(this Friflo.Engine.ECS.EntityStore, Friflo.Engine.ECS.ForEachEntity<TRelation>).TRelation') type.<br/>
Executes in O(N) N: number of all entity relations.

```csharp
public static void ForAllEntityRelations<TRelation>(this Friflo.Engine.ECS.EntityStore store, Friflo.Engine.ECS.ForEachEntity<TRelation> lambda)
    where TRelation : struct, Friflo.Engine.ECS.IRelation, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.RelationExtensions.ForAllEntityRelations_TRelation_(thisFriflo.Engine.ECS.EntityStore,Friflo.Engine.ECS.ForEachEntity_TRelation_).TRelation'></a>

`TRelation`
#### Parameters

<a name='Friflo.Engine.ECS.RelationExtensions.ForAllEntityRelations_TRelation_(thisFriflo.Engine.ECS.EntityStore,Friflo.Engine.ECS.ForEachEntity_TRelation_).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

<a name='Friflo.Engine.ECS.RelationExtensions.ForAllEntityRelations_TRelation_(thisFriflo.Engine.ECS.EntityStore,Friflo.Engine.ECS.ForEachEntity_TRelation_).lambda'></a>

`lambda` [Friflo.Engine.ECS.ForEachEntity&lt;](ForEachEntity_T1_(T1,Entity).md 'Friflo.Engine.ECS.ForEachEntity<T1>(T1, Friflo.Engine.ECS.Entity)')[TRelation](RelationExtensions.ForAllEntityRelations_TRelation_(thisEntityStore,ForEachEntity_TRelation_).md#Friflo.Engine.ECS.RelationExtensions.ForAllEntityRelations_TRelation_(thisFriflo.Engine.ECS.EntityStore,Friflo.Engine.ECS.ForEachEntity_TRelation_).TRelation 'Friflo.Engine.ECS.RelationExtensions.ForAllEntityRelations<TRelation>(this Friflo.Engine.ECS.EntityStore, Friflo.Engine.ECS.ForEachEntity<TRelation>).TRelation')[&gt;](ForEachEntity_T1_(T1,Entity).md 'Friflo.Engine.ECS.ForEachEntity<T1>(T1, Friflo.Engine.ECS.Entity)')