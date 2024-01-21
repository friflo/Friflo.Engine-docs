#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.GetScript<T>() Method

Returns the [Script](Script.md 'Friflo.Engine.ECS.Script') of Type [T](Entity.GetScript_T_().md#Friflo.Engine.ECS.Entity.GetScript_T_().T 'Friflo.Engine.ECS.Entity.GetScript<T>().T'). Otherwise null

```csharp
public T GetScript<T>()
    where T : Friflo.Engine.ECS.Script;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Entity.GetScript_T_().T'></a>

`T`

#### Returns
[T](Entity.GetScript_T_().md#Friflo.Engine.ECS.Entity.GetScript_T_().T 'Friflo.Engine.ECS.Entity.GetScript<T>().T')

### Remarks
Note: Use [GetEntityScript(Entity, ScriptType)](EntityUtils.GetEntityScript(Entity,ScriptType).md 'Friflo.Engine.ECS.EntityUtils.GetEntityScript(Friflo.Engine.ECS.Entity, Friflo.Engine.ECS.ScriptType)') as non generic alternative