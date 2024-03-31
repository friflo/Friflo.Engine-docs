#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityExtensions](EntityExtensions.md 'Friflo.Engine.ECS.EntityExtensions')

## EntityExtensions.Remove<T1>(this Entity, Tags) Method

Remove the specified component and tags from the entity.

```csharp
public static void Remove<T1>(this Friflo.Engine.ECS.Entity entity, in Friflo.Engine.ECS.Tags tags=default(Friflo.Engine.ECS.Tags))
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityExtensions.Remove_T1_(thisFriflo.Engine.ECS.Entity,Friflo.Engine.ECS.Tags).T1'></a>

`T1`
#### Parameters

<a name='Friflo.Engine.ECS.EntityExtensions.Remove_T1_(thisFriflo.Engine.ECS.Entity,Friflo.Engine.ECS.Tags).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

<a name='Friflo.Engine.ECS.EntityExtensions.Remove_T1_(thisFriflo.Engine.ECS.Entity,Friflo.Engine.ECS.Tags).tags'></a>

`tags` [Tags](Tags.md 'Friflo.Engine.ECS.Tags')