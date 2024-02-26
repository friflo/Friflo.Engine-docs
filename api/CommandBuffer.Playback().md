#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[CommandBuffer](CommandBuffer.md 'Friflo.Engine.ECS.CommandBuffer')

## CommandBuffer.Playback() Method

Execute recorded entity changes. [Playback()](CommandBuffer.Playback().md 'Friflo.Engine.ECS.CommandBuffer.Playback()') must be called on the <b>main</b> thread.<br/>
See <a href="https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md#commandbuffer">Example.</a>

```csharp
public void Playback();
```

#### Exceptions

[System.InvalidOperationException](https://docs.microsoft.com/en-us/dotnet/api/System.InvalidOperationException 'System.InvalidOperationException')  
When recording commands after calling [Playback()](CommandBuffer.Playback().md 'Friflo.Engine.ECS.CommandBuffer.Playback()').<br/>
To reuse a [CommandBuffer](CommandBuffer.md 'Friflo.Engine.ECS.CommandBuffer') instance set [ReuseBuffer](CommandBuffer.ReuseBuffer.md 'Friflo.Engine.ECS.CommandBuffer.ReuseBuffer') = true.