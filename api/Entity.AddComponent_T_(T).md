#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.AddComponent<T>(T) Method

Add the given [component](Entity.AddComponent_T_(T).md#Friflo.Engine.ECS.Entity.AddComponent_T_(T).component 'Friflo.Engine.ECS.Entity.AddComponent<T>(T).component') to the entity.

```csharp
public Friflo.Engine.ECS.ComponentChangedAction AddComponent<T>(in T component)
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Entity.AddComponent_T_(T).T'></a>

`T`
#### Parameters

<a name='Friflo.Engine.ECS.Entity.AddComponent_T_(T).component'></a>

`component` [T](Entity.AddComponent_T_(T).md#Friflo.Engine.ECS.Entity.AddComponent_T_(T).T 'Friflo.Engine.ECS.Entity.AddComponent<T>(T).T')

#### Returns
[ComponentChangedAction](ComponentChangedAction.md 'Friflo.Engine.ECS.ComponentChangedAction')

### Remarks
Executes in O(1)