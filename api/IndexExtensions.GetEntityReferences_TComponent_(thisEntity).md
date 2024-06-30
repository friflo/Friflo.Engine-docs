#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[IndexExtensions](IndexExtensions.md 'Friflo.Engine.ECS.IndexExtensions')

## IndexExtensions.GetEntityReferences<TComponent>(this Entity) Method

Return the entities with a component link referencing this entity of the passed [ILinkComponent](ILinkComponent.md 'Friflo.Engine.ECS.ILinkComponent') type.<br/>
Executes in O(1).

```csharp
public static Friflo.Engine.ECS.Entities GetEntityReferences<TComponent>(this Friflo.Engine.ECS.Entity entity)
    where TComponent : struct, Friflo.Engine.ECS.ILinkComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.IndexExtensions.GetEntityReferences_TComponent_(thisFriflo.Engine.ECS.Entity).TComponent'></a>

`TComponent`
#### Parameters

<a name='Friflo.Engine.ECS.IndexExtensions.GetEntityReferences_TComponent_(thisFriflo.Engine.ECS.Entity).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

#### Returns
[Entities](Entities.md 'Friflo.Engine.ECS.Entities')

### Remarks
The method id a specialized version of [GetEntitiesWithComponentValue&lt;TComponent,TValue&gt;(this EntityStore, TValue)](IndexExtensions.GetEntitiesWithComponentValue_TComponent,TValue_(thisEntityStore,TValue).md 'Friflo.Engine.ECS.IndexExtensions.GetEntitiesWithComponentValue<TComponent,TValue>(this Friflo.Engine.ECS.EntityStore, TValue)')<br/>
using ` TComponent = IIndexedComponent<Entity>, TValue = Entity` and `value = this`.