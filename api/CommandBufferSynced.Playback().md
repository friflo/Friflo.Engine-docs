#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[CommandBufferSynced](CommandBufferSynced.md 'Friflo.Engine.ECS.CommandBufferSynced')

## CommandBufferSynced.Playback() Method

Execute recorded entity changes. [Playback()](CommandBufferSynced.Playback().md 'Friflo.Engine.ECS.CommandBufferSynced.Playback()') must be called on the <b>main</b> thread.<br/>
See <a href="https://friflo.gitbook.io/friflo.engine.ecs/examples/optimization#commandbuffer">Example.</a>

```csharp
public void Playback();
```

Implements [Playback()](ICommandBuffer.Playback().md 'Friflo.Engine.ECS.ICommandBuffer.Playback()')

#### Exceptions

[System.InvalidOperationException](https://docs.microsoft.com/en-us/dotnet/api/System.InvalidOperationException 'System.InvalidOperationException')  
When recording commands after calling [Playback()](CommandBufferSynced.Playback().md 'Friflo.Engine.ECS.CommandBufferSynced.Playback()').<br/>