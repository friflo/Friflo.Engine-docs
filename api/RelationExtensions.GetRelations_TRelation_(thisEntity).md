#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[RelationExtensions](RelationExtensions.md 'Friflo.Engine.ECS.RelationExtensions')

## RelationExtensions.GetRelations<TRelation>(this Entity) Method

Returns all unique relations of the passed [entity](RelationExtensions.GetRelations_TRelation_(thisEntity).md#Friflo.Engine.ECS.RelationExtensions.GetRelations_TRelation_(thisFriflo.Engine.ECS.Entity).entity 'Friflo.Engine.ECS.RelationExtensions.GetRelations<TRelation>(this Friflo.Engine.ECS.Entity).entity').<br/>
Executes in O(1). In case [TRelation](RelationExtensions.GetRelations_TRelation_(thisEntity).md#Friflo.Engine.ECS.RelationExtensions.GetRelations_TRelation_(thisFriflo.Engine.ECS.Entity).TRelation 'Friflo.Engine.ECS.RelationExtensions.GetRelations<TRelation>(this Friflo.Engine.ECS.Entity).TRelation') is a [ILinkRelation](ILinkRelation.md 'Friflo.Engine.ECS.ILinkRelation') it returns all linked entities.

```csharp
public static Friflo.Engine.ECS.Relations<TRelation> GetRelations<TRelation>(this Friflo.Engine.ECS.Entity entity)
    where TRelation : struct, Friflo.Engine.ECS.IRelation, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetRelations_TRelation_(thisFriflo.Engine.ECS.Entity).TRelation'></a>

`TRelation`
#### Parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetRelations_TRelation_(thisFriflo.Engine.ECS.Entity).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

#### Returns
[Friflo.Engine.ECS.Relations&lt;](Relations_TRelation_.md 'Friflo.Engine.ECS.Relations<TRelation>')[TRelation](RelationExtensions.GetRelations_TRelation_(thisEntity).md#Friflo.Engine.ECS.RelationExtensions.GetRelations_TRelation_(thisFriflo.Engine.ECS.Entity).TRelation 'Friflo.Engine.ECS.RelationExtensions.GetRelations<TRelation>(this Friflo.Engine.ECS.Entity).TRelation')[&gt;](Relations_TRelation_.md 'Friflo.Engine.ECS.Relations<TRelation>')

#### Exceptions

[System.NullReferenceException](https://docs.microsoft.com/en-us/dotnet/api/System.NullReferenceException 'System.NullReferenceException')  
If the entity is null.