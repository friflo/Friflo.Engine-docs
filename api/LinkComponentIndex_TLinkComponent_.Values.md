#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[LinkComponentIndex&lt;TLinkComponent&gt;](LinkComponentIndex_TLinkComponent_.md 'Friflo.Engine.ECS.LinkComponentIndex<TLinkComponent>')

## LinkComponentIndex<TLinkComponent>.Values Property

Returns all indexed link component values of the passed[Entity](Entity.md 'Friflo.Engine.ECS.Entity') type.<br/>
Executes in O(1). Each value in the returned list is unique. See remarks for additional infos.

```csharp
public System.Collections.Generic.IReadOnlyCollection<Friflo.Engine.ECS.Entity> Values { get; }
```

#### Property Value
[System.Collections.Generic.IReadOnlyCollection&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')[Entity](Entity.md 'Friflo.Engine.ECS.Entity')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1 'System.Collections.Generic.IReadOnlyCollection`1')

### Remarks
- The returned collection changes when indexed component values are updated, removed or added.
- To get the entities having a specific component value use [this[Entity]](LinkComponentIndex_TLinkComponent_.this[Entity].md 'Friflo.Engine.ECS.LinkComponentIndex<TLinkComponent>.this[Friflo.Engine.ECS.Entity]').