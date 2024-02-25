#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[ComponentTypes](ComponentTypes.md#'Friflo.Engine.ECS.ComponentTypes')

## ComponentTypes.Get<T1,T2,T3>() Method

Create an instance containing the passed [IComponent](IComponent.md#'Friflo.Engine.ECS.IComponent') types
[T1](ComponentTypes.Get_T1,T2,T3_().md#Friflo.Engine.ECS.ComponentTypes.Get_T1,T2,T3_().T1#'Friflo.Engine.ECS.ComponentTypes.Get<T1,T2,T3>().T1'), [T2](ComponentTypes.Get_T1,T2,T3_().md#Friflo.Engine.ECS.ComponentTypes.Get_T1,T2,T3_().T2#'Friflo.Engine.ECS.ComponentTypes.Get<T1,T2,T3>().T2') and [T3](ComponentTypes.Get_T1,T2,T3_().md#Friflo.Engine.ECS.ComponentTypes.Get_T1,T2,T3_().T3#'Friflo.Engine.ECS.ComponentTypes.Get<T1,T2,T3>().T3').

```csharp
public static Friflo.Engine.ECS.ComponentTypes Get<T1,T2,T3>()
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.ComponentTypes.Get_T1,T2,T3_().T1'></a>

`T1`

<a name='Friflo.Engine.ECS.ComponentTypes.Get_T1,T2,T3_().T2'></a>

`T2`

<a name='Friflo.Engine.ECS.ComponentTypes.Get_T1,T2,T3_().T3'></a>

`T3`

#### Returns
[ComponentTypes](ComponentTypes.md#'Friflo.Engine.ECS.ComponentTypes')