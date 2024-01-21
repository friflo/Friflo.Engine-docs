#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## Chunk<T> Struct

A [Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>') is container of <b>struct</b> components of Type [T](Chunk_T_.md#Friflo.Engine.ECS.Chunk_T_.T 'Friflo.Engine.ECS.Chunk<T>.T').

```csharp
public readonly struct Chunk<T>
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.Chunk_T_.T'></a>

`T`

[IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') type of a struct component.

### Remarks
[Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>')'s are typically returned a [ArchetypeQuery&lt;T1&gt;](ArchetypeQuery_T1_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1>').[Chunks](ArchetypeQuery_T1_.Chunks.md 'Friflo.Engine.ECS.ArchetypeQuery<T1>.Chunks') enumerator.<br/><br/>
            Its items can be accessed or changed with [this[int]](Chunk_T_.this[int].md 'Friflo.Engine.ECS.Chunk<T>.this[int]') or [Span](Chunk_T_.Span.md 'Friflo.Engine.ECS.Chunk<T>.Span').<br/>
            The [Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>') implementation also support <b>vectorization</b>
            of <a href="https://github.com/dotnet/runtime/blob/main/docs/coding-guidelines/vectorization-guidelines.md">Vector types</a><br/>
            by [AsSpan128&lt;TTo&gt;()](Chunk_T_.AsSpan128_TTo_().md 'Friflo.Engine.ECS.Chunk<T>.AsSpan128<TTo>()'), [AsSpan256&lt;TTo&gt;()](Chunk_T_.AsSpan256_TTo_().md 'Friflo.Engine.ECS.Chunk<T>.AsSpan256<TTo>()') and [AsSpan512&lt;TTo&gt;()](Chunk_T_.AsSpan512_TTo_().md 'Friflo.Engine.ECS.Chunk<T>.AsSpan512<TTo>()').
            <br/><br/><i>See vectorization example</i> at [AsSpan256&lt;TTo&gt;()](Chunk_T_.AsSpan256_TTo_().md 'Friflo.Engine.ECS.Chunk<T>.AsSpan256<TTo>()').

| Fields | |
| :--- | :--- |
| [Length](Chunk_T_.Length.md 'Friflo.Engine.ECS.Chunk<T>.Length') | |

| Properties | |
| :--- | :--- |
| [Span](Chunk_T_.Span.md 'Friflo.Engine.ECS.Chunk<T>.Span') | |
| [StepSpan128](Chunk_T_.StepSpan128.md 'Friflo.Engine.ECS.Chunk<T>.StepSpan128') | The step value in a for loop when converting a [AsSpan128&lt;TTo&gt;()](Chunk_T_.AsSpan128_TTo_().md 'Friflo.Engine.ECS.Chunk<T>.AsSpan128<TTo>()') value to a [System.Runtime.Intrinsics.Vector128&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Runtime.Intrinsics.Vector128-1 'System.Runtime.Intrinsics.Vector128`1')<br/><br/> See example at [AsSpan256&lt;TTo&gt;()](Chunk_T_.AsSpan256_TTo_().md 'Friflo.Engine.ECS.Chunk<T>.AsSpan256<TTo>()'). |
| [StepSpan256](Chunk_T_.StepSpan256.md 'Friflo.Engine.ECS.Chunk<T>.StepSpan256') | The step value in a for loop when converting a [AsSpan256&lt;TTo&gt;()](Chunk_T_.AsSpan256_TTo_().md 'Friflo.Engine.ECS.Chunk<T>.AsSpan256<TTo>()') value to a [System.Runtime.Intrinsics.Vector256&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Runtime.Intrinsics.Vector256-1 'System.Runtime.Intrinsics.Vector256`1')<br/><br/> See example at [AsSpan256&lt;TTo&gt;()](Chunk_T_.AsSpan256_TTo_().md 'Friflo.Engine.ECS.Chunk<T>.AsSpan256<TTo>()'). |
| [StepSpan512](Chunk_T_.StepSpan512.md 'Friflo.Engine.ECS.Chunk<T>.StepSpan512') | The step value in a for loop when converting a [AsSpan512&lt;TTo&gt;()](Chunk_T_.AsSpan512_TTo_().md 'Friflo.Engine.ECS.Chunk<T>.AsSpan512<TTo>()') value to a `Vector512{T}`<br/><br/> See example at [AsSpan256&lt;TTo&gt;()](Chunk_T_.AsSpan256_TTo_().md 'Friflo.Engine.ECS.Chunk<T>.AsSpan256<TTo>()'). |
| [this[int]](Chunk_T_.this[int].md 'Friflo.Engine.ECS.Chunk<T>.this[int]') | |

| Methods | |
| :--- | :--- |
| [AsSpan128&lt;TTo&gt;()](Chunk_T_.AsSpan128_TTo_().md 'Friflo.Engine.ECS.Chunk<T>.AsSpan128<TTo>()') | Return the components as a [System.Span&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Span-1 'System.Span`1') of type <typeparam name="TTo"/>.<br/> The returned [System.Span&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Span-1 'System.Span`1') contains padding elements on its tail to enable assignment to [System.Runtime.Intrinsics.Vector128&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Runtime.Intrinsics.Vector128-1 'System.Runtime.Intrinsics.Vector128`1'). <br/><br/> See example at [AsSpan256&lt;TTo&gt;()](Chunk_T_.AsSpan256_TTo_().md 'Friflo.Engine.ECS.Chunk<T>.AsSpan256<TTo>()'). |
| [AsSpan256&lt;TTo&gt;()](Chunk_T_.AsSpan256_TTo_().md 'Friflo.Engine.ECS.Chunk<T>.AsSpan256<TTo>()') | Return the components as a [System.Span&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Span-1 'System.Span`1') of type <typeparam name="TTo"/> - which can be assigned to [System.Runtime.Intrinsics.Vector256&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Runtime.Intrinsics.Vector256-1 'System.Runtime.Intrinsics.Vector256`1')'s.<br/> The returned [System.Span&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Span-1 'System.Span`1') contains padding elements on its tail to enable safe conversion to a [System.Runtime.Intrinsics.Vector256&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Runtime.Intrinsics.Vector256-1 'System.Runtime.Intrinsics.Vector256`1'). |
| [AsSpan512&lt;TTo&gt;()](Chunk_T_.AsSpan512_TTo_().md 'Friflo.Engine.ECS.Chunk<T>.AsSpan512<TTo>()') | Return the components as a [System.Span&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Span-1 'System.Span`1') of type <typeparam name="TTo"/>.<br/> The returned [System.Span&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Span-1 'System.Span`1') contains padding elements on its tail to enable assignment to Vector512. <br/><br/> See example at [AsSpan256&lt;TTo&gt;()](Chunk_T_.AsSpan256_TTo_().md 'Friflo.Engine.ECS.Chunk<T>.AsSpan256<TTo>()'). |
| [ToString()](Chunk_T_.ToString().md 'Friflo.Engine.ECS.Chunk<T>.ToString()') | |