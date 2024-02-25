#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS')

## ITag Interface

Used to create entity <b>Tag</b>'s by declaring a struct without fields or properties extending [ITag](ITag.md#'Friflo.Engine.ECS.ITag').<br/><b>Note:</b> An [ITag](ITag.md#'Friflo.Engine.ECS.ITag') should be used to tag a group of multiple entities.<br/>
See <a href="https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md#tag">Example.</a>

```csharp
public interface ITag
```

Derived  
&#8627; [Disabled](Disabled.md#'Friflo.Engine.ECS.Disabled')

### Remarks
In case you want to find a unique entity add the component [UniqueEntity](UniqueEntity.md#'Friflo.Engine.ECS.UniqueEntity') to an entity<br/>
and use [GetUniqueEntity(string)](EntityStoreBase.GetUniqueEntity(string).md#'Friflo.Engine.ECS.EntityStoreBase.GetUniqueEntity(string)') to query for this entity.<br/><br/>
Optionally attribute the implementing struct with [TagNameAttribute](TagNameAttribute.md#'Friflo.Engine.ECS.TagNameAttribute')<br/>
to assign a custom tag name used for JSON serialization.