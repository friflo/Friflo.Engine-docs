#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityExtensions](EntityExtensions.md 'Friflo.Engine.ECS.EntityExtensions')

## EntityExtensions.Set<T1>(this Entity, T1) Method

Set the passed component on the entity.

```csharp
public static void Set<T1>(this Friflo.Engine.ECS.Entity entity, in T1 component1)
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1_(thisFriflo.Engine.ECS.Entity,T1).T1'></a>

`T1`
#### Parameters

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1_(thisFriflo.Engine.ECS.Entity,T1).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1_(thisFriflo.Engine.ECS.Entity,T1).component1'></a>

`component1` [T1](EntityExtensions.Set_T1_(thisEntity,T1).md#Friflo.Engine.ECS.EntityExtensions.Set_T1_(thisFriflo.Engine.ECS.Entity,T1).T1 'Friflo.Engine.ECS.EntityExtensions.Set<T1>(this Friflo.Engine.ECS.Entity, T1).T1')

#### Exceptions

[MissingComponentException](MissingComponentException.md 'Friflo.Engine.ECS.MissingComponentException')  
if the entity does not contain a passed component.