#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Index](Friflo.Engine.ECS.Index.md 'Friflo.Engine.ECS.Index')

## IndexExtensions Class

Provide extension methods to query all or a specific component values.<br/>
Enables to query all or a specific entity links (relationships).

```csharp
public static class IndexExtensions
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; IndexExtensions

| Methods | |
| :--- | :--- |
| [GetEntitiesWithComponentValue&lt;TComponent,TValue&gt;(this EntityStore, TValue)](IndexExtensions.GetEntitiesWithComponentValue_TComponent,TValue_(thisEntityStore,TValue).md 'Friflo.Engine.ECS.Index.IndexExtensions.GetEntitiesWithComponentValue<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore, TValue)') | Return the entities with the passed component value.<br/> Executes in O(1) with default index. |
| [GetIndexedComponentValues&lt;TComponent,TValue&gt;(this EntityStore)](IndexExtensions.GetIndexedComponentValues_TComponent,TValue_(thisEntityStore).md 'Friflo.Engine.ECS.Index.IndexExtensions.GetIndexedComponentValues<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore)') | Returns a collection of all indexed component values of the passed [TComponent](IndexExtensions.GetIndexedComponentValues_TComponent,TValue_(thisEntityStore).md#Friflo.Engine.ECS.Index.IndexExtensions.GetIndexedComponentValues_TComponent,TValue_(thisFriflo.Engine.ECS.EntityStore).TComponent 'Friflo.Engine.ECS.Index.IndexExtensions.GetIndexedComponentValues<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore).TComponent') type.<br/> Executes in O(1). Each value in the returned list is unique. See remarks for additional infos. |
| [GetLinkedEntities&lt;TComponent&gt;(this EntityStore)](IndexExtensions.GetLinkedEntities_TComponent_(thisEntityStore).md 'Friflo.Engine.ECS.Index.IndexExtensions.GetLinkedEntities<TComponent>(this Friflo.Engine.ECS.EntityStore)') | Returns all entities linked by the specified [ILinkComponent](ILinkComponent.md 'Friflo.Engine.ECS.Index.ILinkComponent') type.<br/> Executes in O(1). Each entity in the returned list is unique. See remarks for additional infos. |
| [GetLinkingEntities&lt;TComponent&gt;(this Entity)](IndexExtensions.GetLinkingEntities_TComponent_(thisEntity).md 'Friflo.Engine.ECS.Index.IndexExtensions.GetLinkingEntities<TComponent>(this Friflo.Engine.ECS.Entity)') | Return the entities having a component link to this entity of the passed [ILinkComponent](ILinkComponent.md 'Friflo.Engine.ECS.Index.ILinkComponent') type.<br/> Executes in O(1). |
