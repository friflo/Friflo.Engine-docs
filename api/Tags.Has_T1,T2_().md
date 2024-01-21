#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[Tags](Tags.md 'Friflo.Engine.ECS.Tags')

## Tags.Has<T1,T2>() Method

Return true if the [Tags](Tags.md 'Friflo.Engine.ECS.Tags') contain the passed tags.

```csharp
public readonly bool Has<T1,T2>()
    where T1 : struct, Friflo.Engine.ECS.ITag, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.ITag, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.Tags.Has_T1,T2_().T1'></a>

`T1`

<a name='Friflo.Engine.ECS.Tags.Has_T1,T2_().T2'></a>

`T2`

#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')