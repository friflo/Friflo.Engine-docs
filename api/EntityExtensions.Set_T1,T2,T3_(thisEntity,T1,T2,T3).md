#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityExtensions](EntityExtensions.md 'Friflo.Engine.ECS.EntityExtensions')

## EntityExtensions.Set<T1,T2,T3>(this Entity, T1, T2, T3) Method

Set the passed components on the entity.

```csharp
public static void Set<T1,T2,T3>(this Friflo.Engine.ECS.Entity entity, in T1 component1, in T2 component2, in T3 component3)
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3_(thisFriflo.Engine.ECS.Entity,T1,T2,T3).T1'></a>

`T1`

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3_(thisFriflo.Engine.ECS.Entity,T1,T2,T3).T2'></a>

`T2`

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3_(thisFriflo.Engine.ECS.Entity,T1,T2,T3).T3'></a>

`T3`
#### Parameters

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3_(thisFriflo.Engine.ECS.Entity,T1,T2,T3).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3_(thisFriflo.Engine.ECS.Entity,T1,T2,T3).component1'></a>

`component1` [T1](EntityExtensions.Set_T1,T2,T3_(thisEntity,T1,T2,T3).md#Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3_(thisFriflo.Engine.ECS.Entity,T1,T2,T3).T1 'Friflo.Engine.ECS.EntityExtensions.Set<T1,T2,T3>(this Friflo.Engine.ECS.Entity, T1, T2, T3).T1')

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3_(thisFriflo.Engine.ECS.Entity,T1,T2,T3).component2'></a>

`component2` [T2](EntityExtensions.Set_T1,T2,T3_(thisEntity,T1,T2,T3).md#Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3_(thisFriflo.Engine.ECS.Entity,T1,T2,T3).T2 'Friflo.Engine.ECS.EntityExtensions.Set<T1,T2,T3>(this Friflo.Engine.ECS.Entity, T1, T2, T3).T2')

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3_(thisFriflo.Engine.ECS.Entity,T1,T2,T3).component3'></a>

`component3` [T3](EntityExtensions.Set_T1,T2,T3_(thisEntity,T1,T2,T3).md#Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3_(thisFriflo.Engine.ECS.Entity,T1,T2,T3).T3 'Friflo.Engine.ECS.EntityExtensions.Set<T1,T2,T3>(this Friflo.Engine.ECS.Entity, T1, T2, T3).T3')

#### Exceptions

[MissingComponentException](MissingComponentException.md 'Friflo.Engine.ECS.MissingComponentException')  
if the entity does not contain a passed component.