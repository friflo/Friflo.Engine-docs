#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS.Serialize](Friflo.Engine.ECS.Serialize.md#'Friflo.Engine.ECS.Serialize').[DataEntity](DataEntity.md#'Friflo.Engine.ECS.Serialize.DataEntity')

## DataEntity.children Field

```csharp
public List<long> children;
```

#### Field Value
[System.Collections.Generic.List&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.List-1#'System.Collections.Generic.List`1')[System.Int64](https://docs.microsoft.com/en-us/dotnet/api/System.Int64#'System.Int64')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.List-1#'System.Collections.Generic.List`1')

### Remarks
Use a list of child ids instead of a single field `parentId` to enable child order.<br/><br/>
An alternative order implementation - using firstChild, nextSibling - is error prone if referenced nodes are missing.<br/>
For now the child order is required to enable a memorable order in the editor and to avoid merge conflicts.