#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityExtensions](EntityExtensions.md 'Friflo.Engine.ECS.EntityExtensions')

## EntityExtensions.Add<T1,T2,T3,T4,T5,T6>(this Entity, T1, T2, T3, T4, T5, T6, Tags) Method

Add the passed components and tags to the entity.

```csharp
public static void Add<T1,T2,T3,T4,T5,T6>(this Friflo.Engine.ECS.Entity entity, in T1 component1, in T2 component2, in T3 component3, in T4 component4, in T5 component5, in T6 component6, in Friflo.Engine.ECS.Tags tags=default(Friflo.Engine.ECS.Tags))
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T4 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T5 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T6 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6,Friflo.Engine.ECS.Tags).T1'></a>

`T1`

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6,Friflo.Engine.ECS.Tags).T2'></a>

`T2`

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6,Friflo.Engine.ECS.Tags).T3'></a>

`T3`

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6,Friflo.Engine.ECS.Tags).T4'></a>

`T4`

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6,Friflo.Engine.ECS.Tags).T5'></a>

`T5`

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6,Friflo.Engine.ECS.Tags).T6'></a>

`T6`
#### Parameters

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6,Friflo.Engine.ECS.Tags).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6,Friflo.Engine.ECS.Tags).component1'></a>

`component1` [T1](EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisEntity,T1,T2,T3,T4,T5,T6,Tags).md#Friflo.Engine.ECS.EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6,Friflo.Engine.ECS.Tags).T1 'Friflo.Engine.ECS.EntityExtensions.Add<T1,T2,T3,T4,T5,T6>(this Friflo.Engine.ECS.Entity, T1, T2, T3, T4, T5, T6, Friflo.Engine.ECS.Tags).T1')

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6,Friflo.Engine.ECS.Tags).component2'></a>

`component2` [T2](EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisEntity,T1,T2,T3,T4,T5,T6,Tags).md#Friflo.Engine.ECS.EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6,Friflo.Engine.ECS.Tags).T2 'Friflo.Engine.ECS.EntityExtensions.Add<T1,T2,T3,T4,T5,T6>(this Friflo.Engine.ECS.Entity, T1, T2, T3, T4, T5, T6, Friflo.Engine.ECS.Tags).T2')

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6,Friflo.Engine.ECS.Tags).component3'></a>

`component3` [T3](EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisEntity,T1,T2,T3,T4,T5,T6,Tags).md#Friflo.Engine.ECS.EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6,Friflo.Engine.ECS.Tags).T3 'Friflo.Engine.ECS.EntityExtensions.Add<T1,T2,T3,T4,T5,T6>(this Friflo.Engine.ECS.Entity, T1, T2, T3, T4, T5, T6, Friflo.Engine.ECS.Tags).T3')

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6,Friflo.Engine.ECS.Tags).component4'></a>

`component4` [T4](EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisEntity,T1,T2,T3,T4,T5,T6,Tags).md#Friflo.Engine.ECS.EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6,Friflo.Engine.ECS.Tags).T4 'Friflo.Engine.ECS.EntityExtensions.Add<T1,T2,T3,T4,T5,T6>(this Friflo.Engine.ECS.Entity, T1, T2, T3, T4, T5, T6, Friflo.Engine.ECS.Tags).T4')

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6,Friflo.Engine.ECS.Tags).component5'></a>

`component5` [T5](EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisEntity,T1,T2,T3,T4,T5,T6,Tags).md#Friflo.Engine.ECS.EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6,Friflo.Engine.ECS.Tags).T5 'Friflo.Engine.ECS.EntityExtensions.Add<T1,T2,T3,T4,T5,T6>(this Friflo.Engine.ECS.Entity, T1, T2, T3, T4, T5, T6, Friflo.Engine.ECS.Tags).T5')

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6,Friflo.Engine.ECS.Tags).component6'></a>

`component6` [T6](EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisEntity,T1,T2,T3,T4,T5,T6,Tags).md#Friflo.Engine.ECS.EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6,Friflo.Engine.ECS.Tags).T6 'Friflo.Engine.ECS.EntityExtensions.Add<T1,T2,T3,T4,T5,T6>(this Friflo.Engine.ECS.Entity, T1, T2, T3, T4, T5, T6, Friflo.Engine.ECS.Tags).T6')

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1,T2,T3,T4,T5,T6_(thisFriflo.Engine.ECS.Entity,T1,T2,T3,T4,T5,T6,Friflo.Engine.ECS.Tags).tags'></a>

`tags` [Tags](Tags.md 'Friflo.Engine.ECS.Tags')