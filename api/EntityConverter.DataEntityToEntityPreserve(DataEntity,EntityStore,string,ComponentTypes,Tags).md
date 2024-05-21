#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Serialize](Friflo.Engine.ECS.Serialize.md 'Friflo.Engine.ECS.Serialize').[EntityConverter](EntityConverter.md 'Friflo.Engine.ECS.Serialize.EntityConverter')

## EntityConverter.DataEntityToEntityPreserve(DataEntity, EntityStore, string, ComponentTypes, Tags) Method

Add / update the passed [DataEntity](DataEntity.md 'Friflo.Engine.ECS.Serialize.DataEntity') in the given [store](EntityConverter.DataEntityToEntityPreserve(DataEntity,EntityStore,string,ComponentTypes,Tags).md#Friflo.Engine.ECS.Serialize.EntityConverter.DataEntityToEntityPreserve(Friflo.Engine.ECS.Serialize.DataEntity,Friflo.Engine.ECS.EntityStore,string,Friflo.Engine.ECS.ComponentTypes,Friflo.Engine.ECS.Tags).store 'Friflo.Engine.ECS.Serialize.EntityConverter.DataEntityToEntityPreserve(Friflo.Engine.ECS.Serialize.DataEntity, Friflo.Engine.ECS.EntityStore, string, Friflo.Engine.ECS.ComponentTypes, Friflo.Engine.ECS.Tags).store') and returns
the added / updated [Entity](Entity.md 'Friflo.Engine.ECS.Entity').<br/>
The specified [componentTypes](EntityConverter.DataEntityToEntityPreserve(DataEntity,EntityStore,string,ComponentTypes,Tags).md#Friflo.Engine.ECS.Serialize.EntityConverter.DataEntityToEntityPreserve(Friflo.Engine.ECS.Serialize.DataEntity,Friflo.Engine.ECS.EntityStore,string,Friflo.Engine.ECS.ComponentTypes,Friflo.Engine.ECS.Tags).componentTypes 'Friflo.Engine.ECS.Serialize.EntityConverter.DataEntityToEntityPreserve(Friflo.Engine.ECS.Serialize.DataEntity, Friflo.Engine.ECS.EntityStore, string, Friflo.Engine.ECS.ComponentTypes, Friflo.Engine.ECS.Tags).componentTypes') and [tags](EntityConverter.DataEntityToEntityPreserve(DataEntity,EntityStore,string,ComponentTypes,Tags).md#Friflo.Engine.ECS.Serialize.EntityConverter.DataEntityToEntityPreserve(Friflo.Engine.ECS.Serialize.DataEntity,Friflo.Engine.ECS.EntityStore,string,Friflo.Engine.ECS.ComponentTypes,Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.Serialize.EntityConverter.DataEntityToEntityPreserve(Friflo.Engine.ECS.Serialize.DataEntity, Friflo.Engine.ECS.EntityStore, string, Friflo.Engine.ECS.ComponentTypes, Friflo.Engine.ECS.Tags).tags') are preserved if present on entity.

```csharp
public Friflo.Engine.ECS.Entity DataEntityToEntityPreserve(Friflo.Engine.ECS.Serialize.DataEntity dataEntity, Friflo.Engine.ECS.EntityStore store, out string error, in Friflo.Engine.ECS.ComponentTypes componentTypes, in Friflo.Engine.ECS.Tags tags);
```
#### Parameters

<a name='Friflo.Engine.ECS.Serialize.EntityConverter.DataEntityToEntityPreserve(Friflo.Engine.ECS.Serialize.DataEntity,Friflo.Engine.ECS.EntityStore,string,Friflo.Engine.ECS.ComponentTypes,Friflo.Engine.ECS.Tags).dataEntity'></a>

`dataEntity` [DataEntity](DataEntity.md 'Friflo.Engine.ECS.Serialize.DataEntity')

<a name='Friflo.Engine.ECS.Serialize.EntityConverter.DataEntityToEntityPreserve(Friflo.Engine.ECS.Serialize.DataEntity,Friflo.Engine.ECS.EntityStore,string,Friflo.Engine.ECS.ComponentTypes,Friflo.Engine.ECS.Tags).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

<a name='Friflo.Engine.ECS.Serialize.EntityConverter.DataEntityToEntityPreserve(Friflo.Engine.ECS.Serialize.DataEntity,Friflo.Engine.ECS.EntityStore,string,Friflo.Engine.ECS.ComponentTypes,Friflo.Engine.ECS.Tags).error'></a>

`error` [System.String](https://docs.microsoft.com/en-us/dotnet/api/System.String 'System.String')

<a name='Friflo.Engine.ECS.Serialize.EntityConverter.DataEntityToEntityPreserve(Friflo.Engine.ECS.Serialize.DataEntity,Friflo.Engine.ECS.EntityStore,string,Friflo.Engine.ECS.ComponentTypes,Friflo.Engine.ECS.Tags).componentTypes'></a>

`componentTypes` [ComponentTypes](ComponentTypes.md 'Friflo.Engine.ECS.ComponentTypes')

<a name='Friflo.Engine.ECS.Serialize.EntityConverter.DataEntityToEntityPreserve(Friflo.Engine.ECS.Serialize.DataEntity,Friflo.Engine.ECS.EntityStore,string,Friflo.Engine.ECS.ComponentTypes,Friflo.Engine.ECS.Tags).tags'></a>

`tags` [Tags](Tags.md 'Friflo.Engine.ECS.Tags')

#### Returns
[Entity](Entity.md 'Friflo.Engine.ECS.Entity')