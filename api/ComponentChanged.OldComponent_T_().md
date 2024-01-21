#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[ComponentChanged](ComponentChanged.md 'Friflo.Engine.ECS.ComponentChanged')

## ComponentChanged.OldComponent<T>() Method

Returns the old component value before executing [Update](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Update 'Friflo.Engine.ECS.ComponentChangedAction.Update')
or [Remove](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Remove 'Friflo.Engine.ECS.ComponentChangedAction.Remove') component.<br/><br/><b>Note</b>:
The [OldComponent&lt;T&gt;()](ComponentChanged.OldComponent_T_().md 'Friflo.Engine.ECS.ComponentChanged.OldComponent<T>()') return value is only valid within the event handler call.<br/>[ComponentChanged](ComponentChanged.md 'Friflo.Engine.ECS.ComponentChanged') may return an invalid value when calling it outside the event handler scope.<br/>
Instead store the value returned by [OldComponent&lt;T&gt;()](ComponentChanged.OldComponent_T_().md 'Friflo.Engine.ECS.ComponentChanged.OldComponent<T>()') within the handler when using it after the event handler returns.<br/>
Reason: For performance there is only one field per component type storing the old component value.<br/>

```csharp
public T OldComponent<T>()
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.ComponentChanged.OldComponent_T_().T'></a>

`T`

The component type of the changed component.

#### Returns
[T](ComponentChanged.OldComponent_T_().md#Friflo.Engine.ECS.ComponentChanged.OldComponent_T_().T 'Friflo.Engine.ECS.ComponentChanged.OldComponent<T>().T')

#### Exceptions

[System.InvalidOperationException](https://docs.microsoft.com/en-us/dotnet/api/System.InvalidOperationException 'System.InvalidOperationException')  
In case the [Action](ComponentChanged.Action.md 'Friflo.Engine.ECS.ComponentChanged.Action') was [Add](ComponentChangedAction.md#Friflo.Engine.ECS.ComponentChangedAction.Add 'Friflo.Engine.ECS.ComponentChangedAction.Add') component.

[System.ArgumentException](https://docs.microsoft.com/en-us/dotnet/api/System.ArgumentException 'System.ArgumentException')  
In case the component is accessed with the wrong generic type.