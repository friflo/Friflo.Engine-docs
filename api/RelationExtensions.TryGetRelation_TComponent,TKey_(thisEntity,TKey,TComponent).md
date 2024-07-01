#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[RelationExtensions](RelationExtensions.md 'Friflo.Engine.ECS.RelationExtensions')

## RelationExtensions.TryGetRelation<TComponent,TKey>(this Entity, TKey, TComponent) Method

Returns the relation of the [entity](RelationExtensions.TryGetRelation_TComponent,TKey_(thisEntity,TKey,TComponent).md#Friflo.Engine.ECS.RelationExtensions.TryGetRelation_TComponent,TKey_(thisFriflo.Engine.ECS.Entity,TKey,TComponent).entity 'Friflo.Engine.ECS.RelationExtensions.TryGetRelation<TComponent,TKey>(this Friflo.Engine.ECS.Entity, TKey, TComponent).entity') with the given [key](RelationExtensions.TryGetRelation_TComponent,TKey_(thisEntity,TKey,TComponent).md#Friflo.Engine.ECS.RelationExtensions.TryGetRelation_TComponent,TKey_(thisFriflo.Engine.ECS.Entity,TKey,TComponent).key 'Friflo.Engine.ECS.RelationExtensions.TryGetRelation<TComponent,TKey>(this Friflo.Engine.ECS.Entity, TKey, TComponent).key').<br/>
Executes in O(N) N: number of entity relations.

```csharp
public static bool TryGetRelation<TComponent,TKey>(this Friflo.Engine.ECS.Entity entity, TKey key, out TComponent value)
    where TComponent : struct, Friflo.Engine.ECS.IRelationComponent<TKey>, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.RelationExtensions.TryGetRelation_TComponent,TKey_(thisFriflo.Engine.ECS.Entity,TKey,TComponent).TComponent'></a>

`TComponent`

<a name='Friflo.Engine.ECS.RelationExtensions.TryGetRelation_TComponent,TKey_(thisFriflo.Engine.ECS.Entity,TKey,TComponent).TKey'></a>

`TKey`
#### Parameters

<a name='Friflo.Engine.ECS.RelationExtensions.TryGetRelation_TComponent,TKey_(thisFriflo.Engine.ECS.Entity,TKey,TComponent).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

<a name='Friflo.Engine.ECS.RelationExtensions.TryGetRelation_TComponent,TKey_(thisFriflo.Engine.ECS.Entity,TKey,TComponent).key'></a>

`key` [TKey](RelationExtensions.TryGetRelation_TComponent,TKey_(thisEntity,TKey,TComponent).md#Friflo.Engine.ECS.RelationExtensions.TryGetRelation_TComponent,TKey_(thisFriflo.Engine.ECS.Entity,TKey,TComponent).TKey 'Friflo.Engine.ECS.RelationExtensions.TryGetRelation<TComponent,TKey>(this Friflo.Engine.ECS.Entity, TKey, TComponent).TKey')

<a name='Friflo.Engine.ECS.RelationExtensions.TryGetRelation_TComponent,TKey_(thisFriflo.Engine.ECS.Entity,TKey,TComponent).value'></a>

`value` [TComponent](RelationExtensions.TryGetRelation_TComponent,TKey_(thisEntity,TKey,TComponent).md#Friflo.Engine.ECS.RelationExtensions.TryGetRelation_TComponent,TKey_(thisFriflo.Engine.ECS.Entity,TKey,TComponent).TComponent 'Friflo.Engine.ECS.RelationExtensions.TryGetRelation<TComponent,TKey>(this Friflo.Engine.ECS.Entity, TKey, TComponent).TComponent')

#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')