#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery')

## ArchetypeQuery.WithoutAnyTags(Tags) Method

Entities having any of the passed [tags](ArchetypeQuery.WithoutAnyTags(Tags).md#Friflo.Engine.ECS.ArchetypeQuery.WithoutAnyTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.ArchetypeQuery.WithoutAnyTags(Friflo.Engine.ECS.Tags).tags') are excluded from query result.

```csharp
public Friflo.Engine.ECS.ArchetypeQuery WithoutAnyTags(in Friflo.Engine.ECS.Tags tags);
```
#### Parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery.WithoutAnyTags(Friflo.Engine.ECS.Tags).tags'></a>

`tags` [Tags](Tags.md 'Friflo.Engine.ECS.Tags')

Use `Tags.Get<>()` to set the parameter.

#### Returns
[ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery')