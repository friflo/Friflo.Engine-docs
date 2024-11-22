#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStoreBase](EntityStoreBase.md 'Friflo.Engine.ECS.EntityStoreBase')

## EntityStoreBase.QueryRelation<T1>(QueryFilter) Method

Create a reusable [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') with given query [filter](EntityStoreBase.QueryRelation_T1_(QueryFilter).md#Friflo.Engine.ECS.EntityStoreBase.QueryRelation_T1_(Friflo.Engine.ECS.QueryFilter).filter 'Friflo.Engine.ECS.EntityStoreBase.QueryRelation<T1>(Friflo.Engine.ECS.QueryFilter).filter').<br/>
The filter attached to the query can be modified subsequently.

```csharp
public Friflo.Engine.ECS.ArchetypeQuery<T1> QueryRelation<T1>(Friflo.Engine.ECS.QueryFilter filter)
    where T1 : struct, Friflo.Engine.ECS.IRelation, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityStoreBase.QueryRelation_T1_(Friflo.Engine.ECS.QueryFilter).T1'></a>

`T1`
#### Parameters

<a name='Friflo.Engine.ECS.EntityStoreBase.QueryRelation_T1_(Friflo.Engine.ECS.QueryFilter).filter'></a>

`filter` [QueryFilter](QueryFilter.md 'Friflo.Engine.ECS.QueryFilter')

#### Returns
[Friflo.Engine.ECS.ArchetypeQuery&lt;](ArchetypeQuery_T1_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1>')[T1](EntityStoreBase.QueryRelation_T1_(QueryFilter).md#Friflo.Engine.ECS.EntityStoreBase.QueryRelation_T1_(Friflo.Engine.ECS.QueryFilter).T1 'Friflo.Engine.ECS.EntityStoreBase.QueryRelation<T1>(Friflo.Engine.ECS.QueryFilter).T1')[&gt;](ArchetypeQuery_T1_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1>')