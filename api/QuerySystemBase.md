#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Systems](Friflo.Engine.ECS.Systems.md 'Friflo.Engine.ECS.Systems')

## QuerySystemBase Class

A query system returning the components specified in a subclass extending `QuerySystem<T1, ... , Tn>`.

```csharp
public abstract class QuerySystemBase : Friflo.Engine.ECS.Systems.BaseSystem
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; [BaseSystem](BaseSystem.md 'Friflo.Engine.ECS.Systems.BaseSystem') &#129106; QuerySystemBase

Derived  
&#8627; [QuerySystem](QuerySystem.md 'Friflo.Engine.ECS.Systems.QuerySystem')  
&#8627; [QuerySystem&lt;T1,T2,T3,T4,T5&gt;](QuerySystem_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1,T2,T3,T4,T5>')  
&#8627; [QuerySystem&lt;T1,T2,T3,T4&gt;](QuerySystem_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1,T2,T3,T4>')  
&#8627; [QuerySystem&lt;T1,T2,T3&gt;](QuerySystem_T1,T2,T3_.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1,T2,T3>')  
&#8627; [QuerySystem&lt;T1,T2&gt;](QuerySystem_T1,T2_.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1,T2>')  
&#8627; [QuerySystem&lt;T1&gt;](QuerySystem_T1_.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1>')

| Properties | |
| :--- | :--- |
| [CommandBuffer](QuerySystemBase.CommandBuffer.md 'Friflo.Engine.ECS.Systems.QuerySystemBase.CommandBuffer') | Return the [CommandBuffer](QuerySystemBase.CommandBuffer.md 'Friflo.Engine.ECS.Systems.QuerySystemBase.CommandBuffer') of its [ParentGroup](BaseSystem.ParentGroup.md 'Friflo.Engine.ECS.Systems.BaseSystem.ParentGroup'). |
| [ComponentTypes](QuerySystemBase.ComponentTypes.md 'Friflo.Engine.ECS.Systems.QuerySystemBase.ComponentTypes') | The component types of components returned by its `Query` property. |
| [EntityCount](QuerySystemBase.EntityCount.md 'Friflo.Engine.ECS.Systems.QuerySystemBase.EntityCount') | The number of entities matching the `Query`. |
| [Filter](QuerySystemBase.Filter.md 'Friflo.Engine.ECS.Systems.QuerySystemBase.Filter') | A query filter used to restrict the entities returned by its `Query` property.<br/> See remarks to add a tag filter to a custom `QuerySystem`. |
| [Queries](QuerySystemBase.Queries.md 'Friflo.Engine.ECS.Systems.QuerySystemBase.Queries') | Return all system queries. One per store in [Stores](SystemRoot.Stores.md 'Friflo.Engine.ECS.Systems.SystemRoot.Stores'). |

| Methods | |
| :--- | :--- |
| [OnAddStore(EntityStore)](QuerySystemBase.OnAddStore(EntityStore).md 'Friflo.Engine.ECS.Systems.QuerySystemBase.OnAddStore(Friflo.Engine.ECS.EntityStore)') | |
| [OnRemoveStore(EntityStore)](QuerySystemBase.OnRemoveStore(EntityStore).md 'Friflo.Engine.ECS.Systems.QuerySystemBase.OnRemoveStore(Friflo.Engine.ECS.EntityStore)') | |
| [OnUpdate()](QuerySystemBase.OnUpdate().md 'Friflo.Engine.ECS.Systems.QuerySystemBase.OnUpdate()') | Called for every query in [Queries](QuerySystemBase.Queries.md 'Friflo.Engine.ECS.Systems.QuerySystemBase.Queries'). |
| [OnUpdateGroup()](QuerySystemBase.OnUpdateGroup().md 'Friflo.Engine.ECS.Systems.QuerySystemBase.OnUpdateGroup()') | |
