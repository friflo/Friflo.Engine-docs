#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[ComponentTypes](ComponentTypes.md 'Friflo.Engine.ECS.ComponentTypes')

## ComponentTypes.Get<T1,T2>() Method

Create an instance containing the passed [IComponent](IComponent.md 'Friflo.Engine.ECS.IComponent') types
[T1](ComponentTypes.Get_T1,T2_().md#Friflo.Engine.ECS.ComponentTypes.Get_T1,T2_().T1 'Friflo.Engine.ECS.ComponentTypes.Get<T1,T2>().T1') and [T2](ComponentTypes.Get_T1,T2_().md#Friflo.Engine.ECS.ComponentTypes.Get_T1,T2_().T2 'Friflo.Engine.ECS.ComponentTypes.Get<T1,T2>().T2').

```csharp
public static Friflo.Engine.ECS.ComponentTypes Get<T1,T2>()
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.ComponentTypes.Get_T1,T2_().T1'></a>

`T1`

<a name='Friflo.Engine.ECS.ComponentTypes.Get_T1,T2_().T2'></a>

`T2`

#### Returns
[ComponentTypes](ComponentTypes.md 'Friflo.Engine.ECS.ComponentTypes')