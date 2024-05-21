#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Systems](Friflo.Engine.ECS.Systems.md 'Friflo.Engine.ECS.Systems').[BaseSystem](BaseSystem.md 'Friflo.Engine.ECS.Systems.BaseSystem')

## BaseSystem.MoveSystemTo(SystemGroup, int) Method

Move the system to the specified [targetGroup](BaseSystem.MoveSystemTo(SystemGroup,int).md#Friflo.Engine.ECS.Systems.BaseSystem.MoveSystemTo(Friflo.Engine.ECS.Systems.SystemGroup,int).targetGroup 'Friflo.Engine.ECS.Systems.BaseSystem.MoveSystemTo(Friflo.Engine.ECS.Systems.SystemGroup, int).targetGroup') at the given [index](BaseSystem.MoveSystemTo(SystemGroup,int).md#Friflo.Engine.ECS.Systems.BaseSystem.MoveSystemTo(Friflo.Engine.ECS.Systems.SystemGroup,int).index 'Friflo.Engine.ECS.Systems.BaseSystem.MoveSystemTo(Friflo.Engine.ECS.Systems.SystemGroup, int).index').<br/>
If [index](BaseSystem.MoveSystemTo(SystemGroup,int).md#Friflo.Engine.ECS.Systems.BaseSystem.MoveSystemTo(Friflo.Engine.ECS.Systems.SystemGroup,int).index 'Friflo.Engine.ECS.Systems.BaseSystem.MoveSystemTo(Friflo.Engine.ECS.Systems.SystemGroup, int).index') is -1 the system is moved to the tail of the group.

```csharp
public int MoveSystemTo(Friflo.Engine.ECS.Systems.SystemGroup targetGroup, int index);
```
#### Parameters

<a name='Friflo.Engine.ECS.Systems.BaseSystem.MoveSystemTo(Friflo.Engine.ECS.Systems.SystemGroup,int).targetGroup'></a>

`targetGroup` [SystemGroup](SystemGroup.md 'Friflo.Engine.ECS.Systems.SystemGroup')

<a name='Friflo.Engine.ECS.Systems.BaseSystem.MoveSystemTo(Friflo.Engine.ECS.Systems.SystemGroup,int).index'></a>

`index` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

#### Returns
[System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')