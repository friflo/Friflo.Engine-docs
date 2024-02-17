#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## Entity Struct

Represent an object in an [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') - e.g. a cube in a game scene.<br/>
It is the <b>main API</b> to deal with entities in the engine.

```csharp
public readonly struct Entity :
System.IEquatable<Friflo.Engine.ECS.Entity>
```

Implements [System.IEquatable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1 'System.IEquatable`1')[Entity](Entity.md 'Friflo.Engine.ECS.Entity')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1 'System.IEquatable`1')

### Remarks

Every [Entity](Entity.md 'Friflo.Engine.ECS.Entity') has an [Id](Entity.Id.md 'Friflo.Engine.ECS.Entity.Id') and is a container of
[Tags](Tags.md 'Friflo.Engine.ECS.Tags'), [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')'s, [Script](Script.md 'Friflo.Engine.ECS.Script')'s and other child [Entity](Entity.md 'Friflo.Engine.ECS.Entity')'s.<br/><br/>
Comparison to other game engines.
- <b>Unity</b>  - an [Entity](Entity.md 'Friflo.Engine.ECS.Entity') provides a similar features set as a `GameObject` and their ECS `Entity`.
- <b>Godot</b>  - [Entity](Entity.md 'Friflo.Engine.ECS.Entity') is the counterpart of a `Node`.<br/>
                      The key difference is Godot is an OOP architecture inheriting from `Node` over multiple levels.
- <b>FLAX</b>   - [Entity](Entity.md 'Friflo.Engine.ECS.Entity') is the counterpart of an `Actor` - an OOP architecture like Godot.
- <b>STRIDE</b> - [Entity](Entity.md 'Friflo.Engine.ECS.Entity') is the counterpart of a STRIDE `Entity` - a component based architecture like Unity.<br/>
                      In contrast to this engine or Unity it has no ECS architecture - Entity Component System.

<b>Components</b><br/>
            An [Entity](Entity.md 'Friflo.Engine.ECS.Entity') is typically an object that can be rendered on screen like a cube, sphere, capsule, mesh, sprite, ... .<br/>
            Therefore a renderable component needs to be added with [AddComponent&lt;T&gt;()](Entity.AddComponent_T_().md 'Friflo.Engine.ECS.Entity.AddComponent<T>()') to an [Entity](Entity.md 'Friflo.Engine.ECS.Entity').<br/><br/><b>Child entities</b><br/>
            An [Entity](Entity.md 'Friflo.Engine.ECS.Entity') can be added to another [Entity](Entity.md 'Friflo.Engine.ECS.Entity') using [AddChild(Entity)](Entity.AddChild(Entity).md 'Friflo.Engine.ECS.Entity.AddChild(Friflo.Engine.ECS.Entity)').<br/>
            The added [Entity](Entity.md 'Friflo.Engine.ECS.Entity') becomes a child of the [Entity](Entity.md 'Friflo.Engine.ECS.Entity') it is added to - its [Parent](Entity.Parent.md 'Friflo.Engine.ECS.Entity.Parent').<br/>
            This enables to build up a complex game scene with a hierarchy of [Entity](Entity.md 'Friflo.Engine.ECS.Entity')'s.<br/>
            The order of children contained by an entity is the insertion order.<br/><br/><b>Scripts</b><br/>
            A [Script](Script.md 'Friflo.Engine.ECS.Script')'s can be added to an [Entity](Entity.md 'Friflo.Engine.ECS.Entity') to add custom logic (script) and data to an entity.<br/>[Script](Script.md 'Friflo.Engine.ECS.Script')'s are added or removed with [AddScript&lt;TScript&gt;(TScript)](Entity.AddScript_TScript_(TScript).md 'Friflo.Engine.ECS.Entity.AddScript<TScript>(TScript)') / [RemoveScript&lt;TScript&gt;()](Entity.RemoveScript_TScript_().md 'Friflo.Engine.ECS.Entity.RemoveScript<TScript>()').<br/><br/><b>Tags</b><br/>[Tags](Entity.Tags.md 'Friflo.Engine.ECS.Entity.Tags') can be added to an [Entity](Entity.md 'Friflo.Engine.ECS.Entity') to enable filtering entities in queries.<br/>
            By adding [Tags](Entity.Tags.md 'Friflo.Engine.ECS.Entity.Tags') to an [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') it can be restricted to return only entities matching the
            these [Tags](Entity.Tags.md 'Friflo.Engine.ECS.Entity.Tags').<br/><br/><b>Events</b><br/>
            All entity changes - aka mutations - can be observed for specific [Entity](Entity.md 'Friflo.Engine.ECS.Entity')'s and the whole [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore').<br/>
            In detail the following changes can be observed.
            

|type|entity event|event argument|action|
|-|-|-|-|
|component|[OnComponentChanged](Entity.OnComponentChanged.md 'Friflo.Engine.ECS.Entity.OnComponentChanged')|[ComponentChanged](ComponentChanged.md 'Friflo.Engine.ECS.ComponentChanged')|[Add](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Add 'Friflo.Engine.ECS.ComponentChangedAction.Add'), [Update](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Update 'Friflo.Engine.ECS.ComponentChangedAction.Update'), [Remove](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Remove 'Friflo.Engine.ECS.ComponentChangedAction.Remove')|
|script|[OnScriptChanged](Entity.OnScriptChanged.md 'Friflo.Engine.ECS.Entity.OnScriptChanged')|[ScriptChanged](ScriptChanged.md 'Friflo.Engine.ECS.ScriptChanged')|[Remove](ScriptChangedAction.md#Friflo.Engine.ECS.ScriptChangedAction.Remove 'Friflo.Engine.ECS.ScriptChangedAction.Remove'), [Add](ScriptChangedAction.md#Friflo.Engine.ECS.ScriptChangedAction.Add 'Friflo.Engine.ECS.ScriptChangedAction.Add'), [Replace](ScriptChangedAction.md#Friflo.Engine.ECS.ScriptChangedAction.Replace 'Friflo.Engine.ECS.ScriptChangedAction.Replace')|
|tags|[OnTagsChanged](Entity.OnTagsChanged.md 'Friflo.Engine.ECS.Entity.OnTagsChanged')|[TagsChanged](TagsChanged.md 'Friflo.Engine.ECS.TagsChanged')|[AddedTags](TagsChanged.AddedTags.md 'Friflo.Engine.ECS.TagsChanged.AddedTags'), [RemovedTags](TagsChanged.RemovedTags.md 'Friflo.Engine.ECS.TagsChanged.RemovedTags')|
|child entity|[OnChildEntitiesChanged](Entity.OnChildEntitiesChanged.md 'Friflo.Engine.ECS.Entity.OnChildEntitiesChanged')|[ChildEntitiesChanged](ChildEntitiesChanged.md 'Friflo.Engine.ECS.ChildEntitiesChanged')|[Add](ChildEntitiesChangedAction.md#Friflo.Engine.ECS.ChildEntitiesChangedAction.Add 'Friflo.Engine.ECS.ChildEntitiesChangedAction.Add'), [Remove](ChildEntitiesChangedAction.md#Friflo.Engine.ECS.ChildEntitiesChangedAction.Remove 'Friflo.Engine.ECS.ChildEntitiesChangedAction.Remove')|

<b>Properties and Methods by category</b>
- <b>general</b><br/>[Id](Entity.Id.md 'Friflo.Engine.ECS.Entity.Id')<br/>[Pid](Entity.Pid.md 'Friflo.Engine.ECS.Entity.Pid')<br/>[Archetype](Entity.Archetype.md 'Friflo.Engine.ECS.Entity.Archetype')<br/>[Store](Entity.Store.md 'Friflo.Engine.ECS.Entity.Store')<br/>[DebugJSON](Entity.DebugJSON.md 'Friflo.Engine.ECS.Entity.DebugJSON')<br/>
- <b>components</b> · generic             <br/>[HasComponent&lt;T&gt;()](Entity.HasComponent_T_().md 'Friflo.Engine.ECS.Entity.HasComponent<T>()')<br/>[GetComponent&lt;T&gt;()](Entity.GetComponent_T_().md 'Friflo.Engine.ECS.Entity.GetComponent<T>()') - read / write<br/>[TryGetComponent&lt;T&gt;(T)](Entity.TryGetComponent_T_(T).md 'Friflo.Engine.ECS.Entity.TryGetComponent<T>(T)')<br/>[AddComponent&lt;T&gt;()](Entity.AddComponent_T_().md 'Friflo.Engine.ECS.Entity.AddComponent<T>()')<br/>[RemoveComponent&lt;T&gt;()](Entity.RemoveComponent_T_().md 'Friflo.Engine.ECS.Entity.RemoveComponent<T>()')<br/>
- <b>components</b> · common              <br/>[Name](Entity.Name.md 'Friflo.Engine.ECS.Entity.Name')<br/>[Position](Entity.Position.md 'Friflo.Engine.ECS.Entity.Position')<br/>[Rotation](Entity.Rotation.md 'Friflo.Engine.ECS.Entity.Rotation')<br/>[Scale3](Entity.Scale3.md 'Friflo.Engine.ECS.Entity.Scale3')<br/>[HasName](Entity.HasName.md 'Friflo.Engine.ECS.Entity.HasName')<br/>[HasPosition](Entity.HasPosition.md 'Friflo.Engine.ECS.Entity.HasPosition')<br/>[HasRotation](Entity.HasRotation.md 'Friflo.Engine.ECS.Entity.HasRotation')<br/>[HasScale3](Entity.HasScale3.md 'Friflo.Engine.ECS.Entity.HasScale3')<br/>
- <b>scripts</b><br/>[Scripts](Entity.Scripts.md 'Friflo.Engine.ECS.Entity.Scripts')<br/>[GetScript&lt;TScript&gt;()](Entity.GetScript_TScript_().md 'Friflo.Engine.ECS.Entity.GetScript<TScript>()')<br/>[TryGetScript&lt;TScript&gt;(TScript)](Entity.TryGetScript_TScript_(TScript).md 'Friflo.Engine.ECS.Entity.TryGetScript<TScript>(TScript)')<br/>[AddScript&lt;TScript&gt;(TScript)](Entity.AddScript_TScript_(TScript).md 'Friflo.Engine.ECS.Entity.AddScript<TScript>(TScript)')<br/>[RemoveScript&lt;TScript&gt;()](Entity.RemoveScript_TScript_().md 'Friflo.Engine.ECS.Entity.RemoveScript<TScript>()')<br/>
- <b>tags</b><br/>[Tags](Entity.Tags.md 'Friflo.Engine.ECS.Entity.Tags')<br/>[AddTag&lt;TTag&gt;()](Entity.AddTag_TTag_().md 'Friflo.Engine.ECS.Entity.AddTag<TTag>()')<br/>[AddTags(Tags)](Entity.AddTags(Tags).md 'Friflo.Engine.ECS.Entity.AddTags(Friflo.Engine.ECS.Tags)')<br/>[RemoveTag&lt;TTag&gt;()](Entity.RemoveTag_TTag_().md 'Friflo.Engine.ECS.Entity.RemoveTag<TTag>()')<br/>[RemoveTags(Tags)](Entity.RemoveTags(Tags).md 'Friflo.Engine.ECS.Entity.RemoveTags(Friflo.Engine.ECS.Tags)')<br/>
- <b>child entities</b><br/>[Parent](Entity.Parent.md 'Friflo.Engine.ECS.Entity.Parent')<br/>[ChildEntities](Entity.ChildEntities.md 'Friflo.Engine.ECS.Entity.ChildEntities')<br/>[ChildIds](Entity.ChildIds.md 'Friflo.Engine.ECS.Entity.ChildIds')<br/>[ChildCount](Entity.ChildCount.md 'Friflo.Engine.ECS.Entity.ChildCount')<br/>[AddChild(Entity)](Entity.AddChild(Entity).md 'Friflo.Engine.ECS.Entity.AddChild(Friflo.Engine.ECS.Entity)')<br/>[InsertChild(int, Entity)](Entity.InsertChild(int,Entity).md 'Friflo.Engine.ECS.Entity.InsertChild(int, Friflo.Engine.ECS.Entity)')<br/>[RemoveChild(Entity)](Entity.RemoveChild(Entity).md 'Friflo.Engine.ECS.Entity.RemoveChild(Friflo.Engine.ECS.Entity)')<br/>[DeleteEntity()](Entity.DeleteEntity().md 'Friflo.Engine.ECS.Entity.DeleteEntity()')<br/>[GetChildIndex(Entity)](Entity.GetChildIndex(Entity).md 'Friflo.Engine.ECS.Entity.GetChildIndex(Friflo.Engine.ECS.Entity)')<br/>
- <b>events</b><br/>[OnTagsChanged](Entity.OnTagsChanged.md 'Friflo.Engine.ECS.Entity.OnTagsChanged')<br/>[OnComponentChanged](Entity.OnComponentChanged.md 'Friflo.Engine.ECS.Entity.OnComponentChanged')<br/>[OnScriptChanged](Entity.OnScriptChanged.md 'Friflo.Engine.ECS.Entity.OnScriptChanged')<br/>[OnChildEntitiesChanged](Entity.OnChildEntitiesChanged.md 'Friflo.Engine.ECS.Entity.OnChildEntitiesChanged')<br/>[DebugEventHandlers](Entity.DebugEventHandlers.md 'Friflo.Engine.ECS.Entity.DebugEventHandlers')<br/>
- <b>signals</b><br/>[AddSignalHandler&lt;TEvent&gt;(Action&lt;Signal&lt;TEvent&gt;&gt;)](Entity.AddSignalHandler_TEvent_(Action_Signal_TEvent__).md 'Friflo.Engine.ECS.Entity.AddSignalHandler<TEvent>(System.Action<Friflo.Engine.ECS.Signal<TEvent>>)')<br/>[RemoveSignalHandler&lt;TEvent&gt;(Action&lt;Signal&lt;TEvent&gt;&gt;)](Entity.RemoveSignalHandler_TEvent_(Action_Signal_TEvent__).md 'Friflo.Engine.ECS.Entity.RemoveSignalHandler<TEvent>(System.Action<Friflo.Engine.ECS.Signal<TEvent>>)')<br/>[EmitSignal&lt;TEvent&gt;(TEvent)](Entity.EmitSignal_TEvent_(TEvent).md 'Friflo.Engine.ECS.Entity.EmitSignal<TEvent>(TEvent)')<br/>

| Fields | |
| :--- | :--- |
| [Id](Entity.Id.md 'Friflo.Engine.ECS.Entity.Id') | Unique entity id.<br/>             Uniqueness relates to the [Entity](Entity.md 'Friflo.Engine.ECS.Entity')'s stored in its [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') |

| Properties | |
| :--- | :--- |
| [Archetype](Entity.Archetype.md 'Friflo.Engine.ECS.Entity.Archetype') | Returns the [Archetype](Entity.Archetype.md 'Friflo.Engine.ECS.Entity.Archetype') that contains the entity. |
| [Batch](Entity.Batch.md 'Friflo.Engine.ECS.Entity.Batch') | Returns an empty [EntityBatch](EntityBatch.md 'Friflo.Engine.ECS.EntityBatch') to add / remove components and tags of this entity as a batch operation. |
| [ChildCount](Entity.ChildCount.md 'Friflo.Engine.ECS.Entity.ChildCount') | Return the number of child entities. |
| [ChildEntities](Entity.ChildEntities.md 'Friflo.Engine.ECS.Entity.ChildEntities') | Return all child entities of an entity. |
| [ChildIds](Entity.ChildIds.md 'Friflo.Engine.ECS.Entity.ChildIds') | Return the ids of the child entities. |
| [Components](Entity.Components.md 'Friflo.Engine.ECS.Entity.Components') | Return the [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')'s added to the entity. |
| [DebugEventHandlers](Entity.DebugEventHandlers.md 'Friflo.Engine.ECS.Entity.DebugEventHandlers') | Return event and signal handlers added to the entity. |
| [DebugJSON](Entity.DebugJSON.md 'Friflo.Engine.ECS.Entity.DebugJSON') | Return the <b>JSON</b> representation of an entity. |
| [HasName](Entity.HasName.md 'Friflo.Engine.ECS.Entity.HasName') | Returns true if the entity has an [EntityName](EntityName.md 'Friflo.Engine.ECS.EntityName'). |
| [HasPosition](Entity.HasPosition.md 'Friflo.Engine.ECS.Entity.HasPosition') | Returns true if the entity has a [Position](Position.md 'Friflo.Engine.ECS.Position'). |
| [HasRotation](Entity.HasRotation.md 'Friflo.Engine.ECS.Entity.HasRotation') | Returns true if the entity has a [Rotation](Rotation.md 'Friflo.Engine.ECS.Rotation'). |
| [HasScale3](Entity.HasScale3.md 'Friflo.Engine.ECS.Entity.HasScale3') | Returns true if the entity has a [Scale3](Scale3.md 'Friflo.Engine.ECS.Scale3'). |
| [IsNull](Entity.IsNull.md 'Friflo.Engine.ECS.Entity.IsNull') | |
| [Name](Entity.Name.md 'Friflo.Engine.ECS.Entity.Name') | Returns the [EntityName](EntityName.md 'Friflo.Engine.ECS.EntityName') reference of an entity. |
| [Parent](Entity.Parent.md 'Friflo.Engine.ECS.Entity.Parent') | Returns the parent entity that contains the entity. |
| [Pid](Entity.Pid.md 'Friflo.Engine.ECS.Entity.Pid') | Returns the permanent entity id used for serialization. |
| [Position](Entity.Position.md 'Friflo.Engine.ECS.Entity.Position') | Returns the [Position](Position.md 'Friflo.Engine.ECS.Position') reference of an entity. |
| [Rotation](Entity.Rotation.md 'Friflo.Engine.ECS.Entity.Rotation') | Returns the [Rotation](Rotation.md 'Friflo.Engine.ECS.Rotation') reference of an entity. |
| [Scale3](Entity.Scale3.md 'Friflo.Engine.ECS.Entity.Scale3') | Returns the [Scale3](Scale3.md 'Friflo.Engine.ECS.Scale3') reference of an entity. |
| [Scripts](Entity.Scripts.md 'Friflo.Engine.ECS.Entity.Scripts') | Return the [Script](Script.md 'Friflo.Engine.ECS.Script')'s added to the entity. |
| [Store](Entity.Store.md 'Friflo.Engine.ECS.Entity.Store') | Returns the [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') that contains the entity. |
| [StoreOwnership](Entity.StoreOwnership.md 'Friflo.Engine.ECS.Entity.StoreOwnership') | |
| [Tags](Entity.Tags.md 'Friflo.Engine.ECS.Entity.Tags') | Return the [Tags](Tags.md 'Friflo.Engine.ECS.Tags') added to the entity. |
| [TreeMembership](Entity.TreeMembership.md 'Friflo.Engine.ECS.Entity.TreeMembership') | |

| Methods | |
| :--- | :--- |
| [AddChild(Entity)](Entity.AddChild(Entity).md 'Friflo.Engine.ECS.Entity.AddChild(Friflo.Engine.ECS.Entity)') | Add the given [entity](Entity.AddChild(Entity).md#Friflo.Engine.ECS.Entity.AddChild(Friflo.Engine.ECS.Entity).entity 'Friflo.Engine.ECS.Entity.AddChild(Friflo.Engine.ECS.Entity).entity') as a child to the entity. |
| [AddComponent&lt;T&gt;()](Entity.AddComponent_T_().md 'Friflo.Engine.ECS.Entity.AddComponent<T>()') | Add a component of the given type [T](Entity.AddComponent_T_().md#Friflo.Engine.ECS.Entity.AddComponent_T_().T 'Friflo.Engine.ECS.Entity.AddComponent<T>().T') to the entity.<br/>             If the entity contains a component of the same type it is updated. |
| [AddComponent&lt;T&gt;(T)](Entity.AddComponent_T_(T).md 'Friflo.Engine.ECS.Entity.AddComponent<T>(T)') | Add the given [component](Entity.AddComponent_T_(T).md#Friflo.Engine.ECS.Entity.AddComponent_T_(T).component 'Friflo.Engine.ECS.Entity.AddComponent<T>(T).component') to the entity.<br/>             If the entity contains a component of the same type it is updated. |
| [AddScript&lt;TScript&gt;(TScript)](Entity.AddScript_TScript_(TScript).md 'Friflo.Engine.ECS.Entity.AddScript<TScript>(TScript)') | Add the given [script](Entity.AddScript_TScript_(TScript).md#Friflo.Engine.ECS.Entity.AddScript_TScript_(TScript).script 'Friflo.Engine.ECS.Entity.AddScript<TScript>(TScript).script') to the entity.<br/>             If the entity contains a script of the same [TScript](Entity.AddScript_TScript_(TScript).md#Friflo.Engine.ECS.Entity.AddScript_TScript_(TScript).TScript 'Friflo.Engine.ECS.Entity.AddScript<TScript>(TScript).TScript')[System.Type](https://docs.microsoft.com/en-us/dotnet/api/System.Type 'System.Type') it is replaced. |
| [AddSignalHandler&lt;TEvent&gt;(Action&lt;Signal&lt;TEvent&gt;&gt;)](Entity.AddSignalHandler_TEvent_(Action_Signal_TEvent__).md 'Friflo.Engine.ECS.Entity.AddSignalHandler<TEvent>(System.Action<Friflo.Engine.ECS.Signal<TEvent>>)') | Add the given [Signal&lt;TEvent&gt;](Signal_TEvent_.md 'Friflo.Engine.ECS.Signal<TEvent>') handler to the entity. |
| [AddTag&lt;TTag&gt;()](Entity.AddTag_TTag_().md 'Friflo.Engine.ECS.Entity.AddTag<TTag>()') | Add the given [TTag](Entity.AddTag_TTag_().md#Friflo.Engine.ECS.Entity.AddTag_TTag_().TTag 'Friflo.Engine.ECS.Entity.AddTag<TTag>().TTag') to the entity. |
| [AddTags(Tags)](Entity.AddTags(Tags).md 'Friflo.Engine.ECS.Entity.AddTags(Friflo.Engine.ECS.Tags)') | Add the given [tags](Entity.AddTags(Tags).md#Friflo.Engine.ECS.Entity.AddTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.Entity.AddTags(Friflo.Engine.ECS.Tags).tags') to the entity. |
| [DeleteEntity()](Entity.DeleteEntity().md 'Friflo.Engine.ECS.Entity.DeleteEntity()') | Delete the entity from its [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore').<br/> The deleted instance is in [detached](StoreOwnership.md#Friflo.Engine.ECS.StoreOwnership.detached 'Friflo.Engine.ECS.StoreOwnership.detached') state. Calling [Entity](Entity.md 'Friflo.Engine.ECS.Entity') methods result in [System.NullReferenceException](https://docs.microsoft.com/en-us/dotnet/api/System.NullReferenceException 'System.NullReferenceException')'s |
| [EmitSignal&lt;TEvent&gt;(TEvent)](Entity.EmitSignal_TEvent_(TEvent).md 'Friflo.Engine.ECS.Entity.EmitSignal<TEvent>(TEvent)') | Emits the passed signal event to all signal handlers added with [AddSignalHandler&lt;TEvent&gt;(Action&lt;Signal&lt;TEvent&gt;&gt;)](Entity.AddSignalHandler_TEvent_(Action_Signal_TEvent__).md 'Friflo.Engine.ECS.Entity.AddSignalHandler<TEvent>(System.Action<Friflo.Engine.ECS.Signal<TEvent>>)'). |
| [Equals(Entity)](Entity.Equals(Entity).md 'Friflo.Engine.ECS.Entity.Equals(Friflo.Engine.ECS.Entity)') | |
| [Equals(object)](Entity.Equals(object).md 'Friflo.Engine.ECS.Entity.Equals(object)') | Note: Not implemented to avoid excessive boxing. |
| [GetChildIndex(Entity)](Entity.GetChildIndex(Entity).md 'Friflo.Engine.ECS.Entity.GetChildIndex(Friflo.Engine.ECS.Entity)') | Return the position of the given [child](Entity.GetChildIndex(Entity).md#Friflo.Engine.ECS.Entity.GetChildIndex(Friflo.Engine.ECS.Entity).child 'Friflo.Engine.ECS.Entity.GetChildIndex(Friflo.Engine.ECS.Entity).child') in the entity. |
| [GetComponent&lt;T&gt;()](Entity.GetComponent_T_().md 'Friflo.Engine.ECS.Entity.GetComponent<T>()') | Return the component of the given type as a reference. |
| [GetHashCode()](Entity.GetHashCode().md 'Friflo.Engine.ECS.Entity.GetHashCode()') | Note: Not implemented to avoid excessive boxing. |
| [GetScript&lt;TScript&gt;()](Entity.GetScript_TScript_().md 'Friflo.Engine.ECS.Entity.GetScript<TScript>()') | Get the script of the passed [TScript](Entity.GetScript_TScript_().md#Friflo.Engine.ECS.Entity.GetScript_TScript_().TScript 'Friflo.Engine.ECS.Entity.GetScript<TScript>().TScript')[System.Type](https://docs.microsoft.com/en-us/dotnet/api/System.Type 'System.Type'). |
| [HasComponent&lt;T&gt;()](Entity.HasComponent_T_().md 'Friflo.Engine.ECS.Entity.HasComponent<T>()') | Return true if the entity contains a component of the given type. |
| [InsertChild(int, Entity)](Entity.InsertChild(int,Entity).md 'Friflo.Engine.ECS.Entity.InsertChild(int, Friflo.Engine.ECS.Entity)') | Insert the given [entity](Entity.InsertChild(int,Entity).md#Friflo.Engine.ECS.Entity.InsertChild(int,Friflo.Engine.ECS.Entity).entity 'Friflo.Engine.ECS.Entity.InsertChild(int, Friflo.Engine.ECS.Entity).entity') as a child to the entity at the passed [index](Entity.InsertChild(int,Entity).md#Friflo.Engine.ECS.Entity.InsertChild(int,Friflo.Engine.ECS.Entity).index 'Friflo.Engine.ECS.Entity.InsertChild(int, Friflo.Engine.ECS.Entity).index'). |
| [RemoveChild(Entity)](Entity.RemoveChild(Entity).md 'Friflo.Engine.ECS.Entity.RemoveChild(Friflo.Engine.ECS.Entity)') | Remove the given child [entity](Entity.RemoveChild(Entity).md#Friflo.Engine.ECS.Entity.RemoveChild(Friflo.Engine.ECS.Entity).entity 'Friflo.Engine.ECS.Entity.RemoveChild(Friflo.Engine.ECS.Entity).entity') from the entity. |
| [RemoveComponent&lt;T&gt;()](Entity.RemoveComponent_T_().md 'Friflo.Engine.ECS.Entity.RemoveComponent<T>()') | Remove the component of the given type from the entity. |
| [RemoveScript&lt;TScript&gt;()](Entity.RemoveScript_TScript_().md 'Friflo.Engine.ECS.Entity.RemoveScript<TScript>()') | Remove the script with the given [TScript](Entity.RemoveScript_TScript_().md#Friflo.Engine.ECS.Entity.RemoveScript_TScript_().TScript 'Friflo.Engine.ECS.Entity.RemoveScript<TScript>().TScript')[System.Type](https://docs.microsoft.com/en-us/dotnet/api/System.Type 'System.Type') from the entity. |
| [RemoveSignalHandler&lt;TEvent&gt;(Action&lt;Signal&lt;TEvent&gt;&gt;)](Entity.RemoveSignalHandler_TEvent_(Action_Signal_TEvent__).md 'Friflo.Engine.ECS.Entity.RemoveSignalHandler<TEvent>(System.Action<Friflo.Engine.ECS.Signal<TEvent>>)') | Remove the given [Signal&lt;TEvent&gt;](Signal_TEvent_.md 'Friflo.Engine.ECS.Signal<TEvent>') handler from the entity. |
| [RemoveTag&lt;TTag&gt;()](Entity.RemoveTag_TTag_().md 'Friflo.Engine.ECS.Entity.RemoveTag<TTag>()') | Add the given [TTag](Entity.RemoveTag_TTag_().md#Friflo.Engine.ECS.Entity.RemoveTag_TTag_().TTag 'Friflo.Engine.ECS.Entity.RemoveTag<TTag>().TTag') from the entity. |
| [RemoveTags(Tags)](Entity.RemoveTags(Tags).md 'Friflo.Engine.ECS.Entity.RemoveTags(Friflo.Engine.ECS.Tags)') | Remove the given [tags](Entity.RemoveTags(Tags).md#Friflo.Engine.ECS.Entity.RemoveTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.Entity.RemoveTags(Friflo.Engine.ECS.Tags).tags') from the entity. |
| [ToString()](Entity.ToString().md 'Friflo.Engine.ECS.Entity.ToString()') | |
| [TryGetComponent&lt;T&gt;(T)](Entity.TryGetComponent_T_(T).md 'Friflo.Engine.ECS.Entity.TryGetComponent<T>(T)') | |
| [TryGetScript&lt;TScript&gt;(TScript)](Entity.TryGetScript_TScript_(TScript).md 'Friflo.Engine.ECS.Entity.TryGetScript<TScript>(TScript)') | Gets the script with the passed [TScript](Entity.TryGetScript_TScript_(TScript).md#Friflo.Engine.ECS.Entity.TryGetScript_TScript_(TScript).TScript 'Friflo.Engine.ECS.Entity.TryGetScript<TScript>(TScript).TScript')[System.Type](https://docs.microsoft.com/en-us/dotnet/api/System.Type 'System.Type'). |

| Events | |
| :--- | :--- |
| [OnChildEntitiesChanged](Entity.OnChildEntitiesChanged.md 'Friflo.Engine.ECS.Entity.OnChildEntitiesChanged') | Add / remove an event handler for [ChildEntitiesChanged](ChildEntitiesChanged.md 'Friflo.Engine.ECS.ChildEntitiesChanged') events triggered by:<br/>[AddChild(Entity)](Entity.AddChild(Entity).md 'Friflo.Engine.ECS.Entity.AddChild(Friflo.Engine.ECS.Entity)')<br/>[InsertChild(int, Entity)](Entity.InsertChild(int,Entity).md 'Friflo.Engine.ECS.Entity.InsertChild(int, Friflo.Engine.ECS.Entity)')<br/>[RemoveChild(Entity)](Entity.RemoveChild(Entity).md 'Friflo.Engine.ECS.Entity.RemoveChild(Friflo.Engine.ECS.Entity)'). |
| [OnComponentChanged](Entity.OnComponentChanged.md 'Friflo.Engine.ECS.Entity.OnComponentChanged') | Add / remove an event handler for [ComponentChanged](ComponentChanged.md 'Friflo.Engine.ECS.ComponentChanged') events triggered by: <br/>[AddComponent&lt;T&gt;()](Entity.AddComponent_T_().md 'Friflo.Engine.ECS.Entity.AddComponent<T>()')<br/>[RemoveComponent&lt;T&gt;()](Entity.RemoveComponent_T_().md 'Friflo.Engine.ECS.Entity.RemoveComponent<T>()'). |
| [OnScriptChanged](Entity.OnScriptChanged.md 'Friflo.Engine.ECS.Entity.OnScriptChanged') | Add / remove an event handler for [ScriptChanged](ScriptChanged.md 'Friflo.Engine.ECS.ScriptChanged') events triggered by:<br/>[AddScript&lt;TScript&gt;(TScript)](Entity.AddScript_TScript_(TScript).md 'Friflo.Engine.ECS.Entity.AddScript<TScript>(TScript)')<br/>[RemoveScript&lt;TScript&gt;()](Entity.RemoveScript_TScript_().md 'Friflo.Engine.ECS.Entity.RemoveScript<TScript>()'). |
| [OnTagsChanged](Entity.OnTagsChanged.md 'Friflo.Engine.ECS.Entity.OnTagsChanged') | Add / remove an event handler for [TagsChanged](TagsChanged.md 'Friflo.Engine.ECS.TagsChanged') events triggered by:<br/>[AddTag&lt;TTag&gt;()](Entity.AddTag_TTag_().md 'Friflo.Engine.ECS.Entity.AddTag<TTag>()')<br/>[AddTags(Tags)](Entity.AddTags(Tags).md 'Friflo.Engine.ECS.Entity.AddTags(Friflo.Engine.ECS.Tags)')<br/>[RemoveTag&lt;TTag&gt;()](Entity.RemoveTag_TTag_().md 'Friflo.Engine.ECS.Entity.RemoveTag<TTag>()')<br/>[RemoveTags(Tags)](Entity.RemoveTags(Tags).md 'Friflo.Engine.ECS.Entity.RemoveTags(Friflo.Engine.ECS.Tags)'). |

| Operators | |
| :--- | :--- |
| [operator ==(Entity, Entity)](Entity.operator(Entity,Entity).md 'Friflo.Engine.ECS.Entity.op_Equality(Friflo.Engine.ECS.Entity, Friflo.Engine.ECS.Entity)') | |
| [operator !=(Entity, Entity)](Entity.operator!(Entity,Entity).md 'Friflo.Engine.ECS.Entity.op_Inequality(Friflo.Engine.ECS.Entity, Friflo.Engine.ECS.Entity)') | |
