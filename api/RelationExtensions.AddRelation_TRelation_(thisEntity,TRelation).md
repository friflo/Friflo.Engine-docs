#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[RelationExtensions](RelationExtensions.md 'Friflo.Engine.ECS.RelationExtensions')

## RelationExtensions.AddRelation<TRelation>(this Entity, TRelation) Method

Add the relation with the specified [TRelation](RelationExtensions.AddRelation_TRelation_(thisEntity,TRelation).md#Friflo.Engine.ECS.RelationExtensions.AddRelation_TRelation_(thisFriflo.Engine.ECS.Entity,TRelation).TRelation 'Friflo.Engine.ECS.RelationExtensions.AddRelation<TRelation>(this Friflo.Engine.ECS.Entity, TRelation).TRelation') type to the entity.<br/>
Executes in O(1)

```csharp
public static bool AddRelation<TRelation>(this Friflo.Engine.ECS.Entity entity, in TRelation component)
    where TRelation : struct, Friflo.Engine.ECS.IRelation, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.RelationExtensions.AddRelation_TRelation_(thisFriflo.Engine.ECS.Entity,TRelation).TRelation'></a>

`TRelation`
#### Parameters

<a name='Friflo.Engine.ECS.RelationExtensions.AddRelation_TRelation_(thisFriflo.Engine.ECS.Entity,TRelation).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

<a name='Friflo.Engine.ECS.RelationExtensions.AddRelation_TRelation_(thisFriflo.Engine.ECS.Entity,TRelation).component'></a>

`component` [TRelation](RelationExtensions.AddRelation_TRelation_(thisEntity,TRelation).md#Friflo.Engine.ECS.RelationExtensions.AddRelation_TRelation_(thisFriflo.Engine.ECS.Entity,TRelation).TRelation 'Friflo.Engine.ECS.RelationExtensions.AddRelation<TRelation>(this Friflo.Engine.ECS.Entity, TRelation).TRelation')

#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
true - relation is newly added to the entity.<br/> false - relation is updated.

#### Exceptions

[System.NullReferenceException](https://docs.microsoft.com/en-us/dotnet/api/System.NullReferenceException 'System.NullReferenceException')  
If the entity is null.