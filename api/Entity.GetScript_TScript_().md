#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[Entity](Entity.md#'Friflo.Engine.ECS.Entity')

## Entity.GetScript<TScript>() Method

Get the script of the passed [TScript](Entity.GetScript_TScript_().md#Friflo.Engine.ECS.Entity.GetScript_TScript_().TScript#'Friflo.Engine.ECS.Entity.GetScript<TScript>().TScript')[System.Type](https://docs.microsoft.com/en-us/dotnet/api/System.Type#'System.Type').

```csharp
public TScript GetScript<TScript>()
    where TScript : Friflo.Engine.ECS.Script, new();
```
#### Type parameters

<a name='Friflo.Engine.ECS.Entity.GetScript_TScript_().TScript'></a>

`TScript`

#### Returns
[TScript](Entity.GetScript_TScript_().md#Friflo.Engine.ECS.Entity.GetScript_TScript_().TScript#'Friflo.Engine.ECS.Entity.GetScript<TScript>().TScript')  
null if the entity has no script of the passed [TScript](Entity.GetScript_TScript_().md#Friflo.Engine.ECS.Entity.GetScript_TScript_().TScript#'Friflo.Engine.ECS.Entity.GetScript<TScript>().TScript')[System.Type](https://docs.microsoft.com/en-us/dotnet/api/System.Type#'System.Type').

### Remarks
Note: Use [GetEntityScript(Entity, ScriptType)](EntityUtils.GetEntityScript(Entity,ScriptType).md#'Friflo.Engine.ECS.EntityUtils.GetEntityScript(Friflo.Engine.ECS.Entity, Friflo.Engine.ECS.ScriptType)') as non generic alternative.