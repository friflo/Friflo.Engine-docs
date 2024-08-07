#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.AddComponent<T>(T) Method

Add the given [component](Entity.AddComponent_T_(T).md#Friflo.Engine.ECS.Entity.AddComponent_T_(T).component 'Friflo.Engine.ECS.Entity.AddComponent<T>(T).component') to the entity.<br/>
If the entity contains a component of the same type it is updated.<br/>
See <a href="https://friflo.gitbook.io/friflo.engine.ecs/examples/general#component">Example.</a>

```csharp
public bool AddComponent<T>(in T component)
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Entity.AddComponent_T_(T).T'></a>

`T`
#### Parameters

<a name='Friflo.Engine.ECS.Entity.AddComponent_T_(T).component'></a>

`component` [T](Entity.AddComponent_T_(T).md#Friflo.Engine.ECS.Entity.AddComponent_T_(T).T 'Friflo.Engine.ECS.Entity.AddComponent<T>(T).T')

#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
true - component is newly added to the entity.<br/> false - component is updated.