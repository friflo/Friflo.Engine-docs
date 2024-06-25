#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ILinkComponent Interface

Is used to define a component type having a link to another [Entity](Entity.md 'Friflo.Engine.ECS.Entity').

```csharp
public interface ILinkComponent :
Friflo.Engine.ECS.IIndexedComponent<Friflo.Engine.ECS.Entity>,
Friflo.Engine.ECS.IComponent
```

Implements [Friflo.Engine.ECS.IIndexedComponent&lt;](IIndexedComponent_TValue_.md 'Friflo.Engine.ECS.IIndexedComponent<TValue>')[Entity](Entity.md 'Friflo.Engine.ECS.Entity')[&gt;](IIndexedComponent_TValue_.md 'Friflo.Engine.ECS.IIndexedComponent<TValue>'), [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')

### Remarks
This component type enables:
- Return all entities having a [ILinkComponent](ILinkComponent.md 'Friflo.Engine.ECS.ILinkComponent') to a specific entity.<br/>
  See [GetLinkingEntities&lt;TComponent&gt;(this Entity)](IndexExtensions.GetLinkingEntities_TComponent_(thisEntity).md 'Friflo.Engine.ECS.IndexExtensions.GetLinkingEntities<TComponent>(this Friflo.Engine.ECS.Entity)')
- Return all entities linked by a specific [ILinkComponent](ILinkComponent.md 'Friflo.Engine.ECS.ILinkComponent') type.<br/>
  See [GetLinkedEntities&lt;TComponent&gt;()](EntityStore.GetLinkedEntities_TComponent_().md 'Friflo.Engine.ECS.EntityStore.GetLinkedEntities<TComponent>()')
- Filter entities in a query having a [ILinkComponent](ILinkComponent.md 'Friflo.Engine.ECS.ILinkComponent') to a specific entity.<br/>
  See [HasValue&lt;TComponent,TValue&gt;(TValue)](ArchetypeQuery.HasValue_TComponent,TValue_(TValue).md 'Friflo.Engine.ECS.ArchetypeQuery.HasValue<TComponent,TValue>(TValue)').