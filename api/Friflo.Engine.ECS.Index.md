#### [Friflo.Engine.ECS](index.md 'index')

## Friflo.Engine.ECS.Index Namespace

Enables search for indexed component values in O(1) for types: string, int, enum, float, Guid, DateTime, ... . <br/>
Support efficient entity relationships like entity links (foreign keys) and back links (JOIN's).

| Classes | |
| :--- | :--- |
| [ComponentIndex](ComponentIndex.md 'Friflo.Engine.ECS.Index.ComponentIndex') | Base class to enable implementing a custom component index.<br/> A custom component index can be implemented to optimize indexing or component queries for a specific component type. |
| [ComponentIndex&lt;TValue&gt;](ComponentIndex_TValue_.md 'Friflo.Engine.ECS.Index.ComponentIndex<TValue>') | Generic base class required to implement a custom component index. |
| [ComponentIndexAttribute](ComponentIndexAttribute.md 'Friflo.Engine.ECS.Index.ComponentIndexAttribute') | Assigns a custom [ComponentIndex](ComponentIndex.md 'Friflo.Engine.ECS.Index.ComponentIndex') to an attributed component type. |
| [RangeIndex&lt;TValue&gt;](RangeIndex_TValue_.md 'Friflo.Engine.ECS.Index.RangeIndex<TValue>') | A component index optimized to execute range queries in O(log N) at the cost of index updates in O(log N).<br/> The default index executes in O(1) when adding, removing or updating indexed component values. |
