#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Chunk&lt;T&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>')

## Chunk<T>.AsSpan256<TTo>() Method

Return the components as a [System.Span&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Span-1 'System.Span`1') of type [TTo](Chunk_T_.AsSpan256_TTo_().md#Friflo.Engine.ECS.Chunk_T_.AsSpan256_TTo_().TTo 'Friflo.Engine.ECS.Chunk<T>.AsSpan256<TTo>().TTo') - which can be assigned to [System.Runtime.Intrinsics.Vector256&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Runtime.Intrinsics.Vector256-1 'System.Runtime.Intrinsics.Vector256`1')'s.<br/>
The returned [System.Span&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Span-1 'System.Span`1') contains padding elements on its tail to enable safe conversion to a [System.Runtime.Intrinsics.Vector256&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Runtime.Intrinsics.Vector256-1 'System.Runtime.Intrinsics.Vector256`1').

```csharp
public System.Span<TTo> AsSpan256<TTo>()
    where TTo : struct, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Chunk_T_.AsSpan256_TTo_().TTo'></a>

`TTo`

#### Returns
[System.Span&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Span-1 'System.Span`1')[TTo](Chunk_T_.AsSpan256_TTo_().md#Friflo.Engine.ECS.Chunk_T_.AsSpan256_TTo_().TTo 'Friflo.Engine.ECS.Chunk<T>.AsSpan256<TTo>().TTo')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Span-1 'System.Span`1')

### Remarks
By adding padding elements the returned [System.Span&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Span-1 'System.Span`1') can be converted to [System.Runtime.Intrinsics.Vector256](https://docs.microsoft.com/en-us/dotnet/api/System.Runtime.Intrinsics.Vector256 'System.Runtime.Intrinsics.Vector256')'s <br/>
without the need of an additional <b>for</b> loop to process the elements at the tail of the [System.Span&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Span-1 'System.Span`1').<br/><br/><i>Vectorization example:</i><br/>

```csharp
// e.g. using: struct ByteComponent : IComponent { public byte value; }
var add = Vector256.Create<byte>(1);                // create byte[32] vector - all values = 1
foreach (var (component, _) in query.Chunks)
{    
    var bytes   = component.AsSpan256<byte>();      // bytes.Length - multiple of 32
    var step    = component.StepSpan256;            // step = 32
    for (int n = 0; n < bytes.Length; n += step) {
        var slice   = bytes.Slice(n, step);
        var value   = Vector256.Create<byte>(slice);
        var result  = Vector256.Add(value, add);    // execute 32 add instructions at once
        result.CopyTo(slice);
    }
}
```