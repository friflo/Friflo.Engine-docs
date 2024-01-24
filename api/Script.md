#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## Script Class

To enable adding a script class to an [Entity](Entity.md 'Friflo.Engine.ECS.Entity') it need to extend [Script](Script.md 'Friflo.Engine.ECS.Script').

```csharp
public abstract class Script
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; Script

### Remarks
A [Script](Script.md 'Friflo.Engine.ECS.Script') is a reference type - a class-  which contains data <b>and</b> behavior - aka scripts / methods.<br/> 
An [Entity](Entity.md 'Friflo.Engine.ECS.Entity') can contain multiple [Script](Script.md 'Friflo.Engine.ECS.Script')'s but only one of each type.<br/>[Script](Script.md 'Friflo.Engine.ECS.Script')'s can be used if <b>OPP</b> programming approach is preferred
and dealing with less than a few 1.000 instances.<br/><br/>
Optionally attribute the extended class with [ComponentKeyAttribute](ComponentKeyAttribute.md 'Friflo.Engine.ECS.ComponentKeyAttribute')<br/>
to assign a custom component key name used for JSON serialization.<br/><br/><i>Info:</i> Its functionality is similar to a class extending `MonoBehaviour` added to a `GameObject` in Unity.

| Properties | |
| :--- | :--- |
| [Entity](Script.Entity.md 'Friflo.Engine.ECS.Script.Entity') | The entity the component is added to. Otherwise null. |
| [Store](Script.Store.md 'Friflo.Engine.ECS.Script.Store') | |
| [Systems](Script.Systems.md 'Friflo.Engine.ECS.Script.Systems') | |

| Methods | |
| :--- | :--- |
| [Start()](Script.Start().md 'Friflo.Engine.ECS.Script.Start()') | |
| [ToString()](Script.ToString().md 'Friflo.Engine.ECS.Script.ToString()') | |
| [Update()](Script.Update().md 'Friflo.Engine.ECS.Script.Update()') | |
