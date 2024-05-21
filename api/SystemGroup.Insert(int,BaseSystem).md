#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Systems](Friflo.Engine.ECS.Systems.md 'Friflo.Engine.ECS.Systems').[SystemGroup](SystemGroup.md 'Friflo.Engine.ECS.Systems.SystemGroup')

## SystemGroup.Insert(int, BaseSystem) Method

Adds the passed [system](SystemGroup.Insert(int,BaseSystem).md#Friflo.Engine.ECS.Systems.SystemGroup.Insert(int,Friflo.Engine.ECS.Systems.BaseSystem).system 'Friflo.Engine.ECS.Systems.SystemGroup.Insert(int, Friflo.Engine.ECS.Systems.BaseSystem).system') at the given [index](SystemGroup.Insert(int,BaseSystem).md#Friflo.Engine.ECS.Systems.SystemGroup.Insert(int,Friflo.Engine.ECS.Systems.BaseSystem).index 'Friflo.Engine.ECS.Systems.SystemGroup.Insert(int, Friflo.Engine.ECS.Systems.BaseSystem).index') to the group.<br/>
If [index](SystemGroup.Insert(int,BaseSystem).md#Friflo.Engine.ECS.Systems.SystemGroup.Insert(int,Friflo.Engine.ECS.Systems.BaseSystem).index 'Friflo.Engine.ECS.Systems.SystemGroup.Insert(int, Friflo.Engine.ECS.Systems.BaseSystem).index') == -1 the system is added to the tail of the group.

```csharp
public void Insert(int index, Friflo.Engine.ECS.Systems.BaseSystem system);
```
#### Parameters

<a name='Friflo.Engine.ECS.Systems.SystemGroup.Insert(int,Friflo.Engine.ECS.Systems.BaseSystem).index'></a>

`index` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

<a name='Friflo.Engine.ECS.Systems.SystemGroup.Insert(int,Friflo.Engine.ECS.Systems.BaseSystem).system'></a>

`system` [BaseSystem](BaseSystem.md 'Friflo.Engine.ECS.Systems.BaseSystem')