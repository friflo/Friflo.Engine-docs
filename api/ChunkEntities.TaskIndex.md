#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[ChunkEntities](ChunkEntities.md 'Friflo.Engine.ECS.ChunkEntities')

## ChunkEntities.TaskIndex Field

if    0 - The entities are provided from the main (caller) thread using `foreach(...)` loop,
[Run()](QueryJob.Run().md 'Friflo.Engine.ECS.QueryJob.Run()') or [RunParallel()](QueryJob.RunParallel().md 'Friflo.Engine.ECS.QueryJob.RunParallel()').<br/>
if >= 1 - The entities are provided from a worker thread using [RunParallel()](QueryJob.RunParallel().md 'Friflo.Engine.ECS.QueryJob.RunParallel()').

```csharp
public readonly byte TaskIndex;
```

#### Field Value
[System.Byte](https://docs.microsoft.com/en-us/dotnet/api/System.Byte 'System.Byte')