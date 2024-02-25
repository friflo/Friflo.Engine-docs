#### [Friflo.Engine.ECS](index.md#'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md#'Friflo.Engine.ECS').[Entity](Entity.md#'Friflo.Engine.ECS.Entity')

## Entity.TryGetScript<TScript>(TScript) Method

Gets the script with the passed [TScript](Entity.TryGetScript_TScript_(TScript).md#Friflo.Engine.ECS.Entity.TryGetScript_TScript_(TScript).TScript#'Friflo.Engine.ECS.Entity.TryGetScript<TScript>(TScript).TScript')[System.Type](https://docs.microsoft.com/en-us/dotnet/api/System.Type#'System.Type').

```csharp
public bool TryGetScript<TScript>(out TScript result)
    where TScript : Friflo.Engine.ECS.Script, new();
```
#### Type parameters

<a name='Friflo.Engine.ECS.Entity.TryGetScript_TScript_(TScript).TScript'></a>

`TScript`
#### Parameters

<a name='Friflo.Engine.ECS.Entity.TryGetScript_TScript_(TScript).result'></a>

`result` [TScript](Entity.TryGetScript_TScript_(TScript).md#Friflo.Engine.ECS.Entity.TryGetScript_TScript_(TScript).TScript#'Friflo.Engine.ECS.Entity.TryGetScript<TScript>(TScript).TScript')

#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean#'System.Boolean')  
Returns true if the entity has a script the passed [TScript](Entity.TryGetScript_TScript_(TScript).md#Friflo.Engine.ECS.Entity.TryGetScript_TScript_(TScript).TScript#'Friflo.Engine.ECS.Entity.TryGetScript<TScript>(TScript).TScript')[System.Type](https://docs.microsoft.com/en-us/dotnet/api/System.Type#'System.Type').<br/>
Otherwise false.