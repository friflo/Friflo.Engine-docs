#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityExtensions](EntityExtensions.md 'Friflo.Engine.ECS.EntityExtensions')

## EntityExtensions.Remove<T1,T2,T3>(this Entity, Tags) Method

Remove the specified components and tags from the entity.

```csharp
public static void Remove<T1,T2,T3>(this Friflo.Engine.ECS.Entity entity, in Friflo.Engine.ECS.Tags tags=default(Friflo.Engine.ECS.Tags))
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityExtensions.Remove_T1,T2,T3_(thisFriflo.Engine.ECS.Entity,Friflo.Engine.ECS.Tags).T1'></a>

`T1`

<a name='Friflo.Engine.ECS.EntityExtensions.Remove_T1,T2,T3_(thisFriflo.Engine.ECS.Entity,Friflo.Engine.ECS.Tags).T2'></a>

`T2`

<a name='Friflo.Engine.ECS.EntityExtensions.Remove_T1,T2,T3_(thisFriflo.Engine.ECS.Entity,Friflo.Engine.ECS.Tags).T3'></a>

`T3`
#### Parameters

<a name='Friflo.Engine.ECS.EntityExtensions.Remove_T1,T2,T3_(thisFriflo.Engine.ECS.Entity,Friflo.Engine.ECS.Tags).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

<a name='Friflo.Engine.ECS.EntityExtensions.Remove_T1,T2,T3_(thisFriflo.Engine.ECS.Entity,Friflo.Engine.ECS.Tags).tags'></a>

`tags` [Tags](Tags.md 'Friflo.Engine.ECS.Tags')