#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## EntityUtils Class

```csharp
public static class EntityUtils
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; EntityUtils

| Fields | |
| :--- | :--- |
| [EqualityComparer](EntityUtils.EqualityComparer.md 'Friflo.Engine.ECS.EntityUtils.EqualityComparer') | |

| Methods | |
| :--- | :--- |
| [AddEntityComponent(Entity, ComponentType)](EntityUtils.AddEntityComponent(Entity,ComponentType).md 'Friflo.Engine.ECS.EntityUtils.AddEntityComponent(Friflo.Engine.ECS.Entity, Friflo.Engine.ECS.ComponentType)') | |
| [AddEntityComponentValue(Entity, ComponentType, object)](EntityUtils.AddEntityComponentValue(Entity,ComponentType,object).md 'Friflo.Engine.ECS.EntityUtils.AddEntityComponentValue(Friflo.Engine.ECS.Entity, Friflo.Engine.ECS.ComponentType, object)') | |
| [AddEntityScript(Entity, Script)](EntityUtils.AddEntityScript(Entity,Script).md 'Friflo.Engine.ECS.EntityUtils.AddEntityScript(Friflo.Engine.ECS.Entity, Friflo.Engine.ECS.Script)') | |
| [AddNewEntityScript(Entity, ScriptType)](EntityUtils.AddNewEntityScript(Entity,ScriptType).md 'Friflo.Engine.ECS.EntityUtils.AddNewEntityScript(Friflo.Engine.ECS.Entity, Friflo.Engine.ECS.ScriptType)') | |
| [GetEntityComponent(Entity, ComponentType)](EntityUtils.GetEntityComponent(Entity,ComponentType).md 'Friflo.Engine.ECS.EntityUtils.GetEntityComponent(Friflo.Engine.ECS.Entity, Friflo.Engine.ECS.ComponentType)') | Returns a copy of the entity component as an object.<br/> The returned [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') is a boxed struct.<br/> So avoid using this method whenever possible. Use [GetComponent&lt;T&gt;()](Entity.GetComponent_T_().md 'Friflo.Engine.ECS.Entity.GetComponent<T>()') instead. |
| [GetEntityScript(Entity, ScriptType)](EntityUtils.GetEntityScript(Entity,ScriptType).md 'Friflo.Engine.ECS.EntityUtils.GetEntityScript(Friflo.Engine.ECS.Entity, Friflo.Engine.ECS.ScriptType)') | |
| [RemoveEntityComponent(Entity, ComponentType)](EntityUtils.RemoveEntityComponent(Entity,ComponentType).md 'Friflo.Engine.ECS.EntityUtils.RemoveEntityComponent(Friflo.Engine.ECS.Entity, Friflo.Engine.ECS.ComponentType)') | |
| [RemoveEntityScript(Entity, ScriptType)](EntityUtils.RemoveEntityScript(Entity,ScriptType).md 'Friflo.Engine.ECS.EntityUtils.RemoveEntityScript(Friflo.Engine.ECS.Entity, Friflo.Engine.ECS.ScriptType)') | |
