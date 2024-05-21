#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.AddComponent<T>() Method

Add a component of the given type [T](Entity.AddComponent_T_().md#Friflo.Engine.ECS.Entity.AddComponent_T_().T 'Friflo.Engine.ECS.Entity.AddComponent<T>().T') to the entity.<br/>
See <a href="https://github.com/friflo/Friflo.Json.Fliox/wiki/Examples-~-General#component">Example.</a><br/>
If the entity contains a component of the same type it is updated.

```csharp
public bool AddComponent<T>()
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Entity.AddComponent_T_().T'></a>

`T`

#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
true - component is newly added to the entity.<br/> false - component is updated.

### Remarks
Note: Use [AddEntityComponent(Entity, ComponentType)](EntityUtils.AddEntityComponent(Entity,ComponentType).md 'Friflo.Engine.ECS.EntityUtils.AddEntityComponent(Friflo.Engine.ECS.Entity, Friflo.Engine.ECS.ComponentType)') as non generic alternative