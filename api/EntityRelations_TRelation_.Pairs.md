#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityRelations&lt;TRelation&gt;](EntityRelations_TRelation_.md 'Friflo.Engine.ECS.EntityRelations<TRelation>')

## EntityRelations<TRelation>.Pairs Property

Return all entity relations as pairs. A pair is `(entities[i], relations[i])`<br/>
Executes in O(1).  Most efficient way to iterate all entity relations.

```csharp
public (Friflo.Engine.ECS.Entities entities,Friflo.Engine.ECS.Chunk<TRelation> relations) Pairs { get; }
```

#### Property Value
[&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.ValueTuple 'System.ValueTuple')[Entities](Entities.md 'Friflo.Engine.ECS.Entities')[,](https://docs.microsoft.com/en-us/dotnet/api/System.ValueTuple 'System.ValueTuple')[Friflo.Engine.ECS.Chunk&lt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>')[TRelation](EntityRelations_TRelation_.md#Friflo.Engine.ECS.EntityRelations_TRelation_.TRelation 'Friflo.Engine.ECS.EntityRelations<TRelation>.TRelation')[&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.ValueTuple 'System.ValueTuple')