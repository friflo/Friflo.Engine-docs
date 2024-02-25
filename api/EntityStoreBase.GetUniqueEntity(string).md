#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStoreBase](EntityStoreBase.md 'Friflo.Engine.ECS.EntityStoreBase')

## EntityStoreBase.GetUniqueEntity(string) Method

Return the entity with a [UniqueEntity](UniqueEntity.md 'Friflo.Engine.ECS.UniqueEntity') component and its [uid](UniqueEntity.uid.md 'Friflo.Engine.ECS.UniqueEntity.uid') == [uid](EntityStoreBase.GetUniqueEntity(string).md#Friflo.Engine.ECS.EntityStoreBase.GetUniqueEntity(string).uid 'Friflo.Engine.ECS.EntityStoreBase.GetUniqueEntity(string).uid').<br/>
See <a href="https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md#unique-entity">Example.</a>

```csharp
public Friflo.Engine.ECS.Entity GetUniqueEntity(string uid);
```
#### Parameters

<a name='Friflo.Engine.ECS.EntityStoreBase.GetUniqueEntity(string).uid'></a>

`uid` [System.String](https://docs.microsoft.com/en-us/dotnet/api/System.String 'System.String')

#### Returns
[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

#### Exceptions

[System.InvalidOperationException](https://docs.microsoft.com/en-us/dotnet/api/System.InvalidOperationException 'System.InvalidOperationException')  
In case none or more than one [UniqueEntity](UniqueEntity.md 'Friflo.Engine.ECS.UniqueEntity') with the given [uid](EntityStoreBase.GetUniqueEntity(string).md#Friflo.Engine.ECS.EntityStoreBase.GetUniqueEntity(string).uid 'Friflo.Engine.ECS.EntityStoreBase.GetUniqueEntity(string).uid') found.

### Remarks
To Get all [UniqueEntity](UniqueEntity.md 'Friflo.Engine.ECS.UniqueEntity')'s of the store use [UniqueEntities](EntityStoreBase.UniqueEntities.md 'Friflo.Engine.ECS.EntityStoreBase.UniqueEntities').