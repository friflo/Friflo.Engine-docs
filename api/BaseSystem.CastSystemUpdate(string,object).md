#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Systems](Friflo.Engine.ECS.Systems.md 'Friflo.Engine.ECS.Systems').[BaseSystem](BaseSystem.md 'Friflo.Engine.ECS.Systems.BaseSystem')

## BaseSystem.CastSystemUpdate(string, object) Method

Send an event to [OnSystemChanged](BaseSystem.OnSystemChanged.md 'Friflo.Engine.ECS.Systems.BaseSystem.OnSystemChanged') handlers to notify a changed system [field](BaseSystem.CastSystemUpdate(string,object).md#Friflo.Engine.ECS.Systems.BaseSystem.CastSystemUpdate(string,object).field 'Friflo.Engine.ECS.Systems.BaseSystem.CastSystemUpdate(string, object).field').

```csharp
public void CastSystemUpdate(string field, object value);
```
#### Parameters

<a name='Friflo.Engine.ECS.Systems.BaseSystem.CastSystemUpdate(string,object).field'></a>

`field` [System.String](https://docs.microsoft.com/en-us/dotnet/api/System.String 'System.String')

<a name='Friflo.Engine.ECS.Systems.BaseSystem.CastSystemUpdate(string,object).value'></a>

`value` [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object')