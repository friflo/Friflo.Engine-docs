#### [Friflo.Engine.ECS](index.md 'index')

## Friflo.Engine.ECS.Systems Namespace

Used to organize and execute a set of systems within a [SystemRoot](SystemRoot.md 'Friflo.Engine.ECS.Systems.SystemRoot').

| Classes | |
| :--- | :--- |
| [BaseSystem](BaseSystem.md 'Friflo.Engine.ECS.Systems.BaseSystem') | Base class for all systems either a query system, a custom system or a system group. |
| [QuerySystem](QuerySystem.md 'Friflo.Engine.ECS.Systems.QuerySystem') | A query system returning the components specified in a subclass extending `QuerySystem<T1, ... , Tn>`. |
| [QuerySystem&lt;T1,T2,T3,T4,T5&gt;](QuerySystem_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1,T2,T3,T4,T5>') | A query system returning entities with the specified component types via its [Query](QuerySystem_T1,T2,T3,T4,T5_.Query.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1,T2,T3,T4,T5>.Query') property. |
| [QuerySystem&lt;T1,T2,T3,T4&gt;](QuerySystem_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1,T2,T3,T4>') | A query system returning entities with the specified component types via its [Query](QuerySystem_T1,T2,T3,T4_.Query.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1,T2,T3,T4>.Query') property. |
| [QuerySystem&lt;T1,T2,T3&gt;](QuerySystem_T1,T2,T3_.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1,T2,T3>') | A query system returning entities with the specified component types via its [Query](QuerySystem_T1,T2,T3_.Query.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1,T2,T3>.Query') property. |
| [QuerySystem&lt;T1,T2&gt;](QuerySystem_T1,T2_.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1,T2>') | A query system returning entities with the specified component types via its [Query](QuerySystem_T1,T2_.Query.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1,T2>.Query') property. |
| [QuerySystem&lt;T1&gt;](QuerySystem_T1_.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1>') | A query system returning entities with the specified component type via its [Query](QuerySystem_T1_.Query.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1>.Query') property. |
| [SystemExtensions](SystemExtensions.md 'Friflo.Engine.ECS.Systems.SystemExtensions') | Contains System extension methods. |
| [SystemGroup](SystemGroup.md 'Friflo.Engine.ECS.Systems.SystemGroup') | Contains a list of [ChildSystems](SystemGroup.ChildSystems.md 'Friflo.Engine.ECS.Systems.SystemGroup.ChildSystems') which are executed by calling [Update(UpdateTick)](SystemGroup.Update(UpdateTick).md 'Friflo.Engine.ECS.Systems.SystemGroup.Update(Friflo.Engine.ECS.UpdateTick)'). <br/> Each group has a [CommandBuffer](CommandBuffer.md 'Friflo.Engine.ECS.CommandBuffer') per [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore'). |
| [SystemRoot](SystemRoot.md 'Friflo.Engine.ECS.Systems.SystemRoot') | A [SystemRoot](SystemRoot.md 'Friflo.Engine.ECS.Systems.SystemRoot') setup a system hierarchy required to execute systems with [Update(UpdateTick)](SystemGroup.Update(UpdateTick).md 'Friflo.Engine.ECS.Systems.SystemGroup.Update(Friflo.Engine.ECS.UpdateTick)'). |

| Structs | |
| :--- | :--- |
| [SystemChanged](SystemChanged.md 'Friflo.Engine.ECS.Systems.SystemChanged') | The event for event handlers added to [OnSystemChanged](BaseSystem.OnSystemChanged.md 'Friflo.Engine.ECS.Systems.BaseSystem.OnSystemChanged'). |
| [SystemMatch](SystemMatch.md 'Friflo.Engine.ECS.Systems.SystemMatch') | Information of a matching system returned by [GetMatchingSystems(this SystemGroup, Archetype, List&lt;SystemMatch&gt;, bool)](SystemExtensions.GetMatchingSystems(thisSystemGroup,Archetype,List_SystemMatch_,bool).md 'Friflo.Engine.ECS.Systems.SystemExtensions.GetMatchingSystems(this Friflo.Engine.ECS.Systems.SystemGroup, Friflo.Engine.ECS.Archetype, System.Collections.Generic.List<Friflo.Engine.ECS.Systems.SystemMatch>, bool)'). |
| [SystemPerf](SystemPerf.md 'Friflo.Engine.ECS.Systems.SystemPerf') | Provide performance statistics of system execution via the system property [Perf](BaseSystem.Perf.md 'Friflo.Engine.ECS.Systems.BaseSystem.Perf'). |

| Enums | |
| :--- | :--- |
| [SystemChangedAction](SystemChangedAction.md 'Friflo.Engine.ECS.Systems.SystemChangedAction') | The type of [SystemChanged](SystemChanged.md 'Friflo.Engine.ECS.Systems.SystemChanged') event. <br/> See: [Remove](SystemChangedAction.md#Friflo.Engine.ECS.Systems.SystemChangedAction.Remove 'Friflo.Engine.ECS.Systems.SystemChangedAction.Remove'), [Add](SystemChangedAction.md#Friflo.Engine.ECS.Systems.SystemChangedAction.Add 'Friflo.Engine.ECS.Systems.SystemChangedAction.Add'), [Move](SystemChangedAction.md#Friflo.Engine.ECS.Systems.SystemChangedAction.Move 'Friflo.Engine.ECS.Systems.SystemChangedAction.Move') or [Update](SystemChangedAction.md#Friflo.Engine.ECS.Systems.SystemChangedAction.Update 'Friflo.Engine.ECS.Systems.SystemChangedAction.Update') a system. |
