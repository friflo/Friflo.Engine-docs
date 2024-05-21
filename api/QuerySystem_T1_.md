#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Systems](Friflo.Engine.ECS.Systems.md 'Friflo.Engine.ECS.Systems')

## QuerySystem<T1> Class

A query system returning entities with the specified component type via its [Query](QuerySystem_T1_.Query.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1>.Query') property.

```csharp
public abstract class QuerySystem<T1> : Friflo.Engine.ECS.Systems.QuerySystem
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.Systems.QuerySystem_T1_.T1'></a>

`T1`

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; [BaseSystem](BaseSystem.md 'Friflo.Engine.ECS.Systems.BaseSystem') &#129106; [QuerySystem](QuerySystem.md 'Friflo.Engine.ECS.Systems.QuerySystem') &#129106; QuerySystem<T1>

| Properties | |
| :--- | :--- |
| [Query](QuerySystem_T1_.Query.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1>.Query') | Return all entities matching the [Query](QuerySystem_T1_.Query.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1>.Query'). |

| Methods | |
| :--- | :--- |
| [ToString()](QuerySystem_T1_.ToString().md 'Friflo.Engine.ECS.Systems.QuerySystem<T1>.ToString()') | |
