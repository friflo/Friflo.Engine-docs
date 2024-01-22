#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[ComponentTypes](ComponentTypes.md 'Friflo.Engine.ECS.ComponentTypes')

## ComponentTypes.Has<T1,T2>() Method

Return true if it contains all passed [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') types
[T1](ComponentTypes.Has_T1,T2_().md#Friflo.Engine.ECS.ComponentTypes.Has_T1,T2_().T1 'Friflo.Engine.ECS.ComponentTypes.Has<T1,T2>().T1') and [T2](ComponentTypes.Has_T1,T2_().md#Friflo.Engine.ECS.ComponentTypes.Has_T1,T2_().T2 'Friflo.Engine.ECS.ComponentTypes.Has<T1,T2>().T2').

```csharp
public readonly bool Has<T1,T2>()
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.ComponentTypes.Has_T1,T2_().T1'></a>

`T1`

<a name='Friflo.Engine.ECS.ComponentTypes.Has_T1,T2_().T2'></a>

`T2`

#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')