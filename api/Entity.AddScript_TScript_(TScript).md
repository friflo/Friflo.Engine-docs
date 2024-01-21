#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.AddScript<TScript>(TScript) Method

Add the given [script](Entity.AddScript_TScript_(TScript).md#Friflo.Engine.ECS.Entity.AddScript_TScript_(TScript).script 'Friflo.Engine.ECS.Entity.AddScript<TScript>(TScript).script') to the entity.

```csharp
public TScript AddScript<TScript>(TScript script)
    where TScript : Friflo.Engine.ECS.Script;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Entity.AddScript_TScript_(TScript).TScript'></a>

`TScript`
#### Parameters

<a name='Friflo.Engine.ECS.Entity.AddScript_TScript_(TScript).script'></a>

`script` [TScript](Entity.AddScript_TScript_(TScript).md#Friflo.Engine.ECS.Entity.AddScript_TScript_(TScript).TScript 'Friflo.Engine.ECS.Entity.AddScript<TScript>(TScript).TScript')

#### Returns
[TScript](Entity.AddScript_TScript_(TScript).md#Friflo.Engine.ECS.Entity.AddScript_TScript_(TScript).TScript 'Friflo.Engine.ECS.Entity.AddScript<TScript>(TScript).TScript')  
the [Script](Script.md 'Friflo.Engine.ECS.Script') previously added to the entity.

### Remarks
Note: Use [AddNewEntityScript(Entity, ScriptType)](EntityUtils.AddNewEntityScript(Entity,ScriptType).md 'Friflo.Engine.ECS.EntityUtils.AddNewEntityScript(Friflo.Engine.ECS.Entity, Friflo.Engine.ECS.ScriptType)') as non generic alternative