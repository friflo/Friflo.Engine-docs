#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[RelationExtensions](RelationExtensions.md 'Friflo.Engine.ECS.RelationExtensions')

## RelationExtensions.TryGetRelation<TRelation,TKey>(this Entity, TKey, TRelation) Method

Returns the relation of the [entity](RelationExtensions.TryGetRelation_TRelation,TKey_(thisEntity,TKey,TRelation).md#Friflo.Engine.ECS.RelationExtensions.TryGetRelation_TRelation,TKey_(thisFriflo.Engine.ECS.Entity,TKey,TRelation).entity 'Friflo.Engine.ECS.RelationExtensions.TryGetRelation<TRelation,TKey>(this Friflo.Engine.ECS.Entity, TKey, TRelation).entity') with the given [key](RelationExtensions.TryGetRelation_TRelation,TKey_(thisEntity,TKey,TRelation).md#Friflo.Engine.ECS.RelationExtensions.TryGetRelation_TRelation,TKey_(thisFriflo.Engine.ECS.Entity,TKey,TRelation).key 'Friflo.Engine.ECS.RelationExtensions.TryGetRelation<TRelation,TKey>(this Friflo.Engine.ECS.Entity, TKey, TRelation).key').<br/>
Executes in O(N) N: number of entity relations.

```csharp
public static bool TryGetRelation<TRelation,TKey>(this Friflo.Engine.ECS.Entity entity, TKey key, out TRelation value)
    where TRelation : struct, Friflo.Engine.ECS.IRelation<TKey>, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.RelationExtensions.TryGetRelation_TRelation,TKey_(thisFriflo.Engine.ECS.Entity,TKey,TRelation).TRelation'></a>

`TRelation`

<a name='Friflo.Engine.ECS.RelationExtensions.TryGetRelation_TRelation,TKey_(thisFriflo.Engine.ECS.Entity,TKey,TRelation).TKey'></a>

`TKey`
#### Parameters

<a name='Friflo.Engine.ECS.RelationExtensions.TryGetRelation_TRelation,TKey_(thisFriflo.Engine.ECS.Entity,TKey,TRelation).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

<a name='Friflo.Engine.ECS.RelationExtensions.TryGetRelation_TRelation,TKey_(thisFriflo.Engine.ECS.Entity,TKey,TRelation).key'></a>

`key` [TKey](RelationExtensions.TryGetRelation_TRelation,TKey_(thisEntity,TKey,TRelation).md#Friflo.Engine.ECS.RelationExtensions.TryGetRelation_TRelation,TKey_(thisFriflo.Engine.ECS.Entity,TKey,TRelation).TKey 'Friflo.Engine.ECS.RelationExtensions.TryGetRelation<TRelation,TKey>(this Friflo.Engine.ECS.Entity, TKey, TRelation).TKey')

<a name='Friflo.Engine.ECS.RelationExtensions.TryGetRelation_TRelation,TKey_(thisFriflo.Engine.ECS.Entity,TKey,TRelation).value'></a>

`value` [TRelation](RelationExtensions.TryGetRelation_TRelation,TKey_(thisEntity,TKey,TRelation).md#Friflo.Engine.ECS.RelationExtensions.TryGetRelation_TRelation,TKey_(thisFriflo.Engine.ECS.Entity,TKey,TRelation).TRelation 'Friflo.Engine.ECS.RelationExtensions.TryGetRelation<TRelation,TKey>(this Friflo.Engine.ECS.Entity, TKey, TRelation).TRelation')

#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')

#### Exceptions

[System.NullReferenceException](https://docs.microsoft.com/en-us/dotnet/api/System.NullReferenceException 'System.NullReferenceException')  
If the entity is null.