#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[CollectionExtensions](CollectionExtensions.md 'Friflo.Engine.ECS.CollectionExtensions')

## CollectionExtensions.Debug<T>(this Chunk<T>) Method

Returns a string containing the [System.Object.ToString](https://docs.microsoft.com/en-us/dotnet/api/System.Object.ToString 'System.Object.ToString') for each component.<br/>
E.g `"{ 1, 3, 7 }"`

```csharp
public static string Debug<T>(this Friflo.Engine.ECS.Chunk<T> chunk)
    where T : struct, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.CollectionExtensions.Debug_T_(thisFriflo.Engine.ECS.Chunk_T_).T'></a>

`T`
#### Parameters

<a name='Friflo.Engine.ECS.CollectionExtensions.Debug_T_(thisFriflo.Engine.ECS.Chunk_T_).chunk'></a>

`chunk` [Friflo.Engine.ECS.Chunk&lt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>')[T](CollectionExtensions.Debug_T_(thisChunk_T_).md#Friflo.Engine.ECS.CollectionExtensions.Debug_T_(thisFriflo.Engine.ECS.Chunk_T_).T 'Friflo.Engine.ECS.CollectionExtensions.Debug<T>(this Friflo.Engine.ECS.Chunk<T>).T')[&gt;](Chunk_T_.md 'Friflo.Engine.ECS.Chunk<T>')

#### Returns
[System.String](https://docs.microsoft.com/en-us/dotnet/api/System.String 'System.String')