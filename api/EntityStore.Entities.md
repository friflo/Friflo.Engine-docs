#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

## EntityStore.Entities Property

Return all [Entity](Entity.md 'Friflo.Engine.ECS.Entity')'s stored in the [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore').

```csharp
public Friflo.Engine.ECS.QueryEntities Entities { get; }
```

#### Property Value
[QueryEntities](QueryEntities.md 'Friflo.Engine.ECS.QueryEntities')

### Remarks
Property is mainly used for debugging.<br/>
            For efficient access to entity [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent')'s use one of the generic <b>
  <c>EntityStore.Query()</c>
</b> methods.