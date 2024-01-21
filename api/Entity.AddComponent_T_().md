#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.AddComponent<T>() Method

Add a component of the given type to the entity.

```csharp
public Friflo.Engine.ECS.ComponentChangedAction AddComponent<T>()
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Entity.AddComponent_T_().T'></a>

`T`

#### Returns
[ComponentChangedAction](ComponentChangedAction.md 'Friflo.Engine.ECS.ComponentChangedAction')

### Remarks
Executes in O(1)<br/><remarks>Note: Use <see cref="M:Friflo.Engine.ECS.EntityUtils.AddEntityComponent(Friflo.Engine.ECS.Entity,Friflo.Engine.ECS.ComponentType)"/> as non generic alternative</remarks>