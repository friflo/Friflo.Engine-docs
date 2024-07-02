#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[RelationExtensions](RelationExtensions.md 'Friflo.Engine.ECS.RelationExtensions')

## RelationExtensions.ForAllEntityRelations<TComponent>(this EntityStore, ForEachEntity<TComponent>) Method

Iterates all entity relations of the specified [TComponent](RelationExtensions.ForAllEntityRelations_TComponent_(thisEntityStore,ForEachEntity_TComponent_).md#Friflo.Engine.ECS.RelationExtensions.ForAllEntityRelations_TComponent_(thisFriflo.Engine.ECS.EntityStore,Friflo.Engine.ECS.ForEachEntity_TComponent_).TComponent 'Friflo.Engine.ECS.RelationExtensions.ForAllEntityRelations<TComponent>(this Friflo.Engine.ECS.EntityStore, Friflo.Engine.ECS.ForEachEntity<TComponent>).TComponent') type.<br/>
Executes in O(N) N: number of all entity relations.

```csharp
public static void ForAllEntityRelations<TComponent>(this Friflo.Engine.ECS.EntityStore store, Friflo.Engine.ECS.ForEachEntity<TComponent> lambda)
    where TComponent : struct, Friflo.Engine.ECS.IRelationComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.RelationExtensions.ForAllEntityRelations_TComponent_(thisFriflo.Engine.ECS.EntityStore,Friflo.Engine.ECS.ForEachEntity_TComponent_).TComponent'></a>

`TComponent`
#### Parameters

<a name='Friflo.Engine.ECS.RelationExtensions.ForAllEntityRelations_TComponent_(thisFriflo.Engine.ECS.EntityStore,Friflo.Engine.ECS.ForEachEntity_TComponent_).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

<a name='Friflo.Engine.ECS.RelationExtensions.ForAllEntityRelations_TComponent_(thisFriflo.Engine.ECS.EntityStore,Friflo.Engine.ECS.ForEachEntity_TComponent_).lambda'></a>

`lambda` [Friflo.Engine.ECS.ForEachEntity&lt;](ForEachEntity_T1_(T1,Entity).md 'Friflo.Engine.ECS.ForEachEntity<T1>(T1, Friflo.Engine.ECS.Entity)')[TComponent](RelationExtensions.ForAllEntityRelations_TComponent_(thisEntityStore,ForEachEntity_TComponent_).md#Friflo.Engine.ECS.RelationExtensions.ForAllEntityRelations_TComponent_(thisFriflo.Engine.ECS.EntityStore,Friflo.Engine.ECS.ForEachEntity_TComponent_).TComponent 'Friflo.Engine.ECS.RelationExtensions.ForAllEntityRelations<TComponent>(this Friflo.Engine.ECS.EntityStore, Friflo.Engine.ECS.ForEachEntity<TComponent>).TComponent')[&gt;](ForEachEntity_T1_(T1,Entity).md 'Friflo.Engine.ECS.ForEachEntity<T1>(T1, Friflo.Engine.ECS.Entity)')