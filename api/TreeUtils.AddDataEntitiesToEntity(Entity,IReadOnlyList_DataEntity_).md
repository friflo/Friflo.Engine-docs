#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS.Utils](Friflo.Engine.ECS.Utils.md#'Friflo.Engine.ECS.Utils').[TreeUtils](TreeUtils.md#'Friflo.Engine.ECS.Utils.TreeUtils')

## TreeUtils.AddDataEntitiesToEntity(Entity, IReadOnlyList<DataEntity>) Method

Add the given [dataEntities](TreeUtils.AddDataEntitiesToEntity(Entity,IReadOnlyList_DataEntity_).md#Friflo.Engine.ECS.Utils.TreeUtils.AddDataEntitiesToEntity(Friflo.Engine.ECS.Entity,System.Collections.Generic.IReadOnlyList_Friflo.Engine.ECS.Serialize.DataEntity_).dataEntities#'Friflo.Engine.ECS.Utils.TreeUtils.AddDataEntitiesToEntity(Friflo.Engine.ECS.Entity, System.Collections.Generic.IReadOnlyList<Friflo.Engine.ECS.Serialize.DataEntity>).dataEntities') to the specified [targetEntity](TreeUtils.AddDataEntitiesToEntity(Entity,IReadOnlyList_DataEntity_).md#Friflo.Engine.ECS.Utils.TreeUtils.AddDataEntitiesToEntity(Friflo.Engine.ECS.Entity,System.Collections.Generic.IReadOnlyList_Friflo.Engine.ECS.Serialize.DataEntity_).targetEntity#'Friflo.Engine.ECS.Utils.TreeUtils.AddDataEntitiesToEntity(Friflo.Engine.ECS.Entity, System.Collections.Generic.IReadOnlyList<Friflo.Engine.ECS.Serialize.DataEntity>).targetEntity').<br/>
The [pid](DataEntity.pid.md#'Friflo.Engine.ECS.Serialize.DataEntity.pid') and the [children](DataEntity.children.md#'Friflo.Engine.ECS.Serialize.DataEntity.children') of the given [dataEntities](TreeUtils.AddDataEntitiesToEntity(Entity,IReadOnlyList_DataEntity_).md#Friflo.Engine.ECS.Utils.TreeUtils.AddDataEntitiesToEntity(Friflo.Engine.ECS.Entity,System.Collections.Generic.IReadOnlyList_Friflo.Engine.ECS.Serialize.DataEntity_).dataEntities#'Friflo.Engine.ECS.Utils.TreeUtils.AddDataEntitiesToEntity(Friflo.Engine.ECS.Entity, System.Collections.Generic.IReadOnlyList<Friflo.Engine.ECS.Serialize.DataEntity>).dataEntities') 
are replaced with the pids of the newly created [Entity](Entity.md#'Friflo.Engine.ECS.Entity')'s.

```csharp
public static Friflo.Engine.ECS.Utils.AddDataEntitiesResult AddDataEntitiesToEntity(Friflo.Engine.ECS.Entity targetEntity, System.Collections.Generic.IReadOnlyList<Friflo.Engine.ECS.Serialize.DataEntity> dataEntities);
```
#### Parameters

<a name='Friflo.Engine.ECS.Utils.TreeUtils.AddDataEntitiesToEntity(Friflo.Engine.ECS.Entity,System.Collections.Generic.IReadOnlyList_Friflo.Engine.ECS.Serialize.DataEntity_).targetEntity'></a>

`targetEntity` [Entity](Entity.md#'Friflo.Engine.ECS.Entity')

<a name='Friflo.Engine.ECS.Utils.TreeUtils.AddDataEntitiesToEntity(Friflo.Engine.ECS.Entity,System.Collections.Generic.IReadOnlyList_Friflo.Engine.ECS.Serialize.DataEntity_).dataEntities'></a>

`dataEntities` [System.Collections.Generic.IReadOnlyList&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyList-1#'System.Collections.Generic.IReadOnlyList`1')[DataEntity](DataEntity.md#'Friflo.Engine.ECS.Serialize.DataEntity')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyList-1#'System.Collections.Generic.IReadOnlyList`1')

#### Returns
[AddDataEntitiesResult](AddDataEntitiesResult.md#'Friflo.Engine.ECS.Utils.AddDataEntitiesResult')

### Remarks
The order of items in [dataEntities](TreeUtils.AddDataEntitiesToEntity(Entity,IReadOnlyList_DataEntity_).md#Friflo.Engine.ECS.Utils.TreeUtils.AddDataEntitiesToEntity(Friflo.Engine.ECS.Entity,System.Collections.Generic.IReadOnlyList_Friflo.Engine.ECS.Serialize.DataEntity_).dataEntities#'Friflo.Engine.ECS.Utils.TreeUtils.AddDataEntitiesToEntity(Friflo.Engine.ECS.Entity, System.Collections.Generic.IReadOnlyList<Friflo.Engine.ECS.Serialize.DataEntity>).dataEntities') is not relevant.