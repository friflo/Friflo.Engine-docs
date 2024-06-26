#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Index](Friflo.Engine.ECS.Index.md 'Friflo.Engine.ECS.Index').[IndexExtensions](IndexExtensions.md 'Friflo.Engine.ECS.Index.IndexExtensions')

## IndexExtensions.GetAllLinkedEntities<TComponent>(this EntityStore) Method

Returns all entities linked by the specified [ILinkComponent](ILinkComponent.md 'Friflo.Engine.ECS.Index.ILinkComponent') type.<br/>
Executes in O(1). Each entity in the returned list is unique. See remarks for additional infos.

```csharp
public static System.Collections.Generic.IReadOnlyCollection<Friflo.Engine.ECS.Entity> GetAllLinkedEntities<TComponent>(this Friflo.Engine.ECS.EntityStore store)
    where TComponent : struct, Friflo.Engine.ECS.Index.ILinkComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Index.IndexExtensions.GetAllLinkedEntities_TComponent_(thisFriflo.Engine.ECS.EntityStore).TComponent'></a>

`TComponent`
#### Parameters

<a name='Friflo.Engine.ECS.Index.IndexExtensions.GetAllLinkedEntities_TComponent_(thisFriflo.Engine.ECS.EntityStore).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

#### Returns
[System.Collections.Generic.IReadOnlyCollection&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')[Entity](Entity.md 'Friflo.Engine.ECS.Entity')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')

### Remarks
- The returned collection changes when component link values are updated, removed or added.
- To get the entities linking a specific entity use [GetEntityReferences&lt;TComponent&gt;(this Entity)](IndexExtensions.GetEntityReferences_TComponent_(thisEntity).md 'Friflo.Engine.ECS.Index.IndexExtensions.GetEntityReferences<TComponent>(this Friflo.Engine.ECS.Entity)').<br/>
- The method id a specialized version of [GetAllIndexedComponentValues&lt;TComponent,TValue&gt;(this EntityStore)](IndexExtensions.GetAllIndexedComponentValues_TComponent,TValue_(thisEntityStore).md 'Friflo.Engine.ECS.Index.IndexExtensions.GetAllIndexedComponentValues<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore)')<br/>
  using ` TComponent = ILinkComponent>` and `TValue = Entity`.