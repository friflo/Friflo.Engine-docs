#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStoreBase](EntityStoreBase.md 'Friflo.Engine.ECS.EntityStoreBase')

## EntityStoreBase.FindArchetype(ComponentTypes, Tags) Method

Return the [Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype') storing the specified [componentTypes](EntityStoreBase.FindArchetype(ComponentTypes,Tags).md#Friflo.Engine.ECS.EntityStoreBase.FindArchetype(Friflo.Engine.ECS.ComponentTypes,Friflo.Engine.ECS.Tags).componentTypes 'Friflo.Engine.ECS.EntityStoreBase.FindArchetype(Friflo.Engine.ECS.ComponentTypes, Friflo.Engine.ECS.Tags).componentTypes') and [tags](EntityStoreBase.FindArchetype(ComponentTypes,Tags).md#Friflo.Engine.ECS.EntityStoreBase.FindArchetype(Friflo.Engine.ECS.ComponentTypes,Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.EntityStoreBase.FindArchetype(Friflo.Engine.ECS.ComponentTypes, Friflo.Engine.ECS.Tags).tags').<br/>

```csharp
public Friflo.Engine.ECS.Archetype FindArchetype(in Friflo.Engine.ECS.ComponentTypes componentTypes, in Friflo.Engine.ECS.Tags tags);
```
#### Parameters

<a name='Friflo.Engine.ECS.EntityStoreBase.FindArchetype(Friflo.Engine.ECS.ComponentTypes,Friflo.Engine.ECS.Tags).componentTypes'></a>

`componentTypes` [ComponentTypes](ComponentTypes.md 'Friflo.Engine.ECS.ComponentTypes')

<a name='Friflo.Engine.ECS.EntityStoreBase.FindArchetype(Friflo.Engine.ECS.ComponentTypes,Friflo.Engine.ECS.Tags).tags'></a>

`tags` [Tags](Tags.md 'Friflo.Engine.ECS.Tags')

#### Returns
[Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype')  
null if the [Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype') is not present.