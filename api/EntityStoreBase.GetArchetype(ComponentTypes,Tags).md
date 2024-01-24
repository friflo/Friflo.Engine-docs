#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStoreBase](EntityStoreBase.md 'Friflo.Engine.ECS.EntityStoreBase')

## EntityStoreBase.GetArchetype(ComponentTypes, Tags) Method

Return the [Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype') storing the specified [componentTypes](EntityStoreBase.GetArchetype(ComponentTypes,Tags).md#Friflo.Engine.ECS.EntityStoreBase.GetArchetype(Friflo.Engine.ECS.ComponentTypes,Friflo.Engine.ECS.Tags).componentTypes 'Friflo.Engine.ECS.EntityStoreBase.GetArchetype(Friflo.Engine.ECS.ComponentTypes, Friflo.Engine.ECS.Tags).componentTypes') and [tags](EntityStoreBase.GetArchetype(ComponentTypes,Tags).md#Friflo.Engine.ECS.EntityStoreBase.GetArchetype(Friflo.Engine.ECS.ComponentTypes,Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.EntityStoreBase.GetArchetype(Friflo.Engine.ECS.ComponentTypes, Friflo.Engine.ECS.Tags).tags').<br/>
The [Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype') is created if not already present.

```csharp
public Friflo.Engine.ECS.Archetype GetArchetype(in Friflo.Engine.ECS.ComponentTypes componentTypes, in Friflo.Engine.ECS.Tags tags=default(Friflo.Engine.ECS.Tags));
```
#### Parameters

<a name='Friflo.Engine.ECS.EntityStoreBase.GetArchetype(Friflo.Engine.ECS.ComponentTypes,Friflo.Engine.ECS.Tags).componentTypes'></a>

`componentTypes` [ComponentTypes](ComponentTypes.md 'Friflo.Engine.ECS.ComponentTypes')

<a name='Friflo.Engine.ECS.EntityStoreBase.GetArchetype(Friflo.Engine.ECS.ComponentTypes,Friflo.Engine.ECS.Tags).tags'></a>

`tags` [Tags](Tags.md 'Friflo.Engine.ECS.Tags')

#### Returns
[Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype')