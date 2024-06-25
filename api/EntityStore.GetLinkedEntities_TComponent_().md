#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

## EntityStore.GetLinkedEntities<TComponent>() Method

Returns all entities linked by the specified [ILinkComponent](ILinkComponent.md 'Friflo.Engine.ECS.ILinkComponent') type.<br/>
Executes in O(1). Each entity in the returned list is unique. See remarks for additional infos.

```csharp
public System.Collections.Generic.IReadOnlyCollection<Friflo.Engine.ECS.Entity> GetLinkedEntities<TComponent>()
    where TComponent : struct, Friflo.Engine.ECS.ILinkComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityStore.GetLinkedEntities_TComponent_().TComponent'></a>

`TComponent`

#### Returns
[System.Collections.Generic.IReadOnlyCollection&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')[Entity](Entity.md 'Friflo.Engine.ECS.Entity')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')

### Remarks
- The collection changes when component link values are updated, removed or added.
- To get the entities linking a specific entity use [GetLinkingEntities&lt;TComponent&gt;(this Entity)](IndexExtensions.GetLinkingEntities_TComponent_(thisEntity).md 'Friflo.Engine.ECS.IndexExtensions.GetLinkingEntities<TComponent>(this Friflo.Engine.ECS.Entity)').<br/>
- The method id a specialized version of [GetIndexedComponentValues&lt;TComponent,TValue&gt;()](EntityStore.GetIndexedComponentValues_TComponent,TValue_().md 'Friflo.Engine.ECS.EntityStore.GetIndexedComponentValues<TComponent,TValue>()')<br/>
  using ` TComponent = ILinkComponent>` and `TValue = Entity`.