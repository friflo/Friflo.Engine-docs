#### [Friflo.Engine.ECS](index.md 'index')

## Friflo.Engine.ECS Namespace

| Classes | |
| :--- | :--- |
| [Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype') | An [Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype') store entities with a specific set of [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') and [ITag](ITag.md 'Friflo.Engine.ECS.ITag') types. |
| [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') | [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') an all its generic implementation are immutable and designed to reuse its instances. |
| [ArchetypeQuery&lt;T1,T2,T3,T4,T5&gt;](ArchetypeQuery_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>') | |
| [ArchetypeQuery&lt;T1,T2,T3,T4&gt;](ArchetypeQuery_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>') | |
| [ArchetypeQuery&lt;T1,T2,T3&gt;](ArchetypeQuery_T1,T2,T3_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>') | |
| [ArchetypeQuery&lt;T1,T2&gt;](ArchetypeQuery_T1,T2_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>') | |
| [ArchetypeQuery&lt;T1&gt;](ArchetypeQuery_T1_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1>') | |
| [ArchetypeUtils](ArchetypeUtils.md 'Friflo.Engine.ECS.ArchetypeUtils') | |
| [ChunkExtensions](ChunkExtensions.md 'Friflo.Engine.ECS.ChunkExtensions') | |
| [ComponentKeyAttribute](ComponentKeyAttribute.md 'Friflo.Engine.ECS.ComponentKeyAttribute') | Assign a custom key used for JSON serialization for annotated [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') and [Script](Script.md 'Friflo.Engine.ECS.Script') types.<br/> |
| [ComponentSystem](ComponentSystem.md 'Friflo.Engine.ECS.ComponentSystem') | |
| [ComponentType](ComponentType.md 'Friflo.Engine.ECS.ComponentType') | Provide meta data for an [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') struct. |
| [EntityEqualityComparer](EntityEqualityComparer.md 'Friflo.Engine.ECS.EntityEqualityComparer') | |
| [EntitySchema](EntitySchema.md 'Friflo.Engine.ECS.EntitySchema') | Provide type information about all [ITag](ITag.md 'Friflo.Engine.ECS.ITag'), [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') and [Script](Script.md 'Friflo.Engine.ECS.Script') types available in the application. |
| [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') | An [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') is a container for [Entity](Entity.md 'Friflo.Engine.ECS.Entity')'s their components, scripts, tags and the tree structure. |
| [EntityStoreBase](EntityStoreBase.md 'Friflo.Engine.ECS.EntityStoreBase') | Store the [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')s and [ITag](ITag.md 'Friflo.Engine.ECS.ITag') for the [Entity](Entity.md 'Friflo.Engine.ECS.Entity')'s of an [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore'). |
| [EntityStoreBase.Static](EntityStoreBase.Static.md 'Friflo.Engine.ECS.EntityStoreBase.Static') | |
| [EntityUtils](EntityUtils.md 'Friflo.Engine.ECS.EntityUtils') | |
| [RawEntityStore](RawEntityStore.md 'Friflo.Engine.ECS.RawEntityStore') | A [RawEntityStore](RawEntityStore.md 'Friflo.Engine.ECS.RawEntityStore') enables using an entity store without using [Entity](Entity.md 'Friflo.Engine.ECS.Entity')'s.<br/> |
| [SchemaType](SchemaType.md 'Friflo.Engine.ECS.SchemaType') | Provide meta data for [Script](Script.md 'Friflo.Engine.ECS.Script') classes and [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') / [ITag](ITag.md 'Friflo.Engine.ECS.ITag') structs. |
| [Script](Script.md 'Friflo.Engine.ECS.Script') | To enable adding a script class to an [Entity](Entity.md 'Friflo.Engine.ECS.Entity') it need to extend [Script](Script.md 'Friflo.Engine.ECS.Script'). |
| [ScriptType](ScriptType.md 'Friflo.Engine.ECS.ScriptType') | Provide meta data for a [Script](Script.md 'Friflo.Engine.ECS.Script') class. |
| [Signature](Signature.md 'Friflo.Engine.ECS.Signature') | A [Signature](Signature.md 'Friflo.Engine.ECS.Signature') is used to query entities of an [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') |
| [StoreDispatcher](StoreDispatcher.md 'Friflo.Engine.ECS.StoreDispatcher') | Contains methods to dispatch execution of [System.Action](https://docs.microsoft.com/en-us/dotnet/api/System.Action 'System.Action')'s or [System.Func&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-1 'System.Func`1')'s to the main thread. |
| [Systems](Systems.md 'Friflo.Engine.ECS.Systems') | |
| [TagNameAttribute](TagNameAttribute.md 'Friflo.Engine.ECS.TagNameAttribute') | Assign a custom tag name used for JSON serialization for annotated <b>struct</b>s implementing [ITag](ITag.md 'Friflo.Engine.ECS.ITag'). |
| [TagType](TagType.md 'Friflo.Engine.ECS.TagType') | Provide meta data for an [ITag](ITag.md 'Friflo.Engine.ECS.ITag') struct. |

| Structs | |
| :--- | :--- |
| [ChildEntities](ChildEntities.md 'Friflo.Engine.ECS.ChildEntities') | Return the child entities of an [Entity](Entity.md 'Friflo.Engine.ECS.Entity'). |
| [ChildEntitiesChanged](ChildEntitiesChanged.md 'Friflo.Engine.ECS.ChildEntitiesChanged') | Is the event for event handlers added to [OnChildEntitiesChanged](Entity.OnChildEntitiesChanged.md 'Friflo.Engine.ECS.Entity.OnChildEntitiesChanged') or [OnChildEntitiesChanged](EntityStore.OnChildEntitiesChanged.md 'Friflo.Engine.ECS.EntityStore.OnChildEntitiesChanged'). |
| [ChildEnumerator](ChildEnumerator.md 'Friflo.Engine.ECS.ChildEnumerator') | Use to enumerate the child entities stored in [Entity](Entity.md 'Friflo.Engine.ECS.Entity').[ChildEntities](Entity.ChildEntities.md 'Friflo.Engine.ECS.Entity.ChildEntities'). |
| [Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>') | A [Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>') is container of <b>struct</b> components of Type [T](Chunk_T_.md#Friflo.Engine.ECS.Chunk_T_.T 'Friflo.Engine.ECS.Chunk<T>.T'). |
| [ChunkEntities](ChunkEntities.md 'Friflo.Engine.ECS.ChunkEntities') | Provide the entity id for each [Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>').[Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>') element with [Ids](ChunkEntities.Ids.md 'Friflo.Engine.ECS.ChunkEntities.Ids') or [this[int]](ChunkEntities.this[int].md 'Friflo.Engine.ECS.ChunkEntities.this[int]').<br/> |
| [ChunkEntitiesEnumerator](ChunkEntitiesEnumerator.md 'Friflo.Engine.ECS.ChunkEntitiesEnumerator') | |
| [ChunkEnumerator&lt;T1,T2,T3,T4,T5&gt;](ChunkEnumerator_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.ChunkEnumerator<T1,T2,T3,T4,T5>') | |
| [ChunkEnumerator&lt;T1,T2,T3,T4&gt;](ChunkEnumerator_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.ChunkEnumerator<T1,T2,T3,T4>') | |
| [ChunkEnumerator&lt;T1,T2,T3&gt;](ChunkEnumerator_T1,T2,T3_.md 'Friflo.Engine.ECS.ChunkEnumerator<T1,T2,T3>') | |
| [ChunkEnumerator&lt;T1,T2&gt;](ChunkEnumerator_T1,T2_.md 'Friflo.Engine.ECS.ChunkEnumerator<T1,T2>') | |
| [ChunkEnumerator&lt;T1&gt;](ChunkEnumerator_T1_.md 'Friflo.Engine.ECS.ChunkEnumerator<T1>') | |
| [Chunks&lt;T1,T2,T3,T4,T5&gt;](Chunks_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4,T5>') | |
| [Chunks&lt;T1,T2,T3,T4&gt;](Chunks_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3,T4>') | |
| [Chunks&lt;T1,T2,T3&gt;](Chunks_T1,T2,T3_.md 'Friflo.Engine.ECS.Chunks<T1,T2,T3>') | |
| [Chunks&lt;T1,T2&gt;](Chunks_T1,T2_.md 'Friflo.Engine.ECS.Chunks<T1,T2>') | |
| [Chunks&lt;T1&gt;](Chunks_T1_.md 'Friflo.Engine.ECS.Chunks<T1>') | |
| [ComponentChanged](ComponentChanged.md 'Friflo.Engine.ECS.ComponentChanged') | Is the event for event handlers added to [OnComponentChanged](Entity.OnComponentChanged.md 'Friflo.Engine.ECS.Entity.OnComponentChanged'), [OnComponentAdded](EntityStoreBase.OnComponentAdded.md 'Friflo.Engine.ECS.EntityStoreBase.OnComponentAdded') or [OnComponentRemoved](EntityStoreBase.OnComponentRemoved.md 'Friflo.Engine.ECS.EntityStoreBase.OnComponentRemoved'). |
| [ComponentEnumerator](ComponentEnumerator.md 'Friflo.Engine.ECS.ComponentEnumerator') | Enumerate the components of an entity by iterating [EntityComponents](EntityComponents.md 'Friflo.Engine.ECS.EntityComponents'). |
| [ComponentTypes](ComponentTypes.md 'Friflo.Engine.ECS.ComponentTypes') | [ComponentTypes](ComponentTypes.md 'Friflo.Engine.ECS.ComponentTypes') define a set of [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')'s used to list the             component [System.Type](https://docs.microsoft.com/en-us/dotnet/api/System.Type 'System.Type')'s of an [Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype'). |
| [ComponentTypesEnumerator](ComponentTypesEnumerator.md 'Friflo.Engine.ECS.ComponentTypesEnumerator') | Return the [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') types of [ComponentTypes](ComponentTypes.md 'Friflo.Engine.ECS.ComponentTypes'). |
| [DebugEventHandler](DebugEventHandler.md 'Friflo.Engine.ECS.DebugEventHandler') | Used as item type in [DebugEventHandlers](DebugEventHandlers.md 'Friflo.Engine.ECS.DebugEventHandlers') providing the number of handlers for a specific event [Type](DebugEventHandler.Type.md 'Friflo.Engine.ECS.DebugEventHandler.Type'). |
| [DebugEventHandlers](DebugEventHandlers.md 'Friflo.Engine.ECS.DebugEventHandlers') | Provide the event / signal handlers of an entity using [Entity](Entity.md 'Friflo.Engine.ECS.Entity').[DebugEventHandlers](Entity.DebugEventHandlers.md 'Friflo.Engine.ECS.Entity.DebugEventHandlers'). |
| [EngineDependant](EngineDependant.md 'Friflo.Engine.ECS.EngineDependant') | |
| [EntitiesChanged](EntitiesChanged.md 'Friflo.Engine.ECS.EntitiesChanged') | |
| [EntitiesEnumerator](EntitiesEnumerator.md 'Friflo.Engine.ECS.EntitiesEnumerator') | Used to enumerate the [Entities](ArchetypeQuery.Entities.md 'Friflo.Engine.ECS.ArchetypeQuery.Entities') of an  [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery'). |
| [Entity](Entity.md 'Friflo.Engine.ECS.Entity') | Represent an object in an [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') - e.g. a cube in a game scene.<br/> It is the <b>main API</b> to deal with entities in the engine. |
| [EntityComponent](EntityComponent.md 'Friflo.Engine.ECS.EntityComponent') | An item in [EntityComponents](EntityComponents.md 'Friflo.Engine.ECS.EntityComponents') containing an entity [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent'). |
| [EntityComponents](EntityComponents.md 'Friflo.Engine.ECS.EntityComponents') | Return the [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')'s added to an [Entity](Entity.md 'Friflo.Engine.ECS.Entity'). |
| [EntityName](EntityName.md 'Friflo.Engine.ECS.EntityName') | Can be added to an [Entity](Entity.md 'Friflo.Engine.ECS.Entity') to provide a descriptive name for debugging or in an editor. |
| [EntityNode](EntityNode.md 'Friflo.Engine.ECS.EntityNode') | Used by the [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') to store [Entity](Entity.md 'Friflo.Engine.ECS.Entity') components, scripts, tags and child entities internally as an array of nodes. |
| [EntityScripts](EntityScripts.md 'Friflo.Engine.ECS.EntityScripts') | Return the [Script](Script.md 'Friflo.Engine.ECS.Script')'s added to an [Entity](Entity.md 'Friflo.Engine.ECS.Entity'). |
| [EntityScriptsEnumerator](EntityScriptsEnumerator.md 'Friflo.Engine.ECS.EntityScriptsEnumerator') | Used to enumerate the [Script](Script.md 'Friflo.Engine.ECS.Script')'s added to an [Entity](Entity.md 'Friflo.Engine.ECS.Entity'). |
| [Position](Position.md 'Friflo.Engine.ECS.Position') | |
| [QueryChunks&lt;T1,T2,T3,T4,T5&gt;](QueryChunks_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.QueryChunks<T1,T2,T3,T4,T5>') | |
| [QueryChunks&lt;T1,T2,T3,T4&gt;](QueryChunks_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.QueryChunks<T1,T2,T3,T4>') | |
| [QueryChunks&lt;T1,T2,T3&gt;](QueryChunks_T1,T2,T3_.md 'Friflo.Engine.ECS.QueryChunks<T1,T2,T3>') | |
| [QueryChunks&lt;T1,T2&gt;](QueryChunks_T1,T2_.md 'Friflo.Engine.ECS.QueryChunks<T1,T2>') | |
| [QueryChunks&lt;T1&gt;](QueryChunks_T1_.md 'Friflo.Engine.ECS.QueryChunks<T1>') | |
| [QueryEntities](QueryEntities.md 'Friflo.Engine.ECS.QueryEntities') | Provide the result set of an [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') as a set of [Entity](Entity.md 'Friflo.Engine.ECS.Entity')'s. |
| [Rotation](Rotation.md 'Friflo.Engine.ECS.Rotation') | |
| [Scale3](Scale3.md 'Friflo.Engine.ECS.Scale3') | |
| [ScriptChanged](ScriptChanged.md 'Friflo.Engine.ECS.ScriptChanged') | Is the event for event handlers added to [OnScriptChanged](Entity.OnScriptChanged.md 'Friflo.Engine.ECS.Entity.OnScriptChanged'), [OnScriptAdded](EntityStore.OnScriptAdded.md 'Friflo.Engine.ECS.EntityStore.OnScriptAdded') or [OnScriptRemoved](EntityStore.OnScriptRemoved.md 'Friflo.Engine.ECS.EntityStore.OnScriptRemoved'). |
| [Signal&lt;TEvent&gt;](Signal_TEvent_.md 'Friflo.Engine.ECS.Signal<TEvent>') | [Signal&lt;TEvent&gt;](Signal_TEvent_.md 'Friflo.Engine.ECS.Signal<TEvent>')'s are used to emit custom events from an entity to custom [Signal&lt;TEvent&gt;](Signal_TEvent_.md 'Friflo.Engine.ECS.Signal<TEvent>') handlers. |
| [Signature&lt;T1,T2,T3,T4,T5&gt;](Signature_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3,T4,T5>') | |
| [Signature&lt;T1,T2,T3,T4&gt;](Signature_T1,T2,T3,T4_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3,T4>') | |
| [Signature&lt;T1,T2,T3&gt;](Signature_T1,T2,T3_.md 'Friflo.Engine.ECS.Signature<T1,T2,T3>') | |
| [Signature&lt;T1,T2&gt;](Signature_T1,T2_.md 'Friflo.Engine.ECS.Signature<T1,T2>') | |
| [Signature&lt;T1&gt;](Signature_T1_.md 'Friflo.Engine.ECS.Signature<T1>') | |
| [Tags](Tags.md 'Friflo.Engine.ECS.Tags') | [Tags](Tags.md 'Friflo.Engine.ECS.Tags') define a set of [ITag](ITag.md 'Friflo.Engine.ECS.ITag')'s used to query entities in an [EntityStoreBase](EntityStoreBase.md 'Friflo.Engine.ECS.EntityStoreBase'). |
| [TagsChanged](TagsChanged.md 'Friflo.Engine.ECS.TagsChanged') | Is the event for event handlers added to [OnTagsChanged](Entity.OnTagsChanged.md 'Friflo.Engine.ECS.Entity.OnTagsChanged') or [OnTagsChanged](EntityStoreBase.OnTagsChanged.md 'Friflo.Engine.ECS.EntityStoreBase.OnTagsChanged'). |
| [TagsEnumerator](TagsEnumerator.md 'Friflo.Engine.ECS.TagsEnumerator') | Used to enumerate the [ITag](ITag.md 'Friflo.Engine.ECS.ITag')'s stored in [Tags](Tags.md 'Friflo.Engine.ECS.Tags'). |
| [Transform](Transform.md 'Friflo.Engine.ECS.Transform') | |
| [UniqueEntity](UniqueEntity.md 'Friflo.Engine.ECS.UniqueEntity') | A [UniqueEntity](UniqueEntity.md 'Friflo.Engine.ECS.UniqueEntity') is used to assign a unique `string` to an entity within an [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore'). |
| [Unresolved](Unresolved.md 'Friflo.Engine.ECS.Unresolved') | [Unresolved](Unresolved.md 'Friflo.Engine.ECS.Unresolved') is a container for unresolved entity components. |
| [UnresolvedComponent](UnresolvedComponent.md 'Friflo.Engine.ECS.UnresolvedComponent') | Is used as item type for [Unresolved](Unresolved.md 'Friflo.Engine.ECS.Unresolved').[components](Unresolved.components.md 'Friflo.Engine.ECS.Unresolved.components') storing unresolved entity components. |

| Interfaces | |
| :--- | :--- |
| [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') | To enable adding a struct component to an [Entity](Entity.md 'Friflo.Engine.ECS.Entity') it need to implement [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent').<br/>[IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') types are <b>struct</b>s which only contains data <b>but no</b> script / methods.<br/> |
| [IStoreDispatcher](IStoreDispatcher.md 'Friflo.Engine.ECS.IStoreDispatcher') | |
| [ITag](ITag.md 'Friflo.Engine.ECS.ITag') | Used to create entity <b>Tag</b>'s by declaring a struct without fields or properties extending [ITag](ITag.md 'Friflo.Engine.ECS.ITag').<br/><b>Note:</b> An [ITag](ITag.md 'Friflo.Engine.ECS.ITag') should be used to tag a group of multiple entities. See Remarks. |

| Enums | |
| :--- | :--- |
| [ChildEntitiesChangedAction](ChildEntitiesChangedAction.md 'Friflo.Engine.ECS.ChildEntitiesChangedAction') | The modification type of an [ChildEntitiesChanged](ChildEntitiesChanged.md 'Friflo.Engine.ECS.ChildEntitiesChanged') event: [Add](ChildEntitiesChangedAction.md#Friflo.Engine.ECS.ChildEntitiesChangedAction.Add 'Friflo.Engine.ECS.ChildEntitiesChangedAction.Add') or [Remove](ChildEntitiesChangedAction.md#Friflo.Engine.ECS.ChildEntitiesChangedAction.Remove 'Friflo.Engine.ECS.ChildEntitiesChangedAction.Remove') entity. |
| [ComponentChangedAction](ComponentChangedAction.md 'Friflo.Engine.ECS.ComponentChangedAction') | The modification type of a [ComponentChanged](ComponentChanged.md 'Friflo.Engine.ECS.ComponentChanged') event: [Remove](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Remove 'Friflo.Engine.ECS.ComponentChangedAction.Remove'), [Add](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Add 'Friflo.Engine.ECS.ComponentChangedAction.Add') or [Update](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Update 'Friflo.Engine.ECS.ComponentChangedAction.Update') component. |
| [DebugEntityEventKind](DebugEntityEventKind.md 'Friflo.Engine.ECS.DebugEntityEventKind') | Event type of a [DebugEventHandler](DebugEventHandler.md 'Friflo.Engine.ECS.DebugEventHandler'): [Event](DebugEntityEventKind.md#Friflo.Engine.ECS.DebugEntityEventKind.Event 'Friflo.Engine.ECS.DebugEntityEventKind.Event') or [Signal](DebugEntityEventKind.md#Friflo.Engine.ECS.DebugEntityEventKind.Signal 'Friflo.Engine.ECS.DebugEntityEventKind.Signal'). |
| [NodeFlags](NodeFlags.md 'Friflo.Engine.ECS.NodeFlags') | Flags assigned to [EntityNode](EntityNode.md 'Friflo.Engine.ECS.EntityNode')'s internally stored in an [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore'). |
| [PidType](PidType.md 'Friflo.Engine.ECS.PidType') | Specify the way how an [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') generates entity [Pid](Entity.Pid.md 'Friflo.Engine.ECS.Entity.Pid')'s. |
| [SchemaTypeKind](SchemaTypeKind.md 'Friflo.Engine.ECS.SchemaTypeKind') | Declares the [Kind](SchemaType.Kind.md 'Friflo.Engine.ECS.SchemaType.Kind') of a [SchemaType](SchemaType.md 'Friflo.Engine.ECS.SchemaType') |
| [ScriptChangedAction](ScriptChangedAction.md 'Friflo.Engine.ECS.ScriptChangedAction') | The modification type of a [ScriptChanged](ScriptChanged.md 'Friflo.Engine.ECS.ScriptChanged') event: [Remove](ScriptChangedAction.md#Friflo.Engine.ECS.ScriptChangedAction.Remove 'Friflo.Engine.ECS.ScriptChangedAction.Remove'), [Add](ScriptChangedAction.md#Friflo.Engine.ECS.ScriptChangedAction.Add 'Friflo.Engine.ECS.ScriptChangedAction.Add') or [Replace](ScriptChangedAction.md#Friflo.Engine.ECS.ScriptChangedAction.Replace 'Friflo.Engine.ECS.ScriptChangedAction.Replace') script. |
| [StoreOwnership](StoreOwnership.md 'Friflo.Engine.ECS.StoreOwnership') | Describe the ownership state of an [Entity](Entity.md 'Friflo.Engine.ECS.Entity') |
| [TreeMembership](TreeMembership.md 'Friflo.Engine.ECS.TreeMembership') | Describe the membership of an [Entity](Entity.md 'Friflo.Engine.ECS.Entity') to the [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') tree graph. |
