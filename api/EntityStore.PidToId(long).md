#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

## EntityStore.PidToId(long) Method

```csharp
public int PidToId(long pid);
```
#### Parameters

<a name='Friflo.Engine.ECS.EntityStore.PidToId(long).pid'></a>

`pid` [System.Int64](https://docs.microsoft.com/en-us/dotnet/api/System.Int64 'System.Int64')

#### Returns
[System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')

### Remarks
Avoid using this method if store is initialized with [RandomPids](PidType.md#Friflo.Engine.ECS.PidType.RandomPids 'Friflo.Engine.ECS.PidType.RandomPids').<br/>
Instead use [Id](Entity.Id.md 'Friflo.Engine.ECS.Entity.Id') instead of [Pid](Entity.Pid.md 'Friflo.Engine.ECS.Entity.Pid') if possible
as this method performs a [System.Collections.Generic.Dictionary&lt;&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.Dictionary-2 'System.Collections.Generic.Dictionary`2') lookup.