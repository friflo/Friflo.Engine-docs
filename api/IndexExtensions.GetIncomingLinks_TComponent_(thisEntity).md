#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[IndexExtensions](IndexExtensions.md 'Friflo.Engine.ECS.IndexExtensions')

## IndexExtensions.GetIncomingLinks<TComponent>(this Entity) Method

Return the entities with a link component referencing the [target](IndexExtensions.GetIncomingLinks_TComponent_(thisEntity).md#Friflo.Engine.ECS.IndexExtensions.GetIncomingLinks_TComponent_(thisFriflo.Engine.ECS.Entity).target 'Friflo.Engine.ECS.IndexExtensions.GetIncomingLinks<TComponent>(this Friflo.Engine.ECS.Entity).target') entity of the passed [ILinkComponent](ILinkComponent.md 'Friflo.Engine.ECS.ILinkComponent') type.<br/>
Executes in O(1).

```csharp
public static Friflo.Engine.ECS.EntityLinks<TComponent> GetIncomingLinks<TComponent>(this Friflo.Engine.ECS.Entity target)
    where TComponent : struct, Friflo.Engine.ECS.ILinkComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.IndexExtensions.GetIncomingLinks_TComponent_(thisFriflo.Engine.ECS.Entity).TComponent'></a>

`TComponent`
#### Parameters

<a name='Friflo.Engine.ECS.IndexExtensions.GetIncomingLinks_TComponent_(thisFriflo.Engine.ECS.Entity).target'></a>

`target` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')

#### Returns
[Friflo.Engine.ECS.EntityLinks&lt;](EntityLinks_T_.md 'Friflo.Engine.ECS.EntityLinks<T>')[TComponent](IndexExtensions.GetIncomingLinks_TComponent_(thisEntity).md#Friflo.Engine.ECS.IndexExtensions.GetIncomingLinks_TComponent_(thisFriflo.Engine.ECS.Entity).TComponent 'Friflo.Engine.ECS.IndexExtensions.GetIncomingLinks<TComponent>(this Friflo.Engine.ECS.Entity).TComponent')[&gt;](EntityLinks_T_.md 'Friflo.Engine.ECS.EntityLinks<T>')

#### Exceptions

[System.NullReferenceException](https://docs.microsoft.com/en-us/dotnet/api/System.NullReferenceException 'System.NullReferenceException')  
If the entity is null.