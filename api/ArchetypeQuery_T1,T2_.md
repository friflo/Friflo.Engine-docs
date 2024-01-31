#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ArchetypeQuery<T1,T2> Class

```csharp
public sealed class ArchetypeQuery<T1,T2> : Friflo.Engine.ECS.ArchetypeQuery
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2_.T1'></a>

`T1`

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2_.T2'></a>

`T2`

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') &#129106; ArchetypeQuery<T1,T2>

| Properties | |
| :--- | :--- |
| [Chunks](ArchetypeQuery_T1,T2_.Chunks.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>.Chunks') | Return the [Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>')'s storing the components and entities of an [ArchetypeQuery&lt;T1,T2&gt;](ArchetypeQuery_T1,T2_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>'). |

| Methods | |
| :--- | :--- |
| [AllComponents(ComponentTypes)](ArchetypeQuery_T1,T2_.AllComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>.AllComponents(Friflo.Engine.ECS.ComponentTypes)') | |
| [AllTags(Tags)](ArchetypeQuery_T1,T2_.AllTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>.AllTags(Friflo.Engine.ECS.Tags)') | |
| [AnyComponents(ComponentTypes)](ArchetypeQuery_T1,T2_.AnyComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>.AnyComponents(Friflo.Engine.ECS.ComponentTypes)') | |
| [AnyTags(Tags)](ArchetypeQuery_T1,T2_.AnyTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>.AnyTags(Friflo.Engine.ECS.Tags)') | |
| [ReadOnly&lt;T&gt;()](ArchetypeQuery_T1,T2_.ReadOnly_T_().md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>.ReadOnly<T>()') | |
| [WithoutAllComponents(ComponentTypes)](ArchetypeQuery_T1,T2_.WithoutAllComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes)') | |
| [WithoutAllTags(Tags)](ArchetypeQuery_T1,T2_.WithoutAllTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>.WithoutAllTags(Friflo.Engine.ECS.Tags)') | |
| [WithoutAnyComponents(ComponentTypes)](ArchetypeQuery_T1,T2_.WithoutAnyComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>.WithoutAnyComponents(Friflo.Engine.ECS.ComponentTypes)') | |
| [WithoutAnyTags(Tags)](ArchetypeQuery_T1,T2_.WithoutAnyTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2>.WithoutAnyTags(Friflo.Engine.ECS.Tags)') | |
