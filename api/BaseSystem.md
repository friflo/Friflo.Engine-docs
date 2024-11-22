#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Systems](Friflo.Engine.ECS.Systems.md 'Friflo.Engine.ECS.Systems')

## BaseSystem Class

Base class for all systems either a query system, a custom system or a system group.

```csharp
public abstract class BaseSystem
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; BaseSystem

Derived  
&#8627; [QuerySystemBase](QuerySystemBase.md 'Friflo.Engine.ECS.Systems.QuerySystemBase')  
&#8627; [SystemGroup](SystemGroup.md 'Friflo.Engine.ECS.Systems.SystemGroup')

| Properties | |
| :--- | :--- |
| [Enabled](BaseSystem.Enabled.md 'Friflo.Engine.ECS.Systems.BaseSystem.Enabled') | If true the system is executed when calling [Update(UpdateTick)](SystemGroup.Update(UpdateTick).md 'Friflo.Engine.ECS.Systems.SystemGroup.Update(Friflo.Engine.ECS.UpdateTick)') |
| [Id](BaseSystem.Id.md 'Friflo.Engine.ECS.Systems.BaseSystem.Id') | Unique system id of all systems of a [SystemRoot](BaseSystem.SystemRoot.md 'Friflo.Engine.ECS.Systems.BaseSystem.SystemRoot'). |
| [Name](BaseSystem.Name.md 'Friflo.Engine.ECS.Systems.BaseSystem.Name') | The system name. The Name of a [SystemGroup](SystemGroup.md 'Friflo.Engine.ECS.Systems.SystemGroup') can be changed. |
| [ParentGroup](BaseSystem.ParentGroup.md 'Friflo.Engine.ECS.Systems.BaseSystem.ParentGroup') | The parent [SystemGroup](SystemGroup.md 'Friflo.Engine.ECS.Systems.SystemGroup') containing this system. |
| [Perf](BaseSystem.Perf.md 'Friflo.Engine.ECS.Systems.BaseSystem.Perf') | Provide execution statistics of a system if [MonitorPerf](SystemGroup.MonitorPerf.md 'Friflo.Engine.ECS.Systems.SystemGroup.MonitorPerf') is enabled. |
| [SystemRoot](BaseSystem.SystemRoot.md 'Friflo.Engine.ECS.Systems.BaseSystem.SystemRoot') | The [SystemRoot](BaseSystem.SystemRoot.md 'Friflo.Engine.ECS.Systems.BaseSystem.SystemRoot') containing this system. |
| [Tick](BaseSystem.Tick.md 'Friflo.Engine.ECS.Systems.BaseSystem.Tick') | The [UpdateTick](UpdateTick.md 'Friflo.Engine.ECS.UpdateTick') passed to [Update(UpdateTick)](SystemGroup.Update(UpdateTick).md 'Friflo.Engine.ECS.Systems.SystemGroup.Update(Friflo.Engine.ECS.UpdateTick)'). |

| Methods | |
| :--- | :--- |
| [AppendPerfLog(StringBuilder)](BaseSystem.AppendPerfLog(StringBuilder).md 'Friflo.Engine.ECS.Systems.BaseSystem.AppendPerfLog(System.Text.StringBuilder)') | Add performance statistics formatted as a table to the given [System.Text.StringBuilder](https://docs.microsoft.com/en-us/dotnet/api/System.Text.StringBuilder 'System.Text.StringBuilder') without memory allocations. |
| [CastSystemUpdate(string, object)](BaseSystem.CastSystemUpdate(string,object).md 'Friflo.Engine.ECS.Systems.BaseSystem.CastSystemUpdate(string, object)') | Send an event to [OnSystemChanged](BaseSystem.OnSystemChanged.md 'Friflo.Engine.ECS.Systems.BaseSystem.OnSystemChanged') handlers to notify a changed system [field](BaseSystem.CastSystemUpdate(string,object).md#Friflo.Engine.ECS.Systems.BaseSystem.CastSystemUpdate(string,object).field 'Friflo.Engine.ECS.Systems.BaseSystem.CastSystemUpdate(string, object).field'). |
| [GetPerfLog()](BaseSystem.GetPerfLog().md 'Friflo.Engine.ECS.Systems.BaseSystem.GetPerfLog()') | Returns performance statistics formatted as a table intended for logging. |
| [MoveSystemTo(SystemGroup, int)](BaseSystem.MoveSystemTo(SystemGroup,int).md 'Friflo.Engine.ECS.Systems.BaseSystem.MoveSystemTo(Friflo.Engine.ECS.Systems.SystemGroup, int)') | Move the system to the specified [targetGroup](BaseSystem.MoveSystemTo(SystemGroup,int).md#Friflo.Engine.ECS.Systems.BaseSystem.MoveSystemTo(Friflo.Engine.ECS.Systems.SystemGroup,int).targetGroup 'Friflo.Engine.ECS.Systems.BaseSystem.MoveSystemTo(Friflo.Engine.ECS.Systems.SystemGroup, int).targetGroup') at the given [index](BaseSystem.MoveSystemTo(SystemGroup,int).md#Friflo.Engine.ECS.Systems.BaseSystem.MoveSystemTo(Friflo.Engine.ECS.Systems.SystemGroup,int).index 'Friflo.Engine.ECS.Systems.BaseSystem.MoveSystemTo(Friflo.Engine.ECS.Systems.SystemGroup, int).index').<br/> If [index](BaseSystem.MoveSystemTo(SystemGroup,int).md#Friflo.Engine.ECS.Systems.BaseSystem.MoveSystemTo(Friflo.Engine.ECS.Systems.SystemGroup,int).index 'Friflo.Engine.ECS.Systems.BaseSystem.MoveSystemTo(Friflo.Engine.ECS.Systems.SystemGroup, int).index') is -1 the system is moved to the tail of the group. |
| [OnAddStore(EntityStore)](BaseSystem.OnAddStore(EntityStore).md 'Friflo.Engine.ECS.Systems.BaseSystem.OnAddStore(Friflo.Engine.ECS.EntityStore)') | |
| [OnRemoveStore(EntityStore)](BaseSystem.OnRemoveStore(EntityStore).md 'Friflo.Engine.ECS.Systems.BaseSystem.OnRemoveStore(Friflo.Engine.ECS.EntityStore)') | |
| [OnUpdateGroup()](BaseSystem.OnUpdateGroup().md 'Friflo.Engine.ECS.Systems.BaseSystem.OnUpdateGroup()') | Called for every system of the parent [ChildSystems](SystemGroup.ChildSystems.md 'Friflo.Engine.ECS.Systems.SystemGroup.ChildSystems'). |
| [OnUpdateGroupBegin()](BaseSystem.OnUpdateGroupBegin().md 'Friflo.Engine.ECS.Systems.BaseSystem.OnUpdateGroupBegin()') | Called for every system of the parent [ChildSystems](SystemGroup.ChildSystems.md 'Friflo.Engine.ECS.Systems.SystemGroup.ChildSystems') before group [OnUpdateGroup()](SystemGroup.OnUpdateGroup().md 'Friflo.Engine.ECS.Systems.SystemGroup.OnUpdateGroup()'). |
| [OnUpdateGroupEnd()](BaseSystem.OnUpdateGroupEnd().md 'Friflo.Engine.ECS.Systems.BaseSystem.OnUpdateGroupEnd()') | Called for every system of the parent [ChildSystems](SystemGroup.ChildSystems.md 'Friflo.Engine.ECS.Systems.SystemGroup.ChildSystems') after group [OnUpdateGroup()](SystemGroup.OnUpdateGroup().md 'Friflo.Engine.ECS.Systems.SystemGroup.OnUpdateGroup()'). |

| Events | |
| :--- | :--- |
| [OnSystemChanged](BaseSystem.OnSystemChanged.md 'Friflo.Engine.ECS.Systems.BaseSystem.OnSystemChanged') | Event handlers to notify a system has changed.<br/> Like a changed system field or a system added / removed to / from a [SystemGroup](SystemGroup.md 'Friflo.Engine.ECS.Systems.SystemGroup'). |
