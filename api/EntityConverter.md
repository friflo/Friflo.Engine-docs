#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Serialize](Friflo.Engine.ECS.Serialize.md 'Friflo.Engine.ECS.Serialize')

## EntityConverter Class

Converts an [Entity](Entity.md 'Friflo.Engine.ECS.Entity') to a [DataEntity](DataEntity.md 'Friflo.Engine.ECS.Serialize.DataEntity') and vice versa.

```csharp
public sealed class EntityConverter
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; EntityConverter

| Fields | |
| :--- | :--- |
| [Default](EntityConverter.Default.md 'Friflo.Engine.ECS.Serialize.EntityConverter.Default') | An [EntityConverter](EntityConverter.md 'Friflo.Engine.ECS.Serialize.EntityConverter') singleton. Must be used only from the main thread. |

| Methods | |
| :--- | :--- |
| [DataEntityToEntity(DataEntity, EntityStore, string)](EntityConverter.DataEntityToEntity(DataEntity,EntityStore,string).md 'Friflo.Engine.ECS.Serialize.EntityConverter.DataEntityToEntity(Friflo.Engine.ECS.Serialize.DataEntity, Friflo.Engine.ECS.EntityStore, string)') | Add / update the passed [DataEntity](DataEntity.md 'Friflo.Engine.ECS.Serialize.DataEntity') in the given [store](EntityConverter.DataEntityToEntity(DataEntity,EntityStore,string).md#Friflo.Engine.ECS.Serialize.EntityConverter.DataEntityToEntity(Friflo.Engine.ECS.Serialize.DataEntity,Friflo.Engine.ECS.EntityStore,string).store 'Friflo.Engine.ECS.Serialize.EntityConverter.DataEntityToEntity(Friflo.Engine.ECS.Serialize.DataEntity, Friflo.Engine.ECS.EntityStore, string).store') and returns the added / updated [Entity](Entity.md 'Friflo.Engine.ECS.Entity'). |
| [EntityToDataEntity(Entity, DataEntity, bool)](EntityConverter.EntityToDataEntity(Entity,DataEntity,bool).md 'Friflo.Engine.ECS.Serialize.EntityConverter.EntityToDataEntity(Friflo.Engine.ECS.Entity, Friflo.Engine.ECS.Serialize.DataEntity, bool)') | Returns the passed [Entity](Entity.md 'Friflo.Engine.ECS.Entity') as a [DataEntity](DataEntity.md 'Friflo.Engine.ECS.Serialize.DataEntity') |
