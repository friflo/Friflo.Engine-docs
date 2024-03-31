#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityExtensions](EntityExtensions.md 'Friflo.Engine.ECS.EntityExtensions')

## EntityExtensions.Remove<T1,T2,T3,T4,T5,T6,T7>(this Entity, Tags) Method

Remove the specified components and tags from the entity.

```csharp
public static void Remove<T1,T2,T3,T4,T5,T6,T7>(this Friflo.Engine.ECS.Entity entity, in Friflo.Engine.ECS.Tags tags=default(Friflo.Engine.ECS.Tags))
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T4 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T5 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T6 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T7 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityExtensions.Remove_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.Entity,Friflo.Engine.ECS.Tags).T1'></a>

`T1`

<a name='Friflo.Engine.ECS.EntityExtensions.Remove_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.Entity,Friflo.Engine.ECS.Tags).T2'></a>

`T2`

<a name='Friflo.Engine.ECS.EntityExtensions.Remove_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.Entity,Friflo.Engine.ECS.Tags).T3'></a>

`T3`

<a name='Friflo.Engine.ECS.EntityExtensions.Remove_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.Entity,Friflo.Engine.ECS.Tags).T4'></a>

`T4`

<a name='Friflo.Engine.ECS.EntityExtensions.Remove_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.Entity,Friflo.Engine.ECS.Tags).T5'></a>

`T5`

<a name='Friflo.Engine.ECS.EntityExtensions.Remove_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.Entity,Friflo.Engine.ECS.Tags).T6'></a>

`T6`

<a name='Friflo.Engine.ECS.EntityExtensions.Remove_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.Entity,Friflo.Engine.ECS.Tags).T7'></a>

`T7`
#### Parameters

<a name='Friflo.Engine.ECS.EntityExtensions.Remove_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.Entity,Friflo.Engine.ECS.Tags).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

<a name='Friflo.Engine.ECS.EntityExtensions.Remove_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.Entity,Friflo.Engine.ECS.Tags).tags'></a>

`tags` [Tags](Tags.md 'Friflo.Engine.ECS.Tags')