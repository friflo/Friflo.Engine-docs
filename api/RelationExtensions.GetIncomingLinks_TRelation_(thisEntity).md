#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[RelationExtensions](RelationExtensions.md 'Friflo.Engine.ECS.RelationExtensions')

## RelationExtensions.GetIncomingLinks<TRelation>(this Entity) Method

Return the entities with a link relation referencing the [target](RelationExtensions.GetIncomingLinks_TRelation_(thisEntity).md#Friflo.Engine.ECS.RelationExtensions.GetIncomingLinks_TRelation_(thisFriflo.Engine.ECS.Entity).target 'Friflo.Engine.ECS.RelationExtensions.GetIncomingLinks<TRelation>(this Friflo.Engine.ECS.Entity).target') entity of the passed [IRelation](IRelation.md 'Friflo.Engine.ECS.IRelation') type.<br/>
Executes in O(1).

```csharp
public static Friflo.Engine.ECS.EntityLinks<TRelation> GetIncomingLinks<TRelation>(this Friflo.Engine.ECS.Entity target)
    where TRelation : struct, Friflo.Engine.ECS.ILinkRelation, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetIncomingLinks_TRelation_(thisFriflo.Engine.ECS.Entity).TRelation'></a>

`TRelation`
#### Parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetIncomingLinks_TRelation_(thisFriflo.Engine.ECS.Entity).target'></a>

`target` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

#### Returns
[Friflo.Engine.ECS.EntityLinks&lt;](EntityLinks_T_.md 'Friflo.Engine.ECS.EntityLinks<T>')[TRelation](RelationExtensions.GetIncomingLinks_TRelation_(thisEntity).md#Friflo.Engine.ECS.RelationExtensions.GetIncomingLinks_TRelation_(thisFriflo.Engine.ECS.Entity).TRelation 'Friflo.Engine.ECS.RelationExtensions.GetIncomingLinks<TRelation>(this Friflo.Engine.ECS.Entity).TRelation')[&gt;](EntityLinks_T_.md 'Friflo.Engine.ECS.EntityLinks<T>')

#### Exceptions

[System.NullReferenceException](https://docs.microsoft.com/en-us/dotnet/api/System.NullReferenceException 'System.NullReferenceException')  
If the entity is null.