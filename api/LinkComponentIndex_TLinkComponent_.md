#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## LinkComponentIndex<TLinkComponent> Struct

The index for [ILinkComponent](ILinkComponent.md 'Friflo.Engine.ECS.ILinkComponent') struct's to search entities with a specific entity in O(1).

```csharp
public readonly struct LinkComponentIndex<TLinkComponent>
    where TLinkComponent : struct, Friflo.Engine.ECS.ILinkComponent, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.LinkComponentIndex_TLinkComponent_.TLinkComponent'></a>

`TLinkComponent`

| Properties | |
| :--- | :--- |
| [this[Entity]](LinkComponentIndex_TLinkComponent_.this[Entity].md 'Friflo.Engine.ECS.LinkComponentIndex<TLinkComponent>.this[Friflo.Engine.ECS.Entity]') | Return the entities having a link component with the passed component value.<br/> Executes in O(1) with default index. |
| [Values](LinkComponentIndex_TLinkComponent_.Values.md 'Friflo.Engine.ECS.LinkComponentIndex<TLinkComponent>.Values') | Returns all indexed link component values of the passed[Entity](Entity.md 'Friflo.Engine.ECS.Entity') type.<br/> Executes in O(1). Each value in the returned list is unique. See remarks for additional infos. |

| Methods | |
| :--- | :--- |
| [ToString()](LinkComponentIndex_TLinkComponent_.ToString().md 'Friflo.Engine.ECS.LinkComponentIndex<TLinkComponent>.ToString()') | |
