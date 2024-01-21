#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## EntityStore Class

An [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') is a container for [Entity](Entity.md 'Friflo.Engine.ECS.Entity')'s their components, scripts, tags
and their tree structure.

```csharp
public sealed class EntityStore : Friflo.Engine.ECS.EntityStoreBase
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; [EntityStoreBase](EntityStoreBase.md 'Friflo.Engine.ECS.EntityStoreBase') &#129106; EntityStore

### Remarks
The [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') provide the features listed below
- Store a map (container) of entities in linear memory.<br/>
  Entity data can retrieved by entity <b>id</b> using the property [GetEntityById(int)](EntityStore.GetEntityById(int).md 'Friflo.Engine.ECS.EntityStore.GetEntityById(int)').<br/>[Entity](Entity.md 'Friflo.Engine.ECS.Entity')'s have the states below:<br/>
  - <b>
      <see cref="T:Friflo.Engine.ECS.StoreOwnership"/>:</b>[attached](StoreOwnership.md#Friflo.Engine.ECS.StoreOwnership.attached 'Friflo.Engine.ECS.StoreOwnership.attached') / [detached](StoreOwnership.md#Friflo.Engine.ECS.StoreOwnership.detached 'Friflo.Engine.ECS.StoreOwnership.detached')<br/>
                      if [detached](StoreOwnership.md#Friflo.Engine.ECS.StoreOwnership.detached 'Friflo.Engine.ECS.StoreOwnership.detached') - [System.NullReferenceException](https://docs.microsoft.com/en-us/dotnet/api/System.NullReferenceException 'System.NullReferenceException') are thrown by [Entity](Entity.md 'Friflo.Engine.ECS.Entity') methods.
  - <b>
      <see cref="T:Friflo.Engine.ECS.TreeMembership"/>:</b>[treeNode](TreeMembership.md#Friflo.Engine.ECS.TreeMembership.treeNode 'Friflo.Engine.ECS.TreeMembership.treeNode') / [floating](TreeMembership.md#Friflo.Engine.ECS.TreeMembership.floating 'Friflo.Engine.ECS.TreeMembership.floating') node (not part of the [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') tree graph).<br/>
                      All children of a [treeNode](TreeMembership.md#Friflo.Engine.ECS.TreeMembership.treeNode 'Friflo.Engine.ECS.TreeMembership.treeNode') are [treeNode](TreeMembership.md#Friflo.Engine.ECS.TreeMembership.treeNode 'Friflo.Engine.ECS.TreeMembership.treeNode')'s themselves.
- Manage a tree graph of entities which starts with the [StoreRoot](EntityStore.StoreRoot.md 'Friflo.Engine.ECS.EntityStore.StoreRoot') entity to build up a scene graph
- Store the data of [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')'s and [Script](Script.md 'Friflo.Engine.ECS.Script')'s.

| Constructors | |
| :--- | :--- |
| [EntityStore()](EntityStore.EntityStore().md 'Friflo.Engine.ECS.EntityStore.EntityStore()') | |
| [EntityStore(PidType)](EntityStore.EntityStore(PidType).md 'Friflo.Engine.ECS.EntityStore.EntityStore(Friflo.Engine.ECS.PidType)') | |

| Properties | |
| :--- | :--- |
| [Entities](EntityStore.Entities.md 'Friflo.Engine.ECS.EntityStore.Entities') | Return all [Entity](Entity.md 'Friflo.Engine.ECS.Entity')'s stored in the [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore'). |
| [EntityScripts](EntityStore.EntityScripts.md 'Friflo.Engine.ECS.EntityStore.EntityScripts') | Return all [Script](Script.md 'Friflo.Engine.ECS.Script')'s added to [Entity](Entity.md 'Friflo.Engine.ECS.Entity')'s in the [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore'). |
| [StoreRoot](EntityStore.StoreRoot.md 'Friflo.Engine.ECS.EntityStore.StoreRoot') | Return the root [Entity](Entity.md 'Friflo.Engine.ECS.Entity') of the store. |

| Methods | |
| :--- | :--- |
| [CastEntitiesChanged(object, EntitiesChanged)](EntityStore.CastEntitiesChanged(object,EntitiesChanged).md 'Friflo.Engine.ECS.EntityStore.CastEntitiesChanged(object, Friflo.Engine.ECS.EntitiesChanged)') | |
| [CloneEntity(Entity)](EntityStore.CloneEntity(Entity).md 'Friflo.Engine.ECS.EntityStore.CloneEntity(Friflo.Engine.ECS.Entity)') | |
| [CreateEntity()](EntityStore.CreateEntity().md 'Friflo.Engine.ECS.EntityStore.CreateEntity()') | |
| [CreateEntity(int)](EntityStore.CreateEntity(int).md 'Friflo.Engine.ECS.EntityStore.CreateEntity(int)') | |
| [EnsureCapacity(int)](EntityStore.EnsureCapacity(int).md 'Friflo.Engine.ECS.EntityStore.EnsureCapacity(int)') | |
| [GetEntityById(int)](EntityStore.GetEntityById(int).md 'Friflo.Engine.ECS.EntityStore.GetEntityById(int)') | |
| [GetEntityByPid(long)](EntityStore.GetEntityByPid(long).md 'Friflo.Engine.ECS.EntityStore.GetEntityByPid(long)') | |
| [GetEntityNode(int)](EntityStore.GetEntityNode(int).md 'Friflo.Engine.ECS.EntityStore.GetEntityNode(int)') | |
| [GetEntitySchema()](EntityStore.GetEntitySchema().md 'Friflo.Engine.ECS.EntityStore.GetEntitySchema()') | |
| [IdToPid(int)](EntityStore.IdToPid(int).md 'Friflo.Engine.ECS.EntityStore.IdToPid(int)') | |
| [PidToId(long)](EntityStore.PidToId(long).md 'Friflo.Engine.ECS.EntityStore.PidToId(long)') | |
| [SetRandomSeed(int)](EntityStore.SetRandomSeed(int).md 'Friflo.Engine.ECS.EntityStore.SetRandomSeed(int)') | |
| [SetStoreRoot(Entity)](EntityStore.SetStoreRoot(Entity).md 'Friflo.Engine.ECS.EntityStore.SetStoreRoot(Friflo.Engine.ECS.Entity)') | |
| [TryGetEntityByPid(long, Entity)](EntityStore.TryGetEntityByPid(long,Entity).md 'Friflo.Engine.ECS.EntityStore.TryGetEntityByPid(long, Friflo.Engine.ECS.Entity)') | |

| Events | |
| :--- | :--- |
| [OnChildEntitiesChanged](EntityStore.OnChildEntitiesChanged.md 'Friflo.Engine.ECS.EntityStore.OnChildEntitiesChanged') | Add / remove an event handler for [ChildEntitiesChanged](ChildEntitiesChanged.md 'Friflo.Engine.ECS.ChildEntitiesChanged') events triggered by:<br/>[AddChild(Entity)](Entity.AddChild(Entity).md 'Friflo.Engine.ECS.Entity.AddChild(Friflo.Engine.ECS.Entity)')<br/>[InsertChild(int, Entity)](Entity.InsertChild(int,Entity).md 'Friflo.Engine.ECS.Entity.InsertChild(int, Friflo.Engine.ECS.Entity)')<br/>[RemoveChild(Entity)](Entity.RemoveChild(Entity).md 'Friflo.Engine.ECS.Entity.RemoveChild(Friflo.Engine.ECS.Entity)'). |
| [OnEntitiesChanged](EntityStore.OnEntitiesChanged.md 'Friflo.Engine.ECS.EntityStore.OnEntitiesChanged') | Fire events in case an [Entity](Entity.md 'Friflo.Engine.ECS.Entity') changed. |
| [OnScriptAdded](EntityStore.OnScriptAdded.md 'Friflo.Engine.ECS.EntityStore.OnScriptAdded') | Add / remove an event handler for [ScriptChanged](ScriptChanged.md 'Friflo.Engine.ECS.ScriptChanged') events triggered by:<br/>[AddScript&lt;TScript&gt;(TScript)](Entity.AddScript_TScript_(TScript).md 'Friflo.Engine.ECS.Entity.AddScript<TScript>(TScript)'). |
| [OnScriptRemoved](EntityStore.OnScriptRemoved.md 'Friflo.Engine.ECS.EntityStore.OnScriptRemoved') | Add / remove an event handler for [ScriptChanged](ScriptChanged.md 'Friflo.Engine.ECS.ScriptChanged') events triggered by:<br/>[RemoveScript&lt;T&gt;()](Entity.RemoveScript_T_().md 'Friflo.Engine.ECS.Entity.RemoveScript<T>()') . |
