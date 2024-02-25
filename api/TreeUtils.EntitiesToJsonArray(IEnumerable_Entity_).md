#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS.Utils](Friflo.Engine.ECS.Utils.md#'Friflo.Engine.ECS.Utils').[TreeUtils](TreeUtils.md#'Friflo.Engine.ECS.Utils.TreeUtils')

## TreeUtils.EntitiesToJsonArray(IEnumerable<Entity>) Method

Create a JSON array from given [entities](TreeUtils.EntitiesToJsonArray(IEnumerable_Entity_).md#Friflo.Engine.ECS.Utils.TreeUtils.EntitiesToJsonArray(System.Collections.Generic.IEnumerable_Friflo.Engine.ECS.Entity_).entities#'Friflo.Engine.ECS.Utils.TreeUtils.EntitiesToJsonArray(System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.Entity>).entities') including their [ChildEntities](Entity.ChildEntities.md#'Friflo.Engine.ECS.Entity.ChildEntities').

```csharp
public static Friflo.Engine.ECS.Utils.JsonEntities EntitiesToJsonArray(System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.Entity> entities);
```
#### Parameters

<a name='Friflo.Engine.ECS.Utils.TreeUtils.EntitiesToJsonArray(System.Collections.Generic.IEnumerable_Friflo.Engine.ECS.Entity_).entities'></a>

`entities` [System.Collections.Generic.IEnumerable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1#'System.Collections.Generic.IEnumerable`1')[Entity](Entity.md#'Friflo.Engine.ECS.Entity')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1#'System.Collections.Generic.IEnumerable`1')

#### Returns
[JsonEntities](JsonEntities.md#'Friflo.Engine.ECS.Utils.JsonEntities')