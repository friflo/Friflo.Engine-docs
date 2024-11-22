#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Systems](Friflo.Engine.ECS.Systems.md 'Friflo.Engine.ECS.Systems').[QuerySystemBase](QuerySystemBase.md 'Friflo.Engine.ECS.Systems.QuerySystemBase')

## QuerySystemBase.Filter Property

A query filter used to restrict the entities returned by its `Query` property.<br/>
See remarks to add a tag filter to a custom `QuerySystem`.

```csharp
public Friflo.Engine.ECS.QueryFilter Filter { get; }
```

#### Property Value
[QueryFilter](QueryFilter.md 'Friflo.Engine.ECS.QueryFilter')

### Remarks
Additional tag filters can be added in the constructor of a class extending a `QuerySystem`.

```csharp
class MySystem : QuerySystem<Scale3>
{
    public MySystem() => Filter.AnyTags(Tags.Get<MyTag>()); 
    protected override void OnUpdate() { ... }
}
```