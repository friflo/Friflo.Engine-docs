#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Systems](Friflo.Engine.ECS.Systems.md 'Friflo.Engine.ECS.Systems').[SystemPerf](SystemPerf.md 'Friflo.Engine.ECS.Systems.SystemPerf')

## SystemPerf.LastTicks Property

Return the duration of the last execution in timer ticks. <br/>
            Can be 0 in case execution time was below [System.Diagnostics.Stopwatch.Frequency](https://docs.microsoft.com/en-us/dotnet/api/System.Diagnostics.Stopwatch.Frequency 'System.Diagnostics.Stopwatch.Frequency') precision.

```csharp
public long LastTicks { get; }
```

#### Property Value
[System.Int64](https://docs.microsoft.com/en-us/dotnet/api/System.Int64 'System.Int64')