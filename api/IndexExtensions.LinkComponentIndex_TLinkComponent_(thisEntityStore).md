#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[IndexExtensions](IndexExtensions.md 'Friflo.Engine.ECS.IndexExtensions')

## IndexExtensions.LinkComponentIndex<TLinkComponent>(this EntityStore) Method

Returns the index for link components to search entities with a specific entity in O(1).<br/>
Executes in O(1).

```csharp
public static Friflo.Engine.ECS.LinkComponentIndex<TLinkComponent> LinkComponentIndex<TLinkComponent>(this Friflo.Engine.ECS.EntityStore store)
    where TLinkComponent : struct, Friflo.Engine.ECS.ILinkComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.IndexExtensions.LinkComponentIndex_TLinkComponent_(thisFriflo.Engine.ECS.EntityStore).TLinkComponent'></a>

`TLinkComponent`
#### Parameters

<a name='Friflo.Engine.ECS.IndexExtensions.LinkComponentIndex_TLinkComponent_(thisFriflo.Engine.ECS.EntityStore).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

#### Returns
[Friflo.Engine.ECS.LinkComponentIndex&lt;](LinkComponentIndex_TLinkComponent_.md 'Friflo.Engine.ECS.LinkComponentIndex<TLinkComponent>')[TLinkComponent](IndexExtensions.LinkComponentIndex_TLinkComponent_(thisEntityStore).md#Friflo.Engine.ECS.IndexExtensions.LinkComponentIndex_TLinkComponent_(thisFriflo.Engine.ECS.EntityStore).TLinkComponent 'Friflo.Engine.ECS.IndexExtensions.LinkComponentIndex<TLinkComponent>(this Friflo.Engine.ECS.EntityStore).TLinkComponent')[&gt;](LinkComponentIndex_TLinkComponent_.md 'Friflo.Engine.ECS.LinkComponentIndex<TLinkComponent>')