#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[RelationExtensions](RelationExtensions.md 'Friflo.Engine.ECS.RelationExtensions')

## RelationExtensions.GetAllLinkedEntities<TRelation>(this EntityStore) Method

```csharp
public static System.Collections.Generic.IReadOnlyCollection<Friflo.Engine.ECS.Entity> GetAllLinkedEntities<TRelation>(this Friflo.Engine.ECS.EntityStore store)
    where TRelation : struct, Friflo.Engine.ECS.IRelation, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetAllLinkedEntities_TRelation_(thisFriflo.Engine.ECS.EntityStore).TRelation'></a>

`TRelation`
#### Parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetAllLinkedEntities_TRelation_(thisFriflo.Engine.ECS.EntityStore).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

#### Returns
[System.Collections.Generic.IReadOnlyCollection&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')[Entity](Entity.md 'Friflo.Engine.ECS.Entity')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')