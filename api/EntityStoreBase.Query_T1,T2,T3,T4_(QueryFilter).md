#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStoreBase](EntityStoreBase.md 'Friflo.Engine.ECS.EntityStoreBase')

## EntityStoreBase.Query<T1,T2,T3,T4>(QueryFilter) Method

Create a reusable [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') with given query [filter](EntityStoreBase.Query_T1,T2,T3,T4_(QueryFilter).md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3,T4_(Friflo.Engine.ECS.QueryFilter).filter 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3,T4>(Friflo.Engine.ECS.QueryFilter).filter').<br/>
The filter attached to the query can be modified subsequently.

```csharp
public Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4> Query<T1,T2,T3,T4>(Friflo.Engine.ECS.QueryFilter filter)
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T4 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3,T4_(Friflo.Engine.ECS.QueryFilter).T1'></a>

`T1`

<a name='Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3,T4_(Friflo.Engine.ECS.QueryFilter).T2'></a>

`T2`

<a name='Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3,T4_(Friflo.Engine.ECS.QueryFilter).T3'></a>

`T3`

<a name='Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3,T4_(Friflo.Engine.ECS.QueryFilter).T4'></a>

`T4`
#### Parameters

<a name='Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3,T4_(Friflo.Engine.ECS.QueryFilter).filter'></a>

`filter` [QueryFilter](QueryFilter.md 'Friflo.Engine.ECS.QueryFilter')

#### Returns
[Friflo.Engine.ECS.ArchetypeQuery&lt;](ArchetypeQuery_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>')[T1](EntityStoreBase.Query_T1,T2,T3,T4_(QueryFilter).md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3,T4_(Friflo.Engine.ECS.QueryFilter).T1 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3,T4>(Friflo.Engine.ECS.QueryFilter).T1')[,](ArchetypeQuery_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>')[T2](EntityStoreBase.Query_T1,T2,T3,T4_(QueryFilter).md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3,T4_(Friflo.Engine.ECS.QueryFilter).T2 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3,T4>(Friflo.Engine.ECS.QueryFilter).T2')[,](ArchetypeQuery_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>')[T3](EntityStoreBase.Query_T1,T2,T3,T4_(QueryFilter).md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3,T4_(Friflo.Engine.ECS.QueryFilter).T3 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3,T4>(Friflo.Engine.ECS.QueryFilter).T3')[,](ArchetypeQuery_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>')[T4](EntityStoreBase.Query_T1,T2,T3,T4_(QueryFilter).md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3,T4_(Friflo.Engine.ECS.QueryFilter).T4 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3,T4>(Friflo.Engine.ECS.QueryFilter).T4')[&gt;](ArchetypeQuery_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>')