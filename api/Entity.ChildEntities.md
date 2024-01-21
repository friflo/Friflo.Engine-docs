#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.ChildEntities Property

Return all child entities of an entity.

```csharp
public Friflo.Engine.ECS.ChildEntities ChildEntities { get; }
```

#### Property Value
[ChildEntities](ChildEntities.md 'Friflo.Engine.ECS.ChildEntities')

### Remarks
Return all child entities of an entity. Enumerate with: 

```csharp
foreach (var child in entity.ChildEntities)
```
Executes in O(1)