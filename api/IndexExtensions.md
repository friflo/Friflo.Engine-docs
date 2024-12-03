#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## IndexExtensions Class

Provide extension methods to query all or specific component values.<br/>
Enables to query all or specific entity links (relationships).

```csharp
public static class IndexExtensions
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; IndexExtensions

| Methods | |
| :--- | :--- |
| [ComponentIndex&lt;TIndexedComponent,TValue&gt;(this EntityStore)](IndexExtensions.ComponentIndex_TIndexedComponent,TValue_(thisEntityStore).md 'Friflo.Engine.ECS.IndexExtensions.ComponentIndex<TIndexedComponent,TValue>(this Friflo.Engine.ECS.EntityStore)') | Returns the index for indexed components to search entities with a specific component value in O(1).<br/> Executes in O(1). |
| [GetAllIndexedComponentValues&lt;TComponent,TValue&gt;(this EntityStore)](IndexExtensions.GetAllIndexedComponentValues_TComponent,TValue_(thisEntityStore).md 'Friflo.Engine.ECS.IndexExtensions.GetAllIndexedComponentValues<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore)') | Obsolete: Use [Values](ComponentIndex_TIndexedComponent,TValue_.Values.md 'Friflo.Engine.ECS.ComponentIndex<TIndexedComponent,TValue>.Values')<br/> Returns all indexed component values of the passed [TComponent](IndexExtensions.GetAllIndexedComponentValues_TComponent,TValue_(thisEntityStore).md#Friflo.Engine.ECS.IndexExtensions.GetAllIndexedComponentValues_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore).TComponent 'Friflo.Engine.ECS.IndexExtensions.GetAllIndexedComponentValues<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore).TComponent') type.<br/> Executes in O(1). Each value in the returned list is unique. See remarks for additional infos. |
| [GetAllLinkedEntities&lt;TComponent&gt;(this EntityStore)](IndexExtensions.GetAllLinkedEntities_TComponent_(thisEntityStore).md 'Friflo.Engine.ECS.IndexExtensions.GetAllLinkedEntities<TComponent>(this Friflo.Engine.ECS.EntityStore)') | Obsolete: Use [Values](LinkComponentIndex_TLinkComponent_.Values.md 'Friflo.Engine.ECS.LinkComponentIndex<TLinkComponent>.Values')<br/> Returns all entities linked by the specified [ILinkComponent](ILinkComponent.md 'Friflo.Engine.ECS.ILinkComponent') type.<br/> Executes in O(1). Each entity in the returned list is unique. See remarks for additional infos. |
| [GetEntitiesWithComponentValue&lt;TComponent,TValue&gt;(this EntityStore, TValue)](IndexExtensions.GetEntitiesWithComponentValue_TComponent,TValue_(thisEntityStore,TValue).md 'Friflo.Engine.ECS.IndexExtensions.GetEntitiesWithComponentValue<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore, TValue)') | Obsolete: Use [this[TValue]](ComponentIndex_TIndexedComponent,TValue_.this[TValue].md 'Friflo.Engine.ECS.ComponentIndex<TIndexedComponent,TValue>.this[TValue]')<br/> Return the entities with the passed component value.<br/> Executes in O(1) with default index. |
| [GetIncomingLinks&lt;TComponent&gt;(this Entity)](IndexExtensions.GetIncomingLinks_TComponent_(thisEntity).md 'Friflo.Engine.ECS.IndexExtensions.GetIncomingLinks<TComponent>(this Friflo.Engine.ECS.Entity)') | Return the entities with a link component referencing the [target](IndexExtensions.GetIncomingLinks_TComponent_(thisEntity).md#Friflo.Engine.ECS.IndexExtensions.GetIncomingLinks_TComponent_(thisFriflo.Engine.ECS.Entity).target 'Friflo.Engine.ECS.IndexExtensions.GetIncomingLinks<TComponent>(this Friflo.Engine.ECS.Entity).target') entity of the passed [ILinkComponent](ILinkComponent.md 'Friflo.Engine.ECS.ILinkComponent') type.<br/> Executes in O(1). |
| [LinkComponentIndex&lt;TLinkComponent&gt;(this EntityStore)](IndexExtensions.LinkComponentIndex_TLinkComponent_(thisEntityStore).md 'Friflo.Engine.ECS.IndexExtensions.LinkComponentIndex<TLinkComponent>(this Friflo.Engine.ECS.EntityStore)') | Returns the index for link components to search entities with a specific entity in O(1).<br/> Executes in O(1). |
