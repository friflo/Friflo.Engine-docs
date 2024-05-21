#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Systems](Friflo.Engine.ECS.Systems.md 'Friflo.Engine.ECS.Systems').[SystemPerf](SystemPerf.md 'Friflo.Engine.ECS.Systems.SystemPerf')

## SystemPerf.LastMs Property

Return the duration of the last execution in milliseconds. <br/>
           Can be 0 in case execution time was below [System.Diagnostics.Stopwatch.Frequency](https://docs.microsoft.com/en-us/dotnet/api/System.Diagnostics.Stopwatch.Frequency 'System.Diagnostics.Stopwatch.Frequency') precision.

```csharp
public float LastMs { get; }
```

#### Property Value
[System.Single](https://docs.microsoft.com/en-us/dotnet/api/System.Single 'System.Single')