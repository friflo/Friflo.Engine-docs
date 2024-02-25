#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[Entity](Entity.md#'Friflo.Engine.ECS.Entity')

## Entity.RemoveComponent<T>() Method

Remove the component of the given type from the entity.

```csharp
public bool RemoveComponent<T>()
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Entity.RemoveComponent_T_().T'></a>

`T`

#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean#'System.Boolean')  
true if entity contained a component of the given type before

### Remarks
Executes in O(1)<br/><remarks>Note: Use <see cref="M:Friflo.Engine.ECS.EntityUtils.RemoveEntityComponent(Friflo.Engine.ECS.Entity,Friflo.Engine.ECS.ComponentType)"/> as non generic alternative</remarks>