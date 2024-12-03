#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityRelations&lt;TRelation&gt;](EntityRelations_TRelation_.md 'Friflo.Engine.ECS.EntityRelations<TRelation>')

## EntityRelations<TRelation>.Entities Property

Returns a collection of entities having one or more relation.<br/>
Executes in O(1).

```csharp
public Friflo.Engine.ECS.EntityReadOnlyCollection Entities { get; }
```

#### Property Value
[EntityReadOnlyCollection](EntityReadOnlyCollection.md 'Friflo.Engine.ECS.EntityReadOnlyCollection')

### Remarks
- The returned collection changes when relations are updated, removed or added.
- To get all entities including their relations (the cartesian product aka CROSS JOIN) use<br/>[Pairs](EntityRelations_TRelation_.Pairs.md 'Friflo.Engine.ECS.EntityRelations<TRelation>.Pairs')