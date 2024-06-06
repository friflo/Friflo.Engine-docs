#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[ICommandBuffer](ICommandBuffer.md 'Friflo.Engine.ECS.ICommandBuffer')

## ICommandBuffer.SetComponent<T>(int, T) Method

```csharp
void SetComponent<T>(int entityId, in T component)
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.ICommandBuffer.SetComponent_T_(int,T).T'></a>

`T`
#### Parameters

<a name='Friflo.Engine.ECS.ICommandBuffer.SetComponent_T_(int,T).entityId'></a>

`entityId` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

<a name='Friflo.Engine.ECS.ICommandBuffer.SetComponent_T_(int,T).component'></a>

`component` [T](ICommandBuffer.SetComponent_T_(int,T).md#Friflo.Engine.ECS.ICommandBuffer.SetComponent_T_(int,T).T 'Friflo.Engine.ECS.ICommandBuffer.SetComponent<T>(int, T).T')