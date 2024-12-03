#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ILinkComponent Interface

A link component is a component type used to create a single link from one entity to another entity.<br/>
Specific component links can be queried with `HasValue()` in a `Query()`.

```csharp
public interface ILinkComponent :
Friflo.Engine.ECS.IIndexedComponent<Friflo.Engine.ECS.Entity>,
Friflo.Engine.ECS.IComponent
```

Implements [Friflo.Engine.ECS.IIndexedComponent&lt;](IIndexedComponent_TValue_.md 'Friflo.Engine.ECS.IIndexedComponent<TValue>')[Entity](Entity.md 'Friflo.Engine.ECS.Entity')[&gt;](IIndexedComponent_TValue_.md 'Friflo.Engine.ECS.IIndexedComponent<TValue>'), [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')

### Remarks
This component type enables:
- Add a component link to an entity using [AddComponent&lt;T&gt;()](Entity.AddComponent_T_().md 'Friflo.Engine.ECS.Entity.AddComponent<T>()').
- Return all entities having a [ILinkComponent](ILinkComponent.md 'Friflo.Engine.ECS.ILinkComponent') to a specific entity.<br/>
  See [GetIncomingLinks&lt;TComponent&gt;(this Entity)](IndexExtensions.GetIncomingLinks_TComponent_(thisEntity).md 'Friflo.Engine.ECS.IndexExtensions.GetIncomingLinks<TComponent>(this Friflo.Engine.ECS.Entity)')
- Return all entities linked by a specific [ILinkComponent](ILinkComponent.md 'Friflo.Engine.ECS.ILinkComponent') type.<br/>
  See [Values](LinkComponentIndex_TLinkComponent_.Values.md 'Friflo.Engine.ECS.LinkComponentIndex<TLinkComponent>.Values')
- Filter entities in a query having a [ILinkComponent](ILinkComponent.md 'Friflo.Engine.ECS.ILinkComponent') to a specific entity.<br/>
  See [HasValue&lt;TComponent,TValue&gt;(TValue)](ArchetypeQuery.HasValue_TComponent,TValue_(TValue).md 'Friflo.Engine.ECS.ArchetypeQuery.HasValue<TComponent,TValue>(TValue)').