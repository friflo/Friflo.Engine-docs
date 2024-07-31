#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

## EntityStore.RecycleIds Property

If true (default) ids of deleted entities are recycled when creating new entities.<br/>
If false every new entity gets its own unique id. As a result the store capacity will always grow over time.

```csharp
public bool RecycleIds { get; set; }
```

#### Property Value
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')