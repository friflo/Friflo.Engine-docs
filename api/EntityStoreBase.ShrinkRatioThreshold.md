#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStoreBase](EntityStoreBase.md 'Friflo.Engine.ECS.EntityStoreBase')

## EntityStoreBase.ShrinkRatioThreshold Property

Shrink ratio threshold: ` Sum of all Archetype capacities / EntityStore entity count`. Default: 10<br/>   
If the current ratio is > [ShrinkRatioThreshold](EntityStoreBase.ShrinkRatioThreshold.md 'Friflo.Engine.ECS.EntityStoreBase.ShrinkRatioThreshold') archetype capacities are shrinked.

```csharp
public double ShrinkRatioThreshold { get; set; }
```

#### Property Value
[System.Double](https://docs.microsoft.com/en-us/dotnet/api/System.Double 'System.Double')