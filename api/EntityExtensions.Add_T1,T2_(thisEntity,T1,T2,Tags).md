#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityExtensions](EntityExtensions.md 'Friflo.Engine.ECS.EntityExtensions')

## EntityExtensions.Add<T1,T2>(this Entity, T1, T2, Tags) Method

Add the passed components and tags to the entity.

```csharp
public static void Add<T1,T2>(this Friflo.Engine.ECS.Entity entity, in T1 component1, in T2 component2, in Friflo.Engine.ECS.Tags tags=default(Friflo.Engine.ECS.Tags))
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1,T2_(thisFriflo.Engine.ECS.Entity,T1,T2,Friflo.Engine.ECS.Tags).T1'></a>

`T1`

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1,T2_(thisFriflo.Engine.ECS.Entity,T1,T2,Friflo.Engine.ECS.Tags).T2'></a>

`T2`
#### Parameters

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1,T2_(thisFriflo.Engine.ECS.Entity,T1,T2,Friflo.Engine.ECS.Tags).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1,T2_(thisFriflo.Engine.ECS.Entity,T1,T2,Friflo.Engine.ECS.Tags).component1'></a>

`component1` [T1](EntityExtensions.Add_T1,T2_(thisEntity,T1,T2,Tags).md#Friflo.Engine.ECS.EntityExtensions.Add_T1,T2_(thisFriflo.Engine.ECS.Entity,T1,T2,Friflo.Engine.ECS.Tags).T1 'Friflo.Engine.ECS.EntityExtensions.Add<T1,T2>(this Friflo.Engine.ECS.Entity, T1, T2, Friflo.Engine.ECS.Tags).T1')

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1,T2_(thisFriflo.Engine.ECS.Entity,T1,T2,Friflo.Engine.ECS.Tags).component2'></a>

`component2` [T2](EntityExtensions.Add_T1,T2_(thisEntity,T1,T2,Tags).md#Friflo.Engine.ECS.EntityExtensions.Add_T1,T2_(thisFriflo.Engine.ECS.Entity,T1,T2,Friflo.Engine.ECS.Tags).T2 'Friflo.Engine.ECS.EntityExtensions.Add<T1,T2>(this Friflo.Engine.ECS.Entity, T1, T2, Friflo.Engine.ECS.Tags).T2')

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1,T2_(thisFriflo.Engine.ECS.Entity,T1,T2,Friflo.Engine.ECS.Tags).tags'></a>

`tags` [Tags](Tags.md 'Friflo.Engine.ECS.Tags')