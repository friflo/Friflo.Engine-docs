#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityExtensions](EntityExtensions.md 'Friflo.Engine.ECS.EntityExtensions')

## EntityExtensions.Add<T1>(this Entity, T1, Tags) Method

Add the passed component and tags to the entity.

```csharp
public static void Add<T1>(this Friflo.Engine.ECS.Entity entity, in T1 component1, in Friflo.Engine.ECS.Tags tags=default(Friflo.Engine.ECS.Tags))
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1_(thisFriflo.Engine.ECS.Entity,T1,Friflo.Engine.ECS.Tags).T1'></a>

`T1`
#### Parameters

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1_(thisFriflo.Engine.ECS.Entity,T1,Friflo.Engine.ECS.Tags).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1_(thisFriflo.Engine.ECS.Entity,T1,Friflo.Engine.ECS.Tags).component1'></a>

`component1` [T1](EntityExtensions.Add_T1_(thisEntity,T1,Tags).md#Friflo.Engine.ECS.EntityExtensions.Add_T1_(thisFriflo.Engine.ECS.Entity,T1,Friflo.Engine.ECS.Tags).T1 'Friflo.Engine.ECS.EntityExtensions.Add<T1>(this Friflo.Engine.ECS.Entity, T1, Friflo.Engine.ECS.Tags).T1')

<a name='Friflo.Engine.ECS.EntityExtensions.Add_T1_(thisFriflo.Engine.ECS.Entity,T1,Friflo.Engine.ECS.Tags).tags'></a>

`tags` [Tags](Tags.md 'Friflo.Engine.ECS.Tags')