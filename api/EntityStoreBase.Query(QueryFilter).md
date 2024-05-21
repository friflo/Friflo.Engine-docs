#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStoreBase](EntityStoreBase.md 'Friflo.Engine.ECS.EntityStoreBase')

## EntityStoreBase.Query(QueryFilter) Method

Create a reusable [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') with given query [filter](EntityStoreBase.Query(QueryFilter).md#Friflo.Engine.ECS.EntityStoreBase.Query(Friflo.Engine.ECS.QueryFilter).filter 'Friflo.Engine.ECS.EntityStoreBase.Query(Friflo.Engine.ECS.QueryFilter).filter').<br/>
The filter attached to the query can be modified subsequently.

```csharp
public Friflo.Engine.ECS.ArchetypeQuery Query(Friflo.Engine.ECS.QueryFilter filter);
```
#### Parameters

<a name='Friflo.Engine.ECS.EntityStoreBase.Query(Friflo.Engine.ECS.QueryFilter).filter'></a>

`filter` [QueryFilter](QueryFilter.md 'Friflo.Engine.ECS.QueryFilter')

#### Returns
[ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery')