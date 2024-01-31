#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ArchetypeQuery<T1,T2,T3,T4,T5> Class

```csharp
public sealed class ArchetypeQuery<T1,T2,T3,T4,T5> : Friflo.Engine.ECS.ArchetypeQuery
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T4 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T5 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3,T4,T5_.T1'></a>

`T1`

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3,T4,T5_.T2'></a>

`T2`

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3,T4,T5_.T3'></a>

`T3`

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3,T4,T5_.T4'></a>

`T4`

<a name='Friflo.Engine.ECS.ArchetypeQuery_T1,T2,T3,T4,T5_.T5'></a>

`T5`

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') &#129106; ArchetypeQuery<T1,T2,T3,T4,T5>

| Properties | |
| :--- | :--- |
| [Chunks](ArchetypeQuery_T1,T2,T3,T4,T5_.Chunks.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>.Chunks') | Return the [Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>')'s storing the components and entities of an [ArchetypeQuery&lt;T1,T2,T3,T4,T5&gt;](ArchetypeQuery_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>'). |

| Methods | |
| :--- | :--- |
| [AllComponents(ComponentTypes)](ArchetypeQuery_T1,T2,T3,T4,T5_.AllComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>.AllComponents(Friflo.Engine.ECS.ComponentTypes)') | |
| [AllTags(Tags)](ArchetypeQuery_T1,T2,T3,T4,T5_.AllTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>.AllTags(Friflo.Engine.ECS.Tags)') | |
| [AnyComponents(ComponentTypes)](ArchetypeQuery_T1,T2,T3,T4,T5_.AnyComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>.AnyComponents(Friflo.Engine.ECS.ComponentTypes)') | |
| [AnyTags(Tags)](ArchetypeQuery_T1,T2,T3,T4,T5_.AnyTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>.AnyTags(Friflo.Engine.ECS.Tags)') | |
| [ReadOnly&lt;T&gt;()](ArchetypeQuery_T1,T2,T3,T4,T5_.ReadOnly_T_().md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>.ReadOnly<T>()') | |
| [WithoutAllComponents(ComponentTypes)](ArchetypeQuery_T1,T2,T3,T4,T5_.WithoutAllComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes)') | |
| [WithoutAllTags(Tags)](ArchetypeQuery_T1,T2,T3,T4,T5_.WithoutAllTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>.WithoutAllTags(Friflo.Engine.ECS.Tags)') | |
| [WithoutAnyComponents(ComponentTypes)](ArchetypeQuery_T1,T2,T3,T4,T5_.WithoutAnyComponents(ComponentTypes).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>.WithoutAnyComponents(Friflo.Engine.ECS.ComponentTypes)') | |
| [WithoutAnyTags(Tags)](ArchetypeQuery_T1,T2,T3,T4,T5_.WithoutAnyTags(Tags).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>.WithoutAnyTags(Friflo.Engine.ECS.Tags)') | |
