#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[IndexExtensions](IndexExtensions.md 'Friflo.Engine.ECS.IndexExtensions')

## IndexExtensions.GetAllLinkedEntities<TComponent>(this EntityStore) Method

Obsolete: Use [Values](LinkComponentIndex_TLinkComponent_.Values.md 'Friflo.Engine.ECS.LinkComponentIndex<TLinkComponent>.Values')<br/>
Returns all entities linked by the specified [ILinkComponent](ILinkComponent.md 'Friflo.Engine.ECS.ILinkComponent') type.<br/>
Executes in O(1). Each entity in the returned list is unique. See remarks for additional infos.

```csharp
public static System.Collections.Generic.IReadOnlyCollection<Friflo.Engine.ECS.Entity> GetAllLinkedEntities<TComponent>(this Friflo.Engine.ECS.EntityStore store)
    where TComponent : struct, Friflo.Engine.ECS.ILinkComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.IndexExtensions.GetAllLinkedEntities_TComponent_(thisFriflo.Engine.ECS.EntityStore).TComponent'></a>

`TComponent`
#### Parameters

<a name='Friflo.Engine.ECS.IndexExtensions.GetAllLinkedEntities_TComponent_(thisFriflo.Engine.ECS.EntityStore).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

#### Returns
[System.Collections.Generic.IReadOnlyCollection&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')[Entity](Entity.md 'Friflo.Engine.ECS.Entity')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')

### Remarks
- The returned collection changes when component link values are updated, removed or added.
- To get the entities linking a specific entity use [GetIncomingLinks&lt;TComponent&gt;(this Entity)](IndexExtensions.GetIncomingLinks_TComponent_(thisEntity).md 'Friflo.Engine.ECS.IndexExtensions.GetIncomingLinks<TComponent>(this Friflo.Engine.ECS.Entity)').<br/>
- The method is a specialized version of [Values](ComponentIndex_TIndexedComponent,TValue_.Values.md 'Friflo.Engine.ECS.ComponentIndex<TIndexedComponent,TValue>.Values')<br/>
  using ` TIndexedComponent = ILinkComponent` and `TValue = Entity`.