#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ParallelJobRunner Class

Required for parallel - multi threaded - query job execution using [RunParallel()](QueryJob.RunParallel().md 'Friflo.Engine.ECS.QueryJob.RunParallel()').<br/>
See <a href="https://friflo.gitbook.io/friflo.engine.ecs/examples/optimization#parallel-query-job">Example.</a>

```csharp
public sealed class ParallelJobRunner :
System.IDisposable
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; ParallelJobRunner

Implements [System.IDisposable](https://docs.microsoft.com/en-us/dotnet/api/System.IDisposable 'System.IDisposable')

### Remarks
[ParallelJobRunner](ParallelJobRunner.md 'Friflo.Engine.ECS.ParallelJobRunner') is thread safe.<br/>
            The intention is to use the same instance for all jobs. E.g. the JobRunner assigned to the [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore').<br/>
            The job runner divide a job in multiple tasks each executed on its own core.<br/>
            This ensures high cache hit rate of code and data structures.<br/><br/><i>Constraint</i><br/>
            When executing nested jobs - running a job within another job - the nested job requires its own runner.<br/><br/>
            Performance related implementation goals:<br/>
            - Minimize calls to synchronization primitives.<br/>
            - Use cheap synchronization primitives such as:
              [System.Threading.ManualResetEventSlim](https://docs.microsoft.com/en-us/dotnet/api/System.Threading.ManualResetEventSlim 'System.Threading.ManualResetEventSlim'), [System.Threading.Interlocked](https://docs.microsoft.com/en-us/dotnet/api/System.Threading.Interlocked 'System.Threading.Interlocked') and [System.Threading.Volatile](https://docs.microsoft.com/en-us/dotnet/api/System.Threading.Volatile 'System.Threading.Volatile').<br/>
            - Minimize thread context switches caused by [System.Threading.ManualResetEventSlim](https://docs.microsoft.com/en-us/dotnet/api/System.Threading.ManualResetEventSlim 'System.Threading.ManualResetEventSlim') in case calling
              [System.Threading.ManualResetEventSlim.Wait](https://docs.microsoft.com/en-us/dotnet/api/System.Threading.ManualResetEventSlim.Wait 'System.Threading.ManualResetEventSlim.Wait') when the event is not signaled.<br/>
            Note: To analyze the amount of thread context switches use: Process Explorer > Column > CSwitch Delta.

| Constructors | |
| :--- | :--- |
| [ParallelJobRunner(int, string)](ParallelJobRunner.ParallelJobRunner(int,string).md 'Friflo.Engine.ECS.ParallelJobRunner.ParallelJobRunner(int, string)') | |

| Properties | |
| :--- | :--- |
| [IsDisposed](ParallelJobRunner.IsDisposed.md 'Friflo.Engine.ECS.ParallelJobRunner.IsDisposed') | |
| [ThreadCount](ParallelJobRunner.ThreadCount.md 'Friflo.Engine.ECS.ParallelJobRunner.ThreadCount') | |

| Methods | |
| :--- | :--- |
| [Dispose()](ParallelJobRunner.Dispose().md 'Friflo.Engine.ECS.ParallelJobRunner.Dispose()') | |
| [ToString()](ParallelJobRunner.ToString().md 'Friflo.Engine.ECS.ParallelJobRunner.ToString()') | |
