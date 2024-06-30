#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[RelationExtensions](RelationExtensions.md 'Friflo.Engine.ECS.RelationExtensions')

## RelationExtensions.RemoveRelation<T,TKey>(this Entity, TKey) Method

Removes the relation component with the specified [key](RelationExtensions.RemoveRelation_T,TKey_(thisEntity,TKey).md#Friflo.Engine.ECS.RelationExtensions.RemoveRelation_T,TKey_(thisFriflo.Engine.ECS.Entity,TKey).key 'Friflo.Engine.ECS.RelationExtensions.RemoveRelation<T,TKey>(this Friflo.Engine.ECS.Entity, TKey).key') from an entity.<br/>
Executes in O(N) N: number of relations of the specific entity.

```csharp
public static bool RemoveRelation<T,TKey>(this Friflo.Engine.ECS.Entity entity, TKey key)
    where T : struct, Friflo.Engine.ECS.IRelationComponent<TKey>, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.RelationExtensions.RemoveRelation_T,TKey_(thisFriflo.Engine.ECS.Entity,TKey).T'></a>

`T`

<a name='Friflo.Engine.ECS.RelationExtensions.RemoveRelation_T,TKey_(thisFriflo.Engine.ECS.Entity,TKey).TKey'></a>

`TKey`
#### Parameters

<a name='Friflo.Engine.ECS.RelationExtensions.RemoveRelation_T,TKey_(thisFriflo.Engine.ECS.Entity,TKey).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

<a name='Friflo.Engine.ECS.RelationExtensions.RemoveRelation_T,TKey_(thisFriflo.Engine.ECS.Entity,TKey).key'></a>

`key` [TKey](RelationExtensions.RemoveRelation_T,TKey_(thisEntity,TKey).md#Friflo.Engine.ECS.RelationExtensions.RemoveRelation_T,TKey_(thisFriflo.Engine.ECS.Entity,TKey).TKey 'Friflo.Engine.ECS.RelationExtensions.RemoveRelation<T,TKey>(this Friflo.Engine.ECS.Entity, TKey).TKey')

#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
true if the entity contained a relation of the given type before.