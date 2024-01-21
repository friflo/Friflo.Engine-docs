#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityUtils](EntityUtils.md 'Friflo.Engine.ECS.EntityUtils')

## EntityUtils.GetEntityComponent(Entity, ComponentType) Method

Returns a copy of the entity component as an object.<br/>
The returned [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') is a boxed struct.<br/>
So avoid using this method whenever possible. Use [GetComponent&lt;T&gt;()](Entity.GetComponent_T_().md 'Friflo.Engine.ECS.Entity.GetComponent<T>()') instead.

```csharp
public static Friflo.Engine.ECS.IComponent GetEntityComponent(Friflo.Engine.ECS.Entity entity, Friflo.Engine.ECS.ComponentType componentType);
```
#### Parameters

<a name='Friflo.Engine.ECS.EntityUtils.GetEntityComponent(Friflo.Engine.ECS.Entity,Friflo.Engine.ECS.ComponentType).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

<a name='Friflo.Engine.ECS.EntityUtils.GetEntityComponent(Friflo.Engine.ECS.Entity,Friflo.Engine.ECS.ComponentType).componentType'></a>

`componentType` [ComponentType](ComponentType.md 'Friflo.Engine.ECS.ComponentType')

#### Returns
[IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')