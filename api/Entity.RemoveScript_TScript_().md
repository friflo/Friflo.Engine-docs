#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[Entity](Entity.md#'Friflo.Engine.ECS.Entity')

## Entity.RemoveScript<TScript>() Method

Remove the script with the given [TScript](Entity.RemoveScript_TScript_().md#Friflo.Engine.ECS.Entity.RemoveScript_TScript_().TScript#'Friflo.Engine.ECS.Entity.RemoveScript<TScript>().TScript')[System.Type](https://docs.microsoft.com/en-us/dotnet/api/System.Type#'System.Type') from the entity.

```csharp
public TScript RemoveScript<TScript>()
    where TScript : Friflo.Engine.ECS.Script, new();
```
#### Type parameters

<a name='Friflo.Engine.ECS.Entity.RemoveScript_TScript_().TScript'></a>

`TScript`

#### Returns
[TScript](Entity.RemoveScript_TScript_().md#Friflo.Engine.ECS.Entity.RemoveScript_TScript_().TScript#'Friflo.Engine.ECS.Entity.RemoveScript<TScript>().TScript')  
The script the script with the passed [TScript](Entity.RemoveScript_TScript_().md#Friflo.Engine.ECS.Entity.RemoveScript_TScript_().TScript#'Friflo.Engine.ECS.Entity.RemoveScript<TScript>().TScript')[System.Type](https://docs.microsoft.com/en-us/dotnet/api/System.Type#'System.Type') previously added to the entity.<br/>
Or null if the entity has no script with the passed [TScript](Entity.RemoveScript_TScript_().md#Friflo.Engine.ECS.Entity.RemoveScript_TScript_().TScript#'Friflo.Engine.ECS.Entity.RemoveScript<TScript>().TScript')[System.Type](https://docs.microsoft.com/en-us/dotnet/api/System.Type#'System.Type').

### Remarks
Note: Use [RemoveEntityScript(Entity, ScriptType)](EntityUtils.RemoveEntityScript(Entity,ScriptType).md#'Friflo.Engine.ECS.EntityUtils.RemoveEntityScript(Friflo.Engine.ECS.Entity, Friflo.Engine.ECS.ScriptType)') as non generic alternative.