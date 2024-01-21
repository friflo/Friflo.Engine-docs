#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Entity](Entity.md 'Friflo.Engine.ECS.Entity')

## Entity.TryGetScript<T>(T) Method

```csharp
public bool TryGetScript<T>(out T result)
    where T : Friflo.Engine.ECS.Script;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Entity.TryGetScript_T_(T).T'></a>

`T`
#### Parameters

<a name='Friflo.Engine.ECS.Entity.TryGetScript_T_(T).result'></a>

`result` [T](Entity.TryGetScript_T_(T).md#Friflo.Engine.ECS.Entity.TryGetScript_T_(T).T 'Friflo.Engine.ECS.Entity.TryGetScript<T>(T).T')

#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
true if the entity has a [Script](Script.md 'Friflo.Engine.ECS.Script') of Type [T](Entity.TryGetScript_T_(T).md#Friflo.Engine.ECS.Entity.TryGetScript_T_(T).T 'Friflo.Engine.ECS.Entity.TryGetScript<T>(T).T'). Otherwise false