#### [Friflo.Engine.ECS](index.md 'index')

## Friflo.Engine.ECS.Index Namespace

Enables search for indexed component values in O(1) for types: string, int, enum, float, Guid, DateTime, ... . <br/>
Support efficient entity relationships like entity links (foreign keys) and back links (JOIN's).

| Classes | |
| :--- | :--- |
| [ComponentIndex](ComponentIndex.md 'Friflo.Engine.ECS.Index.ComponentIndex') | Base class to enable implementing a custom component index.<br/> A custom component index can be implemented to optimize indexing or component queries for a specific component type. |
| [ComponentIndex&lt;TValue&gt;](ComponentIndex_TValue_.md 'Friflo.Engine.ECS.Index.ComponentIndex<TValue>') | Generic base class required to implement a custom component index. |
| [ComponentIndexAttribute](ComponentIndexAttribute.md 'Friflo.Engine.ECS.Index.ComponentIndexAttribute') | Assigns a custom [ComponentIndex](ComponentIndex.md 'Friflo.Engine.ECS.Index.ComponentIndex') to an attributed component type. |
| [IndexExtensions](IndexExtensions.md 'Friflo.Engine.ECS.Index.IndexExtensions') | Provide extension methods to query all or specific component values.<br/> Enables to query all or specific entity links (relationships). |
| [RangeIndex&lt;TValue&gt;](RangeIndex_TValue_.md 'Friflo.Engine.ECS.Index.RangeIndex<TValue>') | A component index optimized to execute range queries in O(log N) at the cost of index updates in O(log N).<br/> The default index executes in O(1) when adding, removing or updating indexed component values. |

| Interfaces | |
| :--- | :--- |
| [IIndexedComponent&lt;TValue&gt;](IIndexedComponent_TValue_.md 'Friflo.Engine.ECS.Index.IIndexedComponent<TValue>') | Is used to define a component type having a single indexed field / property.<br/> Indexed component values can be queried with `HasValue()` or `ValueInRange() in a Query().` |
| [ILinkComponent](ILinkComponent.md 'Friflo.Engine.ECS.Index.ILinkComponent') | Is used to define a component type having a link relationship to another [Entity](Entity.md 'Friflo.Engine.ECS.Entity').<br/> Specific component links can be queried with `HasValue()` in a `Query()`. |
