#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[Chunk&lt;T&gt;](Chunk_T_.md#'Friflo.Engine.ECS.Chunk<T>')

## Chunk<T>.AsSpan128<TTo>() Method

Return the components as a [System.Span&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Span-1#'System.Span`1') of type [TTo](Chunk_T_.AsSpan128_TTo_().md#Friflo.Engine.ECS.Chunk_T_.AsSpan128_TTo_().TTo#'Friflo.Engine.ECS.Chunk<T>.AsSpan128<TTo>().TTo').<br/>
The returned [System.Span&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Span-1#'System.Span`1') contains padding elements on its tail to enable assignment to Vector128{TTo}.<br/>
See <a href="https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md#query-vectorization---simd">Example.</a>.

```csharp
public System.Span<TTo> AsSpan128<TTo>()
    where TTo : struct, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Chunk_T_.AsSpan128_TTo_().TTo'></a>

`TTo`

#### Returns
[System.Span&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Span-1#'System.Span`1')[TTo](Chunk_T_.AsSpan128_TTo_().md#Friflo.Engine.ECS.Chunk_T_.AsSpan128_TTo_().TTo#'Friflo.Engine.ECS.Chunk<T>.AsSpan128<TTo>().TTo')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Span-1#'System.Span`1')