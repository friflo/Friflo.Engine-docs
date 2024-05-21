#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Systems](Friflo.Engine.ECS.Systems.md 'Friflo.Engine.ECS.Systems')

## QuerySystem Class

A query system returning the components specified in a subclass extending `QuerySystem<T1, ... , Tn>`.

```csharp
public abstract class QuerySystem : Friflo.Engine.ECS.Systems.BaseSystem
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; [BaseSystem](BaseSystem.md 'Friflo.Engine.ECS.Systems.BaseSystem') &#129106; QuerySystem

Derived  
&#8627; [QuerySystem&lt;T1,T2,T3,T4,T5&gt;](QuerySystem_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1,T2,T3,T4,T5>')  
&#8627; [QuerySystem&lt;T1,T2,T3,T4&gt;](QuerySystem_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1,T2,T3,T4>')  
&#8627; [QuerySystem&lt;T1,T2,T3&gt;](QuerySystem_T1,T2,T3_.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1,T2,T3>')  
&#8627; [QuerySystem&lt;T1,T2&gt;](QuerySystem_T1,T2_.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1,T2>')  
&#8627; [QuerySystem&lt;T1&gt;](QuerySystem_T1_.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1>')

| Properties | |
| :--- | :--- |
| [CommandBuffer](QuerySystem.CommandBuffer.md 'Friflo.Engine.ECS.Systems.QuerySystem.CommandBuffer') | Return the [CommandBuffer](QuerySystem.CommandBuffer.md 'Friflo.Engine.ECS.Systems.QuerySystem.CommandBuffer') of its [ParentGroup](BaseSystem.ParentGroup.md 'Friflo.Engine.ECS.Systems.BaseSystem.ParentGroup'). |
| [ComponentTypes](QuerySystem.ComponentTypes.md 'Friflo.Engine.ECS.Systems.QuerySystem.ComponentTypes') | The component types of components returned by its `Query` property. |
| [EntityCount](QuerySystem.EntityCount.md 'Friflo.Engine.ECS.Systems.QuerySystem.EntityCount') | The number of entities matching the `Query`. |
| [Filter](QuerySystem.Filter.md 'Friflo.Engine.ECS.Systems.QuerySystem.Filter') | A query filter used to restrict the entities returned by its `Query` property. |
| [Queries](QuerySystem.Queries.md 'Friflo.Engine.ECS.Systems.QuerySystem.Queries') | Return all system queries. One per store in [Stores](SystemRoot.Stores.md 'Friflo.Engine.ECS.Systems.SystemRoot.Stores'). |

| Methods | |
| :--- | :--- |
| [OnUpdate()](QuerySystem.OnUpdate().md 'Friflo.Engine.ECS.Systems.QuerySystem.OnUpdate()') | Called for every query in [Queries](QuerySystem.Queries.md 'Friflo.Engine.ECS.Systems.QuerySystem.Queries'). |
| [OnUpdateGroup()](QuerySystem.OnUpdateGroup().md 'Friflo.Engine.ECS.Systems.QuerySystem.OnUpdateGroup()') | |
