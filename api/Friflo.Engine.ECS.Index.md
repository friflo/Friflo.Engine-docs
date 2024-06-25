#### [Friflo.Engine.ECS](index.md 'index')

## Friflo.Engine.ECS.Index Namespace

Enables search for indexed component values in O(1) for types: string, int, enum, float, Guid, DateTime, ... . <br/>
Support efficient entity relationships like entity links (foreign keys) and back links (JOIN's).

| Classes | |
| :--- | :--- |
| [ComponentIndex](ComponentIndex.md 'Friflo.Engine.ECS.Index.ComponentIndex') | |
| [ComponentIndex&lt;TValue&gt;](ComponentIndex_TValue_.md 'Friflo.Engine.ECS.Index.ComponentIndex<TValue>') | |
| [IndexExtensions](IndexExtensions.md 'Friflo.Engine.ECS.Index.IndexExtensions') | |
| [RangeIndex&lt;TValue&gt;](RangeIndex_TValue_.md 'Friflo.Engine.ECS.Index.RangeIndex<TValue>') | |

| Interfaces | |
| :--- | :--- |
| [IIndexedComponent&lt;TValue&gt;](IIndexedComponent_TValue_.md 'Friflo.Engine.ECS.Index.IIndexedComponent<TValue>') | Is used to define a component type having a single indexed field / property. |
| [ILinkComponent](ILinkComponent.md 'Friflo.Engine.ECS.Index.ILinkComponent') | Is used to define a component type having a link to another [Entity](Entity.md 'Friflo.Engine.ECS.Entity'). |
