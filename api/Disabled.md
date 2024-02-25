#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## Disabled Struct

If entity [Enabled](Entity.Enabled.md 'Friflo.Engine.ECS.Entity.Enabled') == false it is tagged with [Disabled](Disabled.md 'Friflo.Engine.ECS.Disabled').<br/>
Disabled entities are excluded from query results by default. To include use [WithDisabled()](ArchetypeQuery.WithDisabled().md 'Friflo.Engine.ECS.ArchetypeQuery.WithDisabled()').

```csharp
public struct Disabled :
Friflo.Engine.ECS.ITag
```

Implements [ITag](ITag.md 'Friflo.Engine.ECS.ITag')