#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityData](EntityData.md 'Friflo.Engine.ECS.EntityData')

## EntityData.Tags Property

Return the [Tags](Tags.md 'Friflo.Engine.ECS.Tags') added to an entity.

```csharp
public Friflo.Engine.ECS.Tags Tags { get; }
```

#### Property Value
[Tags](Tags.md 'Friflo.Engine.ECS.Tags')

#### Exceptions

[System.NullReferenceException](https://docs.microsoft.com/en-us/dotnet/api/System.NullReferenceException 'System.NullReferenceException')  
if the entity is deleted.

### Remarks
Executes in O(1)