#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[RelationExtensions](RelationExtensions.md 'Friflo.Engine.ECS.RelationExtensions')

## RelationExtensions.GetIncomingLinks<TComponent>(this Entity) Method

Return the entities with a link relation referencing the [target](RelationExtensions.GetIncomingLinks_TComponent_(thisEntity).md#Friflo.Engine.ECS.RelationExtensions.GetIncomingLinks_TComponent_(thisFriflo.Engine.ECS.Entity).target 'Friflo.Engine.ECS.RelationExtensions.GetIncomingLinks<TComponent>(this Friflo.Engine.ECS.Entity).target') entity of the passed [IRelationComponent](IRelationComponent.md 'Friflo.Engine.ECS.IRelationComponent') type.<br/>
Executes in O(1).

```csharp
public static Friflo.Engine.ECS.EntityLinks<TComponent> GetIncomingLinks<TComponent>(this Friflo.Engine.ECS.Entity target)
    where TComponent : struct, Friflo.Engine.ECS.ILinkRelation, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetIncomingLinks_TComponent_(thisFriflo.Engine.ECS.Entity).TComponent'></a>

`TComponent`
#### Parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetIncomingLinks_TComponent_(thisFriflo.Engine.ECS.Entity).target'></a>

`target` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

#### Returns
[Friflo.Engine.ECS.EntityLinks&lt;](EntityLinks_T_.md 'Friflo.Engine.ECS.EntityLinks<T>')[TComponent](RelationExtensions.GetIncomingLinks_TComponent_(thisEntity).md#Friflo.Engine.ECS.RelationExtensions.GetIncomingLinks_TComponent_(thisFriflo.Engine.ECS.Entity).TComponent 'Friflo.Engine.ECS.RelationExtensions.GetIncomingLinks<TComponent>(this Friflo.Engine.ECS.Entity).TComponent')[&gt;](EntityLinks_T_.md 'Friflo.Engine.ECS.EntityLinks<T>')

#### Exceptions

[System.NullReferenceException](https://docs.microsoft.com/en-us/dotnet/api/System.NullReferenceException 'System.NullReferenceException')  
If the entity is null.