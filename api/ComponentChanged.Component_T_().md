#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[ComponentChanged](ComponentChanged.md 'Friflo.Engine.ECS.ComponentChanged')

## ComponentChanged.Component<T>() Method

Returns the current component value after executing the [Add](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Add 'Friflo.Engine.ECS.ComponentChangedAction.Add')
or [Update](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Update 'Friflo.Engine.ECS.ComponentChangedAction.Update') component.<br/>

```csharp
public T Component<T>()
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.ComponentChanged.Component_T_().T'></a>

`T`

The component type of the changed component.

#### Returns
[T](ComponentChanged.Component_T_().md#Friflo.Engine.ECS.ComponentChanged.Component_T_().T 'Friflo.Engine.ECS.ComponentChanged.Component<T>().T')

#### Exceptions

[System.InvalidOperationException](https://docs.microsoft.com/en-us/dotnet/api/System.InvalidOperationException 'System.InvalidOperationException')  
In case the [Action](ComponentChanged.Action.md 'Friflo.Engine.ECS.ComponentChanged.Action') was [Remove](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Remove 'Friflo.Engine.ECS.ComponentChangedAction.Remove') component.

[System.ArgumentException](https://docs.microsoft.com/en-us/dotnet/api/System.ArgumentException 'System.ArgumentException')  
In case the component is accessed with the wrong generic type.