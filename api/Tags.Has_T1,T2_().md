#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Tags](Tags.md 'Friflo.Engine.ECS.Tags')

## Tags.Has<T1,T2>() Method

Return true if it contains all passed [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') types
[T1](Tags.Has_T1,T2_().md#Friflo.Engine.ECS.Tags.Has_T1,T2_().T1 'Friflo.Engine.ECS.Tags.Has<T1,T2>().T1') and [T2](Tags.Has_T1,T2_().md#Friflo.Engine.ECS.Tags.Has_T1,T2_().T2 'Friflo.Engine.ECS.Tags.Has<T1,T2>().T2').

```csharp
public readonly bool Has<T1,T2>()
    where T1 : struct, Friflo.Engine.ECS.ITag, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.ITag, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Tags.Has_T1,T2_().T1'></a>

`T1`

<a name='Friflo.Engine.ECS.Tags.Has_T1,T2_().T2'></a>

`T2`

#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')