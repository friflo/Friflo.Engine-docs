#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS')

## BatchAlreadyReturnedException Class

Is thrown if using a batch returned by [Batch(bool)](EntityStoreBase.Batch(bool).md#'Friflo.Engine.ECS.EntityStoreBase.Batch(bool)') with autoReturn: true<br/>
after calling [CreateEntity()](CreateEntityBatch.CreateEntity().md#'Friflo.Engine.ECS.CreateEntityBatch.CreateEntity()').

```csharp
public class BatchAlreadyReturnedException : System.InvalidOperationException
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object#'System.Object') &#129106; [System.Exception](https://docs.microsoft.com/en-us/dotnet/api/System.Exception#'System.Exception') &#129106; [System.SystemException](https://docs.microsoft.com/en-us/dotnet/api/System.SystemException#'System.SystemException') &#129106; [System.InvalidOperationException](https://docs.microsoft.com/en-us/dotnet/api/System.InvalidOperationException#'System.InvalidOperationException') &#129106; BatchAlreadyReturnedException