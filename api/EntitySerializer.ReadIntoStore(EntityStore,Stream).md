#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Serialize](Friflo.Engine.ECS.Serialize.md 'Friflo.Engine.ECS.Serialize').[EntitySerializer](EntitySerializer.md 'Friflo.Engine.ECS.Serialize.EntitySerializer')

## EntitySerializer.ReadIntoStore(EntityStore, Stream) Method

Reads the JSON array of the given [stream](EntitySerializer.ReadIntoStore(EntityStore,Stream).md#Friflo.Engine.ECS.Serialize.EntitySerializer.ReadIntoStore(Friflo.Engine.ECS.EntityStore,System.IO.Stream).stream 'Friflo.Engine.ECS.Serialize.EntitySerializer.ReadIntoStore(Friflo.Engine.ECS.EntityStore, System.IO.Stream).stream') into the passed [store](EntitySerializer.ReadIntoStore(EntityStore,Stream).md#Friflo.Engine.ECS.Serialize.EntitySerializer.ReadIntoStore(Friflo.Engine.ECS.EntityStore,System.IO.Stream).store 'Friflo.Engine.ECS.Serialize.EntitySerializer.ReadIntoStore(Friflo.Engine.ECS.EntityStore, System.IO.Stream).store').

```csharp
public Friflo.Engine.ECS.Serialize.ReadResult ReadIntoStore(Friflo.Engine.ECS.EntityStore store, System.IO.Stream stream);
```
#### Parameters

<a name='Friflo.Engine.ECS.Serialize.EntitySerializer.ReadIntoStore(Friflo.Engine.ECS.EntityStore,System.IO.Stream).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

<a name='Friflo.Engine.ECS.Serialize.EntitySerializer.ReadIntoStore(Friflo.Engine.ECS.EntityStore,System.IO.Stream).stream'></a>

`stream` [System.IO.Stream](https://docs.microsoft.com/en-us/dotnet/api/System.IO.Stream 'System.IO.Stream')

#### Returns
[ReadResult](ReadResult.md 'Friflo.Engine.ECS.Serialize.ReadResult')