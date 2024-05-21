#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Systems](Friflo.Engine.ECS.Systems.md 'Friflo.Engine.ECS.Systems')

## SystemRoot Class

A [SystemRoot](SystemRoot.md 'Friflo.Engine.ECS.Systems.SystemRoot') setup a system hierarchy required to execute systems with [Update(UpdateTick)](SystemGroup.Update(UpdateTick).md 'Friflo.Engine.ECS.Systems.SystemGroup.Update(Friflo.Engine.ECS.UpdateTick)').

```csharp
public class SystemRoot : Friflo.Engine.ECS.Systems.SystemGroup
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; [BaseSystem](BaseSystem.md 'Friflo.Engine.ECS.Systems.BaseSystem') &#129106; [SystemGroup](SystemGroup.md 'Friflo.Engine.ECS.Systems.SystemGroup') &#129106; SystemRoot

| Constructors | |
| :--- | :--- |
| [SystemRoot(EntityStore, string)](SystemRoot.SystemRoot(EntityStore,string).md 'Friflo.Engine.ECS.Systems.SystemRoot.SystemRoot(Friflo.Engine.ECS.EntityStore, string)') | Create a root system for the specified [entityStore](SystemRoot.SystemRoot(EntityStore,string).md#Friflo.Engine.ECS.Systems.SystemRoot.SystemRoot(Friflo.Engine.ECS.EntityStore,string).entityStore 'Friflo.Engine.ECS.Systems.SystemRoot.SystemRoot(Friflo.Engine.ECS.EntityStore, string).entityStore'). |
| [SystemRoot(string)](SystemRoot.SystemRoot(string).md 'Friflo.Engine.ECS.Systems.SystemRoot.SystemRoot(string)') | Create a root system without an [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore'). |

| Properties | |
| :--- | :--- |
| [Stores](SystemRoot.Stores.md 'Friflo.Engine.ECS.Systems.SystemRoot.Stores') | Returns the [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')'s added to the root system. |

| Methods | |
| :--- | :--- |
| [AddStore(EntityStore)](SystemRoot.AddStore(EntityStore).md 'Friflo.Engine.ECS.Systems.SystemRoot.AddStore(Friflo.Engine.ECS.EntityStore)') | Adds the passed [entityStore](SystemRoot.AddStore(EntityStore).md#Friflo.Engine.ECS.Systems.SystemRoot.AddStore(Friflo.Engine.ECS.EntityStore).entityStore 'Friflo.Engine.ECS.Systems.SystemRoot.AddStore(Friflo.Engine.ECS.EntityStore).entityStore') to the root system. |
| [RemoveStore(EntityStore)](SystemRoot.RemoveStore(EntityStore).md 'Friflo.Engine.ECS.Systems.SystemRoot.RemoveStore(Friflo.Engine.ECS.EntityStore)') | Removed the passed [entityStore](SystemRoot.RemoveStore(EntityStore).md#Friflo.Engine.ECS.Systems.SystemRoot.RemoveStore(Friflo.Engine.ECS.EntityStore).entityStore 'Friflo.Engine.ECS.Systems.SystemRoot.RemoveStore(Friflo.Engine.ECS.EntityStore).entityStore') from the root system. |
| [ToString()](SystemRoot.ToString().md 'Friflo.Engine.ECS.Systems.SystemRoot.ToString()') | |
