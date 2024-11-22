#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Systems](Friflo.Engine.ECS.Systems.md 'Friflo.Engine.ECS.Systems')

## QuerySystem<T1,T2,T3> Class

A query system returning entities with the specified component types via its [Query](QuerySystem_T1,T2,T3_.Query.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1,T2,T3>.Query') property.

```csharp
public abstract class QuerySystem<T1,T2,T3> : Friflo.Engine.ECS.Systems.QuerySystemBase
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
```
#### Type parameters

<a name='Friflo.Engine.ECS.Systems.QuerySystem_T1,T2,T3_.T1'></a>

`T1`

<a name='Friflo.Engine.ECS.Systems.QuerySystem_T1,T2,T3_.T2'></a>

`T2`

<a name='Friflo.Engine.ECS.Systems.QuerySystem_T1,T2,T3_.T3'></a>

`T3`

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; [BaseSystem](BaseSystem.md 'Friflo.Engine.ECS.Systems.BaseSystem') &#129106; [QuerySystemBase](QuerySystemBase.md 'Friflo.Engine.ECS.Systems.QuerySystemBase') &#129106; QuerySystem<T1,T2,T3>

| Properties | |
| :--- | :--- |
| [Query](QuerySystem_T1,T2,T3_.Query.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1,T2,T3>.Query') | Return all entities matching the [Query](QuerySystem_T1,T2,T3_.Query.md 'Friflo.Engine.ECS.Systems.QuerySystem<T1,T2,T3>.Query'). |

| Methods | |
| :--- | :--- |
| [ToString()](QuerySystem_T1,T2,T3_.ToString().md 'Friflo.Engine.ECS.Systems.QuerySystem<T1,T2,T3>.ToString()') | |
