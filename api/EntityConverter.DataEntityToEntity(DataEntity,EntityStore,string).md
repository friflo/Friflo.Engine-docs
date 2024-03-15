#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Serialize](Friflo.Engine.ECS.Serialize.md 'Friflo.Engine.ECS.Serialize').[EntityConverter](EntityConverter.md 'Friflo.Engine.ECS.Serialize.EntityConverter')

## EntityConverter.DataEntityToEntity(DataEntity, EntityStore, string) Method

Add / update the passed [DataEntity](DataEntity.md 'Friflo.Engine.ECS.Serialize.DataEntity') in the given [store](EntityConverter.DataEntityToEntity(DataEntity,EntityStore,string).md#Friflo.Engine.ECS.Serialize.EntityConverter.DataEntityToEntity(Friflo.Engine.ECS.Serialize.DataEntity,Friflo.Engine.ECS.EntityStore,string).store 'Friflo.Engine.ECS.Serialize.EntityConverter.DataEntityToEntity(Friflo.Engine.ECS.Serialize.DataEntity, Friflo.Engine.ECS.EntityStore, string).store') and returns
the added / updated [Entity](Entity.md 'Friflo.Engine.ECS.Entity').

```csharp
public Friflo.Engine.ECS.Entity DataEntityToEntity(Friflo.Engine.ECS.Serialize.DataEntity dataEntity, Friflo.Engine.ECS.EntityStore store, out string error);
```
#### Parameters

<a name='Friflo.Engine.ECS.Serialize.EntityConverter.DataEntityToEntity(Friflo.Engine.ECS.Serialize.DataEntity,Friflo.Engine.ECS.EntityStore,string).dataEntity'></a>

`dataEntity` [DataEntity](DataEntity.md 'Friflo.Engine.ECS.Serialize.DataEntity')

<a name='Friflo.Engine.ECS.Serialize.EntityConverter.DataEntityToEntity(Friflo.Engine.ECS.Serialize.DataEntity,Friflo.Engine.ECS.EntityStore,string).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

<a name='Friflo.Engine.ECS.Serialize.EntityConverter.DataEntityToEntity(Friflo.Engine.ECS.Serialize.DataEntity,Friflo.Engine.ECS.EntityStore,string).error'></a>

`error` [System.String](https://docs.microsoft.com/en-us/dotnet/api/System.String 'System.String')

#### Returns
[Entity](Entity.md 'Friflo.Engine.ECS.Entity')