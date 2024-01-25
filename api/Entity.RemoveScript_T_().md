#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.RemoveScript<T>() Method

Remove the script with the given type from the entity.

```csharp
public T RemoveScript<T>()
    where T : Friflo.Engine.ECS.Script, new();
```
#### Type parameters

<a name='Friflo.Engine.ECS.Entity.RemoveScript_T_().T'></a>

`T`

#### Returns
[T](Entity.RemoveScript_T_().md#Friflo.Engine.ECS.Entity.RemoveScript_T_().T 'Friflo.Engine.ECS.Entity.RemoveScript<T>().T')  
The [Script](Script.md 'Friflo.Engine.ECS.Script') previously added to the entity.

### Remarks
Note: Use [RemoveEntityScript(Entity, ScriptType)](EntityUtils.RemoveEntityScript(Entity,ScriptType).md 'Friflo.Engine.ECS.EntityUtils.RemoveEntityScript(Friflo.Engine.ECS.Entity, Friflo.Engine.ECS.ScriptType)') as non generic alternative