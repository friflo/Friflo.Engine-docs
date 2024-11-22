#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[CommandBuffer](CommandBuffer.md 'Friflo.Engine.ECS.CommandBuffer')

## CommandBuffer.SetComponent<T>(int, T) Method

Obsolete. Same behavior as `AddComponent(int,T)`.

```csharp
public void SetComponent<T>(int entityId, in T component)
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.CommandBuffer.SetComponent_T_(int,T).T'></a>

`T`
#### Parameters

<a name='Friflo.Engine.ECS.CommandBuffer.SetComponent_T_(int,T).entityId'></a>

`entityId` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

<a name='Friflo.Engine.ECS.CommandBuffer.SetComponent_T_(int,T).component'></a>

`component` [T](CommandBuffer.SetComponent_T_(int,T).md#Friflo.Engine.ECS.CommandBuffer.SetComponent_T_(int,T).T 'Friflo.Engine.ECS.CommandBuffer.SetComponent<T>(int, T).T')

Implements [SetComponent&lt;T&gt;(int, T)](ICommandBuffer.SetComponent_T_(int,T).md 'Friflo.Engine.ECS.ICommandBuffer.SetComponent<T>(int, T)')