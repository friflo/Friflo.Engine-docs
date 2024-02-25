#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## StoreDispatcher Class

Contains methods to dispatch execution of [System.Action](https://docs.microsoft.com/en-us/dotnet/api/System.Action 'System.Action')'s or [System.Func&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-1 'System.Func`1')'s to the main thread.

```csharp
public static class StoreDispatcher
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; StoreDispatcher

### Remarks
These methods are required to access an [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore') as instances of this class are not thread safe. 
Note: This file may be moved to project: [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')
Method mapping for various UI application libraries.
- <b>AvaloniaUI</b> - methods map to `Avalonia.Threading.Dispatcher.UIThread` methods. <br/>
- <b>MAUI</b> - methods map to `Microsoft.Maui.ApplicationModel.MainThread` methods. <br/>
- <b>WinForms</b> - methods map to `System.Windows.Threading.Dispatcher` methods. <br/>

| Methods | |
| :--- | :--- |
| [AssertMainThread()](StoreDispatcher.AssertMainThread().md 'Friflo.Engine.ECS.StoreDispatcher.AssertMainThread()') | |
| [Invoke&lt;TResult&gt;(Func&lt;TResult&gt;)](StoreDispatcher.Invoke_TResult_(Func_TResult_).md 'Friflo.Engine.ECS.StoreDispatcher.Invoke<TResult>(System.Func<TResult>)') | |
| [InvokeAsync(Func&lt;Task&gt;)](StoreDispatcher.InvokeAsync(Func_Task_).md 'Friflo.Engine.ECS.StoreDispatcher.InvokeAsync(System.Func<System.Threading.Tasks.Task>)') | |
| [InvokeAsync&lt;TResult&gt;(Func&lt;Task&lt;TResult&gt;&gt;)](StoreDispatcher.InvokeAsync_TResult_(Func_Task_TResult__).md 'Friflo.Engine.ECS.StoreDispatcher.InvokeAsync<TResult>(System.Func<System.Threading.Tasks.Task<TResult>>)') | |
| [Post(Action)](StoreDispatcher.Post(Action).md 'Friflo.Engine.ECS.StoreDispatcher.Post(System.Action)') | |
| [SetDispatcher(IStoreDispatcher)](StoreDispatcher.SetDispatcher(IStoreDispatcher).md 'Friflo.Engine.ECS.StoreDispatcher.SetDispatcher(Friflo.Engine.ECS.IStoreDispatcher)') | |
