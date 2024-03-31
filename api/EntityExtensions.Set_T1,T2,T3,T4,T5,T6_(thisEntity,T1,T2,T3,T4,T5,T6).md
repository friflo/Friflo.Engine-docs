#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityExtensions](EntityExtensions.md 'Friflo.Engine.ECS.EntityExtensions')

## EntityExtensions.Set<T1,T2,T3,T4,T5,T6>(this Entity, T1, T2, T3, T4, T5, T6) Method

Set the passed components on the entity.

```csharp
public static void Set<T1,T2,T3,T4,T5,T6>(this Friflo.Engine.ECS.Entity entity, in T1 component1, in T2 component2, in T3 component3, in T4 component4, in T5 component5, in T6 component6)
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T4 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T5 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T6 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6).T1'></a>

`T1`

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6).T2'></a>

`T2`

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6).T3'></a>

`T3`

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6).T4'></a>

`T4`

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6).T5'></a>

`T5`

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6).T6'></a>

`T6`
#### Parameters

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6).component1'></a>

`component1` [T1](EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisEntity,T1,T2,T3,T4,T5,T6).md#Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6).T1 'Friflo.Engine.ECS.EntityExtensions.Set<T1,T2,T3,T4,T5,T6>(this Friflo.Engine.ECS.Entity, T1, T2, T3, T4, T5, T6).T1')

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6).component2'></a>

`component2` [T2](EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisEntity,T1,T2,T3,T4,T5,T6).md#Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6).T2 'Friflo.Engine.ECS.EntityExtensions.Set<T1,T2,T3,T4,T5,T6>(this Friflo.Engine.ECS.Entity, T1, T2, T3, T4, T5, T6).T2')

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6).component3'></a>

`component3` [T3](EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisEntity,T1,T2,T3,T4,T5,T6).md#Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6).T3 'Friflo.Engine.ECS.EntityExtensions.Set<T1,T2,T3,T4,T5,T6>(this Friflo.Engine.ECS.Entity, T1, T2, T3, T4, T5, T6).T3')

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6).component4'></a>

`component4` [T4](EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisEntity,T1,T2,T3,T4,T5,T6).md#Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6).T4 'Friflo.Engine.ECS.EntityExtensions.Set<T1,T2,T3,T4,T5,T6>(this Friflo.Engine.ECS.Entity, T1, T2, T3, T4, T5, T6).T4')

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6).component5'></a>

`component5` [T5](EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisEntity,T1,T2,T3,T4,T5,T6).md#Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6).T5 'Friflo.Engine.ECS.EntityExtensions.Set<T1,T2,T3,T4,T5,T6>(this Friflo.Engine.ECS.Entity, T1, T2, T3, T4, T5, T6).T5')

<a name='Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6).component6'></a>

`component6` [T6](EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisEntity,T1,T2,T3,T4,T5,T6).md#Friflo.Engine.ECS.EntityExtensions.Set_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6).T6 'Friflo.Engine.ECS.EntityExtensions.Set<T1,T2,T3,T4,T5,T6>(this Friflo.Engine.ECS.Entity, T1, T2, T3, T4, T5, T6).T6')

#### Exceptions

[MissingComponentException](MissingComponentException.md 'Friflo.Engine.ECS.MissingComponentException')  
if the entity does not contain a passed component.