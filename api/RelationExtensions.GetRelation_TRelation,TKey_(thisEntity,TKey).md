#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[RelationExtensions](RelationExtensions.md 'Friflo.Engine.ECS.RelationExtensions')

## RelationExtensions.GetRelation<TRelation,TKey>(this Entity, TKey) Method

Returns the relation of the [entity](RelationExtensions.GetRelation_TRelation,TKey_(thisEntity,TKey).md#Friflo.Engine.ECS.RelationExtensions.GetRelation_TRelation,TKey_(thisFriflo.Engine.ECS.Entity,TKey).entity 'Friflo.Engine.ECS.RelationExtensions.GetRelation<TRelation,TKey>(this Friflo.Engine.ECS.Entity, TKey).entity') with the given [key](RelationExtensions.GetRelation_TRelation,TKey_(thisEntity,TKey).md#Friflo.Engine.ECS.RelationExtensions.GetRelation_TRelation,TKey_(thisFriflo.Engine.ECS.Entity,TKey).key 'Friflo.Engine.ECS.RelationExtensions.GetRelation<TRelation,TKey>(this Friflo.Engine.ECS.Entity, TKey).key').<br/>
Executes in O(N) N: number of entity relations.

```csharp
public static ref TRelation GetRelation<TRelation,TKey>(this Friflo.Engine.ECS.Entity entity, TKey key)
    where TRelation : struct, Friflo.Engine.ECS.IRelation<TKey>, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetRelation_TRelation,TKey_(thisFriflo.Engine.ECS.Entity,TKey).TRelation'></a>

`TRelation`

<a name='Friflo.Engine.ECS.RelationExtensions.GetRelation_TRelation,TKey_(thisFriflo.Engine.ECS.Entity,TKey).TKey'></a>

`TKey`
#### Parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetRelation_TRelation,TKey_(thisFriflo.Engine.ECS.Entity,TKey).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

<a name='Friflo.Engine.ECS.RelationExtensions.GetRelation_TRelation,TKey_(thisFriflo.Engine.ECS.Entity,TKey).key'></a>

`key` [TKey](RelationExtensions.GetRelation_TRelation,TKey_(thisEntity,TKey).md#Friflo.Engine.ECS.RelationExtensions.GetRelation_TRelation,TKey_(thisFriflo.Engine.ECS.Entity,TKey).TKey 'Friflo.Engine.ECS.RelationExtensions.GetRelation<TRelation,TKey>(this Friflo.Engine.ECS.Entity, TKey).TKey')

#### Returns
[TRelation](RelationExtensions.GetRelation_TRelation,TKey_(thisEntity,TKey).md#Friflo.Engine.ECS.RelationExtensions.GetRelation_TRelation,TKey_(thisFriflo.Engine.ECS.Entity,TKey).TRelation 'Friflo.Engine.ECS.RelationExtensions.GetRelation<TRelation,TKey>(this Friflo.Engine.ECS.Entity, TKey).TRelation')

#### Exceptions

[System.Collections.Generic.KeyNotFoundException](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.KeyNotFoundException 'System.Collections.Generic.KeyNotFoundException')  
The relation is not found at the passed entity.

[System.NullReferenceException](https://docs.microsoft.com/en-us/dotnet/api/System.NullReferenceException 'System.NullReferenceException')  
If the entity is null.