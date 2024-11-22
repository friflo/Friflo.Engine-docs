#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Archetype](Archetype.md 'Friflo.Engine.ECS.Archetype')

## Archetype.Components<TComponent>() Method

Return the components of the specified [TComponent](Archetype.Components_TComponent_().md#Friflo.Engine.ECS.Archetype.Components_TComponent_().TComponent 'Friflo.Engine.ECS.Archetype.Components<TComponent>().TComponent') type stored in the archetype.

```csharp
public System.Span<TComponent> Components<TComponent>()
    where TComponent : struct, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Archetype.Components_TComponent_().TComponent'></a>

`TComponent`

#### Returns
[System.Span&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Span-1 'System.Span`1')[TComponent](Archetype.Components_TComponent_().md#Friflo.Engine.ECS.Archetype.Components_TComponent_().TComponent 'Friflo.Engine.ECS.Archetype.Components<TComponent>().TComponent')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Span-1 'System.Span`1')