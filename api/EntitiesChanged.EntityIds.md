#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[EntitiesChanged](EntitiesChanged.md#'Friflo.Engine.ECS.EntitiesChanged')

## EntitiesChanged.EntityIds Property

```csharp
public System.Collections.Generic.IReadOnlySet<int> EntityIds { get; }
```

#### Property Value
[System.Collections.Generic.IReadOnlySet&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlySet-1#'System.Collections.Generic.IReadOnlySet`1')[System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32#'System.Int32')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlySet-1#'System.Collections.Generic.IReadOnlySet`1')

### Remarks
Use [GetEntityById(int)](EntityStore.GetEntityById(int).md#'Friflo.Engine.ECS.EntityStore.GetEntityById(int)') to get the [Entity](Entity.md#'Friflo.Engine.ECS.Entity'). E.g.<br/>

```csharp
var entity = store.GetEntityById(args.EntityIds[]);
```