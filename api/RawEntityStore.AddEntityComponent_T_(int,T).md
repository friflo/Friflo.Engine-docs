#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[RawEntityStore](RawEntityStore.md 'Friflo.Engine.ECS.RawEntityStore')

## RawEntityStore.AddEntityComponent<T>(int, T) Method

```csharp
public Friflo.Engine.ECS.ComponentChangedAction AddEntityComponent<T>(int id, in T component)
    where T : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.RawEntityStore.AddEntityComponent_T_(int,T).T'></a>

`T`
#### Parameters

<a name='Friflo.Engine.ECS.RawEntityStore.AddEntityComponent_T_(int,T).id'></a>

`id` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

<a name='Friflo.Engine.ECS.RawEntityStore.AddEntityComponent_T_(int,T).component'></a>

`component` [T](RawEntityStore.AddEntityComponent_T_(int,T).md#Friflo.Engine.ECS.RawEntityStore.AddEntityComponent_T_(int,T).T 'Friflo.Engine.ECS.RawEntityStore.AddEntityComponent<T>(int, T).T')

#### Returns
[ComponentChangedAction](ComponentChangedAction.md 'Friflo.Engine.ECS.ComponentChangedAction')