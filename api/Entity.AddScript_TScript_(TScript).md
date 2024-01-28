#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.AddScript<TScript>(TScript) Method

Add the given [script](Entity.AddScript_TScript_(TScript).md#Friflo.Engine.ECS.Entity.AddScript_TScript_(TScript).script 'Friflo.Engine.ECS.Entity.AddScript<TScript>(TScript).script') to the entity.<br/>
            If the entity contains a script of the same [TScript](Entity.AddScript_TScript_(TScript).md#Friflo.Engine.ECS.Entity.AddScript_TScript_(TScript).TScript 'Friflo.Engine.ECS.Entity.AddScript<TScript>(TScript).TScript')[System.Type](https://docs.microsoft.com/en-us/dotnet/api/System.Type 'System.Type') it is replaced.

```csharp
public TScript AddScript<TScript>(TScript script)
    where TScript : Friflo.Engine.ECS.Script, new();
```
#### Type parameters

<a name='Friflo.Engine.ECS.Entity.AddScript_TScript_(TScript).TScript'></a>

`TScript`
#### Parameters

<a name='Friflo.Engine.ECS.Entity.AddScript_TScript_(TScript).script'></a>

`script` [TScript](Entity.AddScript_TScript_(TScript).md#Friflo.Engine.ECS.Entity.AddScript_TScript_(TScript).TScript 'Friflo.Engine.ECS.Entity.AddScript<TScript>(TScript).TScript')

#### Returns
[TScript](Entity.AddScript_TScript_(TScript).md#Friflo.Engine.ECS.Entity.AddScript_TScript_(TScript).TScript 'Friflo.Engine.ECS.Entity.AddScript<TScript>(TScript).TScript')  
The script with the passed [TScript](Entity.AddScript_TScript_(TScript).md#Friflo.Engine.ECS.Entity.AddScript_TScript_(TScript).TScript 'Friflo.Engine.ECS.Entity.AddScript<TScript>(TScript).TScript')[System.Type](https://docs.microsoft.com/en-us/dotnet/api/System.Type 'System.Type') previously added to the entity.<br/>
Return null if the entity had no script with the passed [TScript](Entity.AddScript_TScript_(TScript).md#Friflo.Engine.ECS.Entity.AddScript_TScript_(TScript).TScript 'Friflo.Engine.ECS.Entity.AddScript<TScript>(TScript).TScript')[System.Type](https://docs.microsoft.com/en-us/dotnet/api/System.Type 'System.Type').

### Remarks
Note: Use [AddNewEntityScript(Entity, ScriptType)](EntityUtils.AddNewEntityScript(Entity,ScriptType).md 'Friflo.Engine.ECS.EntityUtils.AddNewEntityScript(Friflo.Engine.ECS.Entity, Friflo.Engine.ECS.ScriptType)') as non generic alternative.