#### [Friflo.Engine.ECS](index.md 'index')

## Friflo.Engine.ECS.Index Namespace

Enables search for indexed component values in O(1) for types: string, int, enum, float, Guid, DateTime, ... . <br/>
Support efficient entity relationships like entity links (foreign keys) and back links (JOIN's).

| Classes | |
| :--- | :--- |
| [ComponentIndex](ComponentIndex.md 'Friflo.Engine.ECS.Index.ComponentIndex') | Base class to enable implementing custom component indexes. |
| [ComponentIndex&lt;TValue&gt;](ComponentIndex_TValue_.md 'Friflo.Engine.ECS.Index.ComponentIndex<TValue>') | Generic base class required to implement custom component indexes. |
| [IndexExtensions](IndexExtensions.md 'Friflo.Engine.ECS.Index.IndexExtensions') | Provide extension methods to query all or a specific component values.<br/> Enables to query all or a specific entity links (relationships). |
| [RangeIndex&lt;TValue&gt;](RangeIndex_TValue_.md 'Friflo.Engine.ECS.Index.RangeIndex<TValue>') | A component index optimized to execute range queries in O(log N) at the cost of index updates in O(log N).<br/> The default index executed index updates in O(1): |

| Interfaces | |
| :--- | :--- |
| [IIndexedComponent&lt;TValue&gt;](IIndexedComponent_TValue_.md 'Friflo.Engine.ECS.Index.IIndexedComponent<TValue>') | Is used to define a component type having a single indexed field / property. |
| [ILinkComponent](ILinkComponent.md 'Friflo.Engine.ECS.Index.ILinkComponent') | Is used to define a component type having a link relationship to another [Entity](Entity.md 'Friflo.Engine.ECS.Entity'). |
