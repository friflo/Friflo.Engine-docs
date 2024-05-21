#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Systems](Friflo.Engine.ECS.Systems.md 'Friflo.Engine.ECS.Systems')

## SystemPerf Struct

Provide performance statics of system execution.

```csharp
public struct SystemPerf
```

| Properties | |
| :--- | :--- |
| [LastMs](SystemPerf.LastMs.md 'Friflo.Engine.ECS.Systems.SystemPerf.LastMs') | Return the duration of the last execution in milliseconds. <br/>            Can be 0 in case execution time was below [System.Diagnostics.Stopwatch.Frequency](https://docs.microsoft.com/en-us/dotnet/api/System.Diagnostics.Stopwatch.Frequency 'System.Diagnostics.Stopwatch.Frequency') precision. |
| [LastTicks](SystemPerf.LastTicks.md 'Friflo.Engine.ECS.Systems.SystemPerf.LastTicks') | Return the duration of the last execution in timer ticks. <br/>             Can be 0 in case execution time was below [System.Diagnostics.Stopwatch.Frequency](https://docs.microsoft.com/en-us/dotnet/api/System.Diagnostics.Stopwatch.Frequency 'System.Diagnostics.Stopwatch.Frequency') precision. |
| [SumMs](SystemPerf.SumMs.md 'Friflo.Engine.ECS.Systems.SystemPerf.SumMs') | Return the sum of all execution times in milliseconds. |
| [SumTicks](SystemPerf.SumTicks.md 'Friflo.Engine.ECS.Systems.SystemPerf.SumTicks') | Return the sum of all execution times in timer ticks. |
| [UpdateCount](SystemPerf.UpdateCount.md 'Friflo.Engine.ECS.Systems.SystemPerf.UpdateCount') | Return the number of system executions. |

| Methods | |
| :--- | :--- |
| [LastAvgMs(int)](SystemPerf.LastAvgMs(int).md 'Friflo.Engine.ECS.Systems.SystemPerf.LastAvgMs(int)') | Return the average duration of the last [count](SystemPerf.LastAvgMs(int).md#Friflo.Engine.ECS.Systems.SystemPerf.LastAvgMs(int).count 'Friflo.Engine.ECS.Systems.SystemPerf.LastAvgMs(int).count') executions in milliseconds. |
| [ToString()](SystemPerf.ToString().md 'Friflo.Engine.ECS.Systems.SystemPerf.ToString()') | |
