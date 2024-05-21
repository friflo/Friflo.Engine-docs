#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Systems](Friflo.Engine.ECS.Systems.md 'Friflo.Engine.ECS.Systems').[SystemExtensions](SystemExtensions.md 'Friflo.Engine.ECS.Systems.SystemExtensions')

## SystemExtensions.GetMatchingSystems(this SystemGroup, Archetype, List<SystemMatch>, bool) Method

Return the systems of a [SystemGroup](SystemGroup.md 'Friflo.Engine.ECS.Systems.SystemGroup') matching the passed [archetype](SystemExtensions.GetMatchingSystems(thisSystemGroup,Archetype,List_SystemMatch_,bool).md#Friflo.Engine.ECS.Systems.SystemExtensions.GetMatchingSystems(thisFriflo.Engine.ECS.Systems.SystemGroup,Friflo.Engine.ECS.Archetype,System.Collections.Generic.List_Friflo.Engine.ECS.Systems.SystemMatch_,bool).archetype 'Friflo.Engine.ECS.Systems.SystemExtensions.GetMatchingSystems(this Friflo.Engine.ECS.Systems.SystemGroup, Friflo.Engine.ECS.Archetype, System.Collections.Generic.List<Friflo.Engine.ECS.Systems.SystemMatch>, bool).archetype').

```csharp
public static void GetMatchingSystems(this Friflo.Engine.ECS.Systems.SystemGroup systemGroup, Friflo.Engine.ECS.Archetype archetype, System.Collections.Generic.List<Friflo.Engine.ECS.Systems.SystemMatch> target, bool addGroups);
```
#### Parameters

<a name='Friflo.Engine.ECS.Systems.SystemExtensions.GetMatchingSystems(thisFriflo.Engine.ECS.Systems.SystemGroup,Friflo.Engine.ECS.Archetype,System.Collections.Generic.List_Friflo.Engine.ECS.Systems.SystemMatch_,bool).systemGroup'></a>

`systemGroup` [SystemGroup](SystemGroup.md 'Friflo.Engine.ECS.Systems.SystemGroup')

<a name='Friflo.Engine.ECS.Systems.SystemExtensions.GetMatchingSystems(thisFriflo.Engine.ECS.Systems.SystemGroup,Friflo.Engine.ECS.Archetype,System.Collections.Generic.List_Friflo.Engine.ECS.Systems.SystemMatch_,bool).archetype'></a>

`archetype` [Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype')

<a name='Friflo.Engine.ECS.Systems.SystemExtensions.GetMatchingSystems(thisFriflo.Engine.ECS.Systems.SystemGroup,Friflo.Engine.ECS.Archetype,System.Collections.Generic.List_Friflo.Engine.ECS.Systems.SystemMatch_,bool).target'></a>

`target` [System.Collections.Generic.List&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.List-1 'System.Collections.Generic.List`1')[SystemMatch](SystemMatch.md 'Friflo.Engine.ECS.Systems.SystemMatch')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.List-1 'System.Collections.Generic.List`1')

<a name='Friflo.Engine.ECS.Systems.SystemExtensions.GetMatchingSystems(thisFriflo.Engine.ECS.Systems.SystemGroup,Friflo.Engine.ECS.Archetype,System.Collections.Generic.List_Friflo.Engine.ECS.Systems.SystemMatch_,bool).addGroups'></a>

`addGroups` [System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')