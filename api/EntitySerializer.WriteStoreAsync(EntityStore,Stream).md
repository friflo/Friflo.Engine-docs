#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Serialize](Friflo.Engine.ECS.Serialize.md 'Friflo.Engine.ECS.Serialize').[EntitySerializer](EntitySerializer.md 'Friflo.Engine.ECS.Serialize.EntitySerializer')

## EntitySerializer.WriteStoreAsync(EntityStore, Stream) Method

Asynchronously writes all entities in the given [store](EntitySerializer.WriteStoreAsync(EntityStore,Stream).md#Friflo.Engine.ECS.Serialize.EntitySerializer.WriteStoreAsync(Friflo.Engine.ECS.EntityStore,System.IO.Stream).store 'Friflo.Engine.ECS.Serialize.EntitySerializer.WriteStoreAsync(Friflo.Engine.ECS.EntityStore, System.IO.Stream).store') as a JSON array to the passed [stream](EntitySerializer.WriteStoreAsync(EntityStore,Stream).md#Friflo.Engine.ECS.Serialize.EntitySerializer.WriteStoreAsync(Friflo.Engine.ECS.EntityStore,System.IO.Stream).stream 'Friflo.Engine.ECS.Serialize.EntitySerializer.WriteStoreAsync(Friflo.Engine.ECS.EntityStore, System.IO.Stream).stream').

```csharp
public System.Threading.Tasks.Task WriteStoreAsync(Friflo.Engine.ECS.EntityStore store, System.IO.Stream stream);
```
#### Parameters

<a name='Friflo.Engine.ECS.Serialize.EntitySerializer.WriteStoreAsync(Friflo.Engine.ECS.EntityStore,System.IO.Stream).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

<a name='Friflo.Engine.ECS.Serialize.EntitySerializer.WriteStoreAsync(Friflo.Engine.ECS.EntityStore,System.IO.Stream).stream'></a>

`stream` [System.IO.Stream](https://docs.microsoft.com/en-us/dotnet/api/System.IO.Stream 'System.IO.Stream')

#### Returns
[System.Threading.Tasks.Task](https://docs.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.Task 'System.Threading.Tasks.Task')