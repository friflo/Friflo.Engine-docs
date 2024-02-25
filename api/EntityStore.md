#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## EntityStore Class

An [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') is a container for [Entity](Entity.md 'Friflo.Engine.ECS.Entity')'s their components, scripts, tags
and the tree structure.<br/>
See <a href="https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md#entitystore">Example.</a>

```csharp
public sealed class EntityStore : Friflo.Engine.ECS.EntityStoreBase
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; [EntityStoreBase](EntityStoreBase.md 'Friflo.Engine.ECS.EntityStoreBase') &#129106; EntityStore

### Remarks
The [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') provide the features listed below
- Store a map (container) of entities in linear memory.<br/>
  Entity data can retrieved by entity <b>id</b> using the property [GetEntityById(int)](EntityStore.GetEntityById(int).md 'Friflo.Engine.ECS.EntityStore.GetEntityById(int)').<br/>[Entity](Entity.md 'Friflo.Engine.ECS.Entity')'s have the states below:<br/>
  - [StoreOwnership](StoreOwnership.md 'Friflo.Engine.ECS.StoreOwnership'): [attached](StoreOwnership.md#Friflo.Engine.ECS.StoreOwnership.attached 'Friflo.Engine.ECS.StoreOwnership.attached') / [detached](StoreOwnership.md#Friflo.Engine.ECS.StoreOwnership.detached 'Friflo.Engine.ECS.StoreOwnership.detached')<br/>
                      if [detached](StoreOwnership.md#Friflo.Engine.ECS.StoreOwnership.detached 'Friflo.Engine.ECS.StoreOwnership.detached') - [System.NullReferenceException](https://docs.microsoft.com/en-us/dotnet/api/System.NullReferenceException 'System.NullReferenceException') are thrown by [Entity](Entity.md 'Friflo.Engine.ECS.Entity') properties and methods.
  - [TreeMembership](TreeMembership.md 'Friflo.Engine.ECS.TreeMembership'): [treeNode](TreeMembership.md#Friflo.Engine.ECS.TreeMembership.treeNode 'Friflo.Engine.ECS.TreeMembership.treeNode') / [floating](TreeMembership.md#Friflo.Engine.ECS.TreeMembership.floating 'Friflo.Engine.ECS.TreeMembership.floating') node (not part of the [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') tree graph).<br/>
                      All children of a [treeNode](TreeMembership.md#Friflo.Engine.ECS.TreeMembership.treeNode 'Friflo.Engine.ECS.TreeMembership.treeNode') are [treeNode](TreeMembership.md#Friflo.Engine.ECS.TreeMembership.treeNode 'Friflo.Engine.ECS.TreeMembership.treeNode')'s themselves.
- Manage a tree graph of entities which starts with the [StoreRoot](EntityStore.StoreRoot.md 'Friflo.Engine.ECS.EntityStore.StoreRoot') entity to build up a scene graph.
- Store the data of [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')'s and [Script](Script.md 'Friflo.Engine.ECS.Script')'s.

| Constructors | |
| :--- | :--- |
| [EntityStore()](EntityStore.EntityStore().md 'Friflo.Engine.ECS.EntityStore.EntityStore()') | |
| [EntityStore(PidType)](EntityStore.EntityStore(PidType).md 'Friflo.Engine.ECS.EntityStore.EntityStore(Friflo.Engine.ECS.PidType)') | |

| Fields | |
| :--- | :--- |
| [Info](EntityStore.Info.md 'Friflo.Engine.ECS.EntityStore.Info') | |

| Properties | |
| :--- | :--- |
| [Capacity](EntityStore.Capacity.md 'Friflo.Engine.ECS.EntityStore.Capacity') | |
| [Entities](EntityStore.Entities.md 'Friflo.Engine.ECS.EntityStore.Entities') | Return all [Entity](Entity.md 'Friflo.Engine.ECS.Entity')'s stored in the [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore'). |
| [EntityScripts](EntityStore.EntityScripts.md 'Friflo.Engine.ECS.EntityStore.EntityScripts') | Return all [Script](Script.md 'Friflo.Engine.ECS.Script')'s added to [Entity](Entity.md 'Friflo.Engine.ECS.Entity')'s in the [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore'). |
| [EventRecorder](EntityStore.EventRecorder.md 'Friflo.Engine.ECS.EntityStore.EventRecorder') | Record adding/removing of components/tags to/from entities if [Enabled](EventRecorder.Enabled.md 'Friflo.Engine.ECS.EventRecorder.Enabled') is true.<br/> It is required to filter these events using an [EventFilter](EventFilter.md 'Friflo.Engine.ECS.EventFilter'). |
| [StoreRoot](EntityStore.StoreRoot.md 'Friflo.Engine.ECS.EntityStore.StoreRoot') | Return the root [Entity](Entity.md 'Friflo.Engine.ECS.Entity') of the store. |

| Methods | |
| :--- | :--- |
| [CastEntitiesChanged(object, EntitiesChanged)](EntityStore.CastEntitiesChanged(object,EntitiesChanged).md 'Friflo.Engine.ECS.EntityStore.CastEntitiesChanged(object, Friflo.Engine.ECS.EntitiesChanged)') | |
| [CloneEntity(Entity)](EntityStore.CloneEntity(Entity).md 'Friflo.Engine.ECS.EntityStore.CloneEntity(Friflo.Engine.ECS.Entity)') | Create and return a clone of the of the passed [entity](EntityStore.CloneEntity(Entity).md#Friflo.Engine.ECS.EntityStore.CloneEntity(Friflo.Engine.ECS.Entity).entity 'Friflo.Engine.ECS.EntityStore.CloneEntity(Friflo.Engine.ECS.Entity).entity') in the store. |
| [CreateEntity()](EntityStore.CreateEntity().md 'Friflo.Engine.ECS.EntityStore.CreateEntity()') | Create and return a new [Entity](Entity.md 'Friflo.Engine.ECS.Entity') in the entity store.<br/> See <a href="https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md#entity">Example.</a> |
| [CreateEntity(int)](EntityStore.CreateEntity(int).md 'Friflo.Engine.ECS.EntityStore.CreateEntity(int)') | Create and return new [Entity](Entity.md 'Friflo.Engine.ECS.Entity') with the passed [id](EntityStore.CreateEntity(int).md#Friflo.Engine.ECS.EntityStore.CreateEntity(int).id 'Friflo.Engine.ECS.EntityStore.CreateEntity(int).id') in the entity store. |
| [EnsureCapacity(int)](EntityStore.EnsureCapacity(int).md 'Friflo.Engine.ECS.EntityStore.EnsureCapacity(int)') | Allocates memory for entities in the store to enable creating entities without reallocation. |
| [GetCommandBuffer()](EntityStore.GetCommandBuffer().md 'Friflo.Engine.ECS.EntityStore.GetCommandBuffer()') | Returns a [CommandBuffer](CommandBuffer.md 'Friflo.Engine.ECS.CommandBuffer') used to record and [Playback()](CommandBuffer.Playback().md 'Friflo.Engine.ECS.CommandBuffer.Playback()') entity changes. |
| [GetEntityById(int)](EntityStore.GetEntityById(int).md 'Friflo.Engine.ECS.EntityStore.GetEntityById(int)') | Return the [Entity](Entity.md 'Friflo.Engine.ECS.Entity') with the passed entity [id](EntityStore.GetEntityById(int).md#Friflo.Engine.ECS.EntityStore.GetEntityById(int).id 'Friflo.Engine.ECS.EntityStore.GetEntityById(int).id'). |
| [GetEntityByPid(long)](EntityStore.GetEntityByPid(long).md 'Friflo.Engine.ECS.EntityStore.GetEntityByPid(long)') | Return the [Entity](Entity.md 'Friflo.Engine.ECS.Entity') with the passed entity [pid](EntityStore.GetEntityByPid(long).md#Friflo.Engine.ECS.EntityStore.GetEntityByPid(long).pid 'Friflo.Engine.ECS.EntityStore.GetEntityByPid(long).pid'). |
| [GetEntityNode(int)](EntityStore.GetEntityNode(int).md 'Friflo.Engine.ECS.EntityStore.GetEntityNode(int)') | Return the internal node for the passed entity [id](EntityStore.GetEntityNode(int).md#Friflo.Engine.ECS.EntityStore.GetEntityNode(int).id 'Friflo.Engine.ECS.EntityStore.GetEntityNode(int).id'). |
| [GetEntitySchema()](EntityStore.GetEntitySchema().md 'Friflo.Engine.ECS.EntityStore.GetEntitySchema()') | Return the [EntitySchema](EntitySchema.md 'Friflo.Engine.ECS.EntitySchema') containing all available [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent'), [ITag](ITag.md 'Friflo.Engine.ECS.ITag') and [Script](Script.md 'Friflo.Engine.ECS.Script') types. |
| [IdToPid(int)](EntityStore.IdToPid(int).md 'Friflo.Engine.ECS.EntityStore.IdToPid(int)') | Return the [Pid](Entity.Pid.md 'Friflo.Engine.ECS.Entity.Pid') for the passed entity [id](EntityStore.IdToPid(int).md#Friflo.Engine.ECS.EntityStore.IdToPid(int).id 'Friflo.Engine.ECS.EntityStore.IdToPid(int).id'). |
| [PidToId(long)](EntityStore.PidToId(long).md 'Friflo.Engine.ECS.EntityStore.PidToId(long)') | Return the [Id](Entity.Id.md 'Friflo.Engine.ECS.Entity.Id') for the passed entity [pid](EntityStore.PidToId(long).md#Friflo.Engine.ECS.EntityStore.PidToId(long).pid 'Friflo.Engine.ECS.EntityStore.PidToId(long).pid'). |
| [SetRandomSeed(int)](EntityStore.SetRandomSeed(int).md 'Friflo.Engine.ECS.EntityStore.SetRandomSeed(int)') | Set the seed used to create random entity [Pid](Entity.Pid.md 'Friflo.Engine.ECS.Entity.Pid')'s for an entity store <br/> created with [PidType](PidType.md 'Friflo.Engine.ECS.PidType') == [RandomPids](PidType.md#Friflo.Engine.ECS.PidType.RandomPids 'Friflo.Engine.ECS.PidType.RandomPids'). |
| [SetStoreRoot(Entity)](EntityStore.SetStoreRoot(Entity).md 'Friflo.Engine.ECS.EntityStore.SetStoreRoot(Friflo.Engine.ECS.Entity)') | Set the passed [entity](EntityStore.SetStoreRoot(Entity).md#Friflo.Engine.ECS.EntityStore.SetStoreRoot(Friflo.Engine.ECS.Entity).entity 'Friflo.Engine.ECS.EntityStore.SetStoreRoot(Friflo.Engine.ECS.Entity).entity') as the [StoreRoot](EntityStore.StoreRoot.md 'Friflo.Engine.ECS.EntityStore.StoreRoot') entity. |
| [TryGetEntityByPid(long, Entity)](EntityStore.TryGetEntityByPid(long,Entity).md 'Friflo.Engine.ECS.EntityStore.TryGetEntityByPid(long, Friflo.Engine.ECS.Entity)') | Try to return the [Entity](Entity.md 'Friflo.Engine.ECS.Entity') with the passed entity [pid](EntityStore.TryGetEntityByPid(long,Entity).md#Friflo.Engine.ECS.EntityStore.TryGetEntityByPid(long,Friflo.Engine.ECS.Entity).pid 'Friflo.Engine.ECS.EntityStore.TryGetEntityByPid(long, Friflo.Engine.ECS.Entity).pid').<br/> |

| Events | |
| :--- | :--- |
| [OnChildEntitiesChanged](EntityStore.OnChildEntitiesChanged.md 'Friflo.Engine.ECS.EntityStore.OnChildEntitiesChanged') | Add / remove an event handler for [ChildEntitiesChanged](ChildEntitiesChanged.md 'Friflo.Engine.ECS.ChildEntitiesChanged') events triggered by:<br/>[AddChild(Entity)](Entity.AddChild(Entity).md 'Friflo.Engine.ECS.Entity.AddChild(Friflo.Engine.ECS.Entity)')<br/>[InsertChild(int, Entity)](Entity.InsertChild(int,Entity).md 'Friflo.Engine.ECS.Entity.InsertChild(int, Friflo.Engine.ECS.Entity)')<br/>[RemoveChild(Entity)](Entity.RemoveChild(Entity).md 'Friflo.Engine.ECS.Entity.RemoveChild(Friflo.Engine.ECS.Entity)'). |
| [OnEntitiesChanged](EntityStore.OnEntitiesChanged.md 'Friflo.Engine.ECS.EntityStore.OnEntitiesChanged') | Fire events in case an [Entity](Entity.md 'Friflo.Engine.ECS.Entity') changed. |
| [OnScriptAdded](EntityStore.OnScriptAdded.md 'Friflo.Engine.ECS.EntityStore.OnScriptAdded') | Add / remove an event handler for [ScriptChanged](ScriptChanged.md 'Friflo.Engine.ECS.ScriptChanged') events triggered by:<br/>[AddScript&lt;TScript&gt;(TScript)](Entity.AddScript_TScript_(TScript).md 'Friflo.Engine.ECS.Entity.AddScript<TScript>(TScript)'). |
| [OnScriptRemoved](EntityStore.OnScriptRemoved.md 'Friflo.Engine.ECS.EntityStore.OnScriptRemoved') | Add / remove an event handler for [ScriptChanged](ScriptChanged.md 'Friflo.Engine.ECS.ScriptChanged') events triggered by:<br/>[RemoveScript&lt;TScript&gt;()](Entity.RemoveScript_TScript_().md 'Friflo.Engine.ECS.Entity.RemoveScript<TScript>()') . |
