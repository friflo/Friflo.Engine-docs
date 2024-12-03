#### [Friflo.Engine.ECS](index.md 'index')

## Friflo.Engine.ECS.Index Namespace

Enables search for indexed component values in O(1) for types: string, int, enum, float, Guid, DateTime, ... . <br/>
Support efficient entity relationships like entity links (foreign keys) and back links (JOIN's).

| Classes | |
| :--- | :--- |
| [AbstractComponentIndex](AbstractComponentIndex.md 'Friflo.Engine.ECS.Index.AbstractComponentIndex') | Base class to enable implementing a custom component index.<br/> A custom component index can be implemented to optimize indexing or component queries for a specific component type. |
| [ComponentIndexAttribute](ComponentIndexAttribute.md 'Friflo.Engine.ECS.Index.ComponentIndexAttribute') | Assigns a custom [AbstractComponentIndex](AbstractComponentIndex.md 'Friflo.Engine.ECS.Index.AbstractComponentIndex') to an attributed component type. |
| [GenericComponentIndex&lt;TValue&gt;](GenericComponentIndex_TValue_.md 'Friflo.Engine.ECS.Index.GenericComponentIndex<TValue>') | Generic base class required to implement a custom component index. |
| [RangeIndex&lt;TIndexedComponent,TValue&gt;](RangeIndex_TIndexedComponent,TValue_.md 'Friflo.Engine.ECS.Index.RangeIndex<TIndexedComponent,TValue>') | A component index optimized to execute range queries in O(log N) at the cost of index updates in O(log N).<br/> The default index executes in O(1) when adding, removing or updating indexed component values. |
