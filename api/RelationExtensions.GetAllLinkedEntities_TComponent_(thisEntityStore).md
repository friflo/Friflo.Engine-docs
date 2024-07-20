#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[RelationExtensions](RelationExtensions.md 'Friflo.Engine.ECS.RelationExtensions')

## RelationExtensions.GetAllLinkedEntities<TComponent>(this EntityStore) Method

```csharp
public static System.Collections.Generic.IReadOnlyCollection<Friflo.Engine.ECS.Entity> GetAllLinkedEntities<TComponent>(this Friflo.Engine.ECS.EntityStore store)
    where TComponent : struct, Friflo.Engine.ECS.IRelationComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetAllLinkedEntities_TComponent_(thisFriflo.Engine.ECS.EntityStore).TComponent'></a>

`TComponent`
#### Parameters

<a name='Friflo.Engine.ECS.RelationExtensions.GetAllLinkedEntities_TComponent_(thisFriflo.Engine.ECS.EntityStore).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

#### Returns
[System.Collections.Generic.IReadOnlyCollection&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')[Entity](Entity.md 'Friflo.Engine.ECS.Entity')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')