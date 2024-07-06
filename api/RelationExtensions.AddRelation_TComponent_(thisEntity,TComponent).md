#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[RelationExtensions](RelationExtensions.md 'Friflo.Engine.ECS.RelationExtensions')

## RelationExtensions.AddRelation<TComponent>(this Entity, TComponent) Method

Add the relation component with the specified [TComponent](RelationExtensions.AddRelation_TComponent_(thisEntity,TComponent).md#Friflo.Engine.ECS.RelationExtensions.AddRelation_TComponent_(thisFriflo.Engine.ECS.Entity,TComponent).TComponent 'Friflo.Engine.ECS.RelationExtensions.AddRelation<TComponent>(this Friflo.Engine.ECS.Entity, TComponent).TComponent') type to the entity.<br/>
Executes in O(1)

```csharp
public static bool AddRelation<TComponent>(this Friflo.Engine.ECS.Entity entity, in TComponent component)
    where TComponent : struct, Friflo.Engine.ECS.IRelationComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.RelationExtensions.AddRelation_TComponent_(thisFriflo.Engine.ECS.Entity,TComponent).TComponent'></a>

`TComponent`
#### Parameters

<a name='Friflo.Engine.ECS.RelationExtensions.AddRelation_TComponent_(thisFriflo.Engine.ECS.Entity,TComponent).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

<a name='Friflo.Engine.ECS.RelationExtensions.AddRelation_TComponent_(thisFriflo.Engine.ECS.Entity,TComponent).component'></a>

`component` [TComponent](RelationExtensions.AddRelation_TComponent_(thisEntity,TComponent).md#Friflo.Engine.ECS.RelationExtensions.AddRelation_TComponent_(thisFriflo.Engine.ECS.Entity,TComponent).TComponent 'Friflo.Engine.ECS.RelationExtensions.AddRelation<TComponent>(this Friflo.Engine.ECS.Entity, TComponent).TComponent')

#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
true - relation is newly added to the entity.<br/> false - relation is updated.

#### Exceptions

[System.NullReferenceException](https://docs.microsoft.com/en-us/dotnet/api/System.NullReferenceException 'System.NullReferenceException')  
If the entity is null.