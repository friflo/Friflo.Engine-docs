#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Systems](Friflo.Engine.ECS.Systems.md 'Friflo.Engine.ECS.Systems')

## SystemGroup Class

Contains a list of [ChildSystems](SystemGroup.ChildSystems.md 'Friflo.Engine.ECS.Systems.SystemGroup.ChildSystems') which are executed by calling [Update(UpdateTick)](SystemGroup.Update(UpdateTick).md 'Friflo.Engine.ECS.Systems.SystemGroup.Update(Friflo.Engine.ECS.UpdateTick)'). <br/>
Each group has a [CommandBuffer](CommandBuffer.md 'Friflo.Engine.ECS.CommandBuffer') per [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore').

```csharp
public class SystemGroup : Friflo.Engine.ECS.Systems.BaseSystem,
System.Collections.IEnumerable
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; [BaseSystem](BaseSystem.md 'Friflo.Engine.ECS.Systems.BaseSystem') &#129106; SystemGroup

Derived  
&#8627; [SystemRoot](SystemRoot.md 'Friflo.Engine.ECS.Systems.SystemRoot')

Implements [System.Collections.IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerable 'System.Collections.IEnumerable')

| Constructors | |
| :--- | :--- |
| [SystemGroup(string)](SystemGroup.SystemGroup(string).md 'Friflo.Engine.ECS.Systems.SystemGroup.SystemGroup(string)') | Creates a group with the passed [name](SystemGroup.SystemGroup(string).md#Friflo.Engine.ECS.Systems.SystemGroup.SystemGroup(string).name 'Friflo.Engine.ECS.Systems.SystemGroup.SystemGroup(string).name'). |

| Properties | |
| :--- | :--- |
| [ChildSystems](SystemGroup.ChildSystems.md 'Friflo.Engine.ECS.Systems.SystemGroup.ChildSystems') | The child systems added to the group. |
| [MonitorPerf](SystemGroup.MonitorPerf.md 'Friflo.Engine.ECS.Systems.SystemGroup.MonitorPerf') | If true the execution statics of its [ChildSystems](SystemGroup.ChildSystems.md 'Friflo.Engine.ECS.Systems.SystemGroup.ChildSystems') are collected. |
| [Name](SystemGroup.Name.md 'Friflo.Engine.ECS.Systems.SystemGroup.Name') | The name of the group. Can be changed by [SetName(string)](SystemGroup.SetName(string).md 'Friflo.Engine.ECS.Systems.SystemGroup.SetName(string)'). |

| Methods | |
| :--- | :--- |
| [Add(BaseSystem)](SystemGroup.Add(BaseSystem).md 'Friflo.Engine.ECS.Systems.SystemGroup.Add(Friflo.Engine.ECS.Systems.BaseSystem)') | Adds the passed [system](SystemGroup.Add(BaseSystem).md#Friflo.Engine.ECS.Systems.SystemGroup.Add(Friflo.Engine.ECS.Systems.BaseSystem).system 'Friflo.Engine.ECS.Systems.SystemGroup.Add(Friflo.Engine.ECS.Systems.BaseSystem).system') to the group. |
| [FindGroup(string, bool)](SystemGroup.FindGroup(string,bool).md 'Friflo.Engine.ECS.Systems.SystemGroup.FindGroup(string, bool)') | Returns the group with the specified [name](SystemGroup.FindGroup(string,bool).md#Friflo.Engine.ECS.Systems.SystemGroup.FindGroup(string,bool).name 'Friflo.Engine.ECS.Systems.SystemGroup.FindGroup(string, bool).name'). |
| [FindSystem&lt;T&gt;(bool)](SystemGroup.FindSystem_T_(bool).md 'Friflo.Engine.ECS.Systems.SystemGroup.FindSystem<T>(bool)') | Returns the system with of the specified type [T](SystemGroup.FindSystem_T_(bool).md#Friflo.Engine.ECS.Systems.SystemGroup.FindSystem_T_(bool).T 'Friflo.Engine.ECS.Systems.SystemGroup.FindSystem<T>(bool).T'). |
| [GetEnumerator()](SystemGroup.GetEnumerator().md 'Friflo.Engine.ECS.Systems.SystemGroup.GetEnumerator()') | Returns an enumerator that iterates through the [ChildSystems](SystemGroup.ChildSystems.md 'Friflo.Engine.ECS.Systems.SystemGroup.ChildSystems'). |
| [Insert(int, BaseSystem)](SystemGroup.Insert(int,BaseSystem).md 'Friflo.Engine.ECS.Systems.SystemGroup.Insert(int, Friflo.Engine.ECS.Systems.BaseSystem)') | Adds the passed [system](SystemGroup.Insert(int,BaseSystem).md#Friflo.Engine.ECS.Systems.SystemGroup.Insert(int,Friflo.Engine.ECS.Systems.BaseSystem).system 'Friflo.Engine.ECS.Systems.SystemGroup.Insert(int, Friflo.Engine.ECS.Systems.BaseSystem).system') at the given [index](SystemGroup.Insert(int,BaseSystem).md#Friflo.Engine.ECS.Systems.SystemGroup.Insert(int,Friflo.Engine.ECS.Systems.BaseSystem).index 'Friflo.Engine.ECS.Systems.SystemGroup.Insert(int, Friflo.Engine.ECS.Systems.BaseSystem).index') to the group.<br/> If [index](SystemGroup.Insert(int,BaseSystem).md#Friflo.Engine.ECS.Systems.SystemGroup.Insert(int,Friflo.Engine.ECS.Systems.BaseSystem).index 'Friflo.Engine.ECS.Systems.SystemGroup.Insert(int, Friflo.Engine.ECS.Systems.BaseSystem).index') == -1 the system is added to the tail of the group. |
| [IsAncestorOf(BaseSystem)](SystemGroup.IsAncestorOf(BaseSystem).md 'Friflo.Engine.ECS.Systems.SystemGroup.IsAncestorOf(Friflo.Engine.ECS.Systems.BaseSystem)') | Returns true if the group is an ancestor of the passed [system](SystemGroup.IsAncestorOf(BaseSystem).md#Friflo.Engine.ECS.Systems.SystemGroup.IsAncestorOf(Friflo.Engine.ECS.Systems.BaseSystem).system 'Friflo.Engine.ECS.Systems.SystemGroup.IsAncestorOf(Friflo.Engine.ECS.Systems.BaseSystem).system'). |
| [OnAddStore(EntityStore)](SystemGroup.OnAddStore(EntityStore).md 'Friflo.Engine.ECS.Systems.SystemGroup.OnAddStore(Friflo.Engine.ECS.EntityStore)') | |
| [OnRemoveStore(EntityStore)](SystemGroup.OnRemoveStore(EntityStore).md 'Friflo.Engine.ECS.Systems.SystemGroup.OnRemoveStore(Friflo.Engine.ECS.EntityStore)') | |
| [OnUpdateGroup()](SystemGroup.OnUpdateGroup().md 'Friflo.Engine.ECS.Systems.SystemGroup.OnUpdateGroup()') | Is called when executing [Update(UpdateTick)](SystemGroup.Update(UpdateTick).md 'Friflo.Engine.ECS.Systems.SystemGroup.Update(Friflo.Engine.ECS.UpdateTick)'). |
| [Remove(BaseSystem)](SystemGroup.Remove(BaseSystem).md 'Friflo.Engine.ECS.Systems.SystemGroup.Remove(Friflo.Engine.ECS.Systems.BaseSystem)') | Removes the passed [system](SystemGroup.Remove(BaseSystem).md#Friflo.Engine.ECS.Systems.SystemGroup.Remove(Friflo.Engine.ECS.Systems.BaseSystem).system 'Friflo.Engine.ECS.Systems.SystemGroup.Remove(Friflo.Engine.ECS.Systems.BaseSystem).system') from the group. |
| [SetMonitorPerf(bool)](SystemGroup.SetMonitorPerf(bool).md 'Friflo.Engine.ECS.Systems.SystemGroup.SetMonitorPerf(bool)') | Enable / disable performance monitoring of its [ChildSystems](SystemGroup.ChildSystems.md 'Friflo.Engine.ECS.Systems.SystemGroup.ChildSystems'). |
| [SetName(string)](SystemGroup.SetName(string).md 'Friflo.Engine.ECS.Systems.SystemGroup.SetName(string)') | Changes the name of the system group. |
| [ToString()](SystemGroup.ToString().md 'Friflo.Engine.ECS.Systems.SystemGroup.ToString()') | |
| [Update(UpdateTick)](SystemGroup.Update(UpdateTick).md 'Friflo.Engine.ECS.Systems.SystemGroup.Update(Friflo.Engine.ECS.UpdateTick)') | Execute all systems within the group. |

| Explicit Interface Implementations | |
| :--- | :--- |
| [System.Collections.IEnumerable.GetEnumerator()](SystemGroup.System.Collections.IEnumerable.GetEnumerator().md 'Friflo.Engine.ECS.Systems.SystemGroup.System.Collections.IEnumerable.GetEnumerator()') | |
