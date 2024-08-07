#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

## EntityStore.CloneEntity(Entity) Method

Create and return a clone of the passed [entity](EntityStore.CloneEntity(Entity).md#Friflo.Engine.ECS.EntityStore.CloneEntity(Friflo.Engine.ECS.Entity).entity 'Friflo.Engine.ECS.EntityStore.CloneEntity(Friflo.Engine.ECS.Entity).entity') in the store.

```csharp
public Friflo.Engine.ECS.Entity CloneEntity(Friflo.Engine.ECS.Entity entity);
```
#### Parameters

<a name='Friflo.Engine.ECS.EntityStore.CloneEntity(Friflo.Engine.ECS.Entity).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

#### Returns
[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

### Remarks
Child entities of the passed [entity](EntityStore.CloneEntity(Entity).md#Friflo.Engine.ECS.EntityStore.CloneEntity(Friflo.Engine.ECS.Entity).entity 'Friflo.Engine.ECS.EntityStore.CloneEntity(Friflo.Engine.ECS.Entity).entity') are not copied to the cloned entity.<br/>
If doing this these child entities would be children of the passed entity <b>and</b> the clone.