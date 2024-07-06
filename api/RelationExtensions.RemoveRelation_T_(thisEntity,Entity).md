#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[RelationExtensions](RelationExtensions.md 'Friflo.Engine.ECS.RelationExtensions')

## RelationExtensions.RemoveRelation<T>(this Entity, Entity) Method

Removes the specified link relation [target](RelationExtensions.RemoveRelation_T_(thisEntity,Entity).md#Friflo.Engine.ECS.RelationExtensions.RemoveRelation_T_(thisFriflo.Engine.ECS.Entity,Friflo.Engine.ECS.Entity).target 'Friflo.Engine.ECS.RelationExtensions.RemoveRelation<T>(this Friflo.Engine.ECS.Entity, Friflo.Engine.ECS.Entity).target') from an entity.<br/>
Executes in O(N) N: number of link relations of the specified entity.

```csharp
public static bool RemoveRelation<T>(this Friflo.Engine.ECS.Entity entity, Friflo.Engine.ECS.Entity target)
    where T : struct, Friflo.Engine.ECS.ILinkRelation, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.RelationExtensions.RemoveRelation_T_(thisFriflo.Engine.ECS.Entity,Friflo.Engine.ECS.Entity).T'></a>

`T`
#### Parameters

<a name='Friflo.Engine.ECS.RelationExtensions.RemoveRelation_T_(thisFriflo.Engine.ECS.Entity,Friflo.Engine.ECS.Entity).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

<a name='Friflo.Engine.ECS.RelationExtensions.RemoveRelation_T_(thisFriflo.Engine.ECS.Entity,Friflo.Engine.ECS.Entity).target'></a>

`target` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
true if the entity contained a link relation of the given type before.

#### Exceptions

[System.NullReferenceException](https://docs.microsoft.com/en-us/dotnet/api/System.NullReferenceException 'System.NullReferenceException')  
If the entity is null.