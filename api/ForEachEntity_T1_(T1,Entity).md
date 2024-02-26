#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ForEachEntity<T1>(T1, Entity) Delegate

Provide the state of an [entity](ForEachEntity_T1_(T1,Entity).md#Friflo.Engine.ECS.ForEachEntity_T1_(T1,Friflo.Engine.ECS.Entity).entity 'Friflo.Engine.ECS.ForEachEntity<T1>(T1, Friflo.Engine.ECS.Entity).entity') within [ForEachEntity(ForEachEntity&lt;T1&gt;)](ArchetypeQuery_T1_.ForEachEntity(ForEachEntity_T1_).md 'Friflo.Engine.ECS.ArchetypeQuery<T1>.ForEachEntity(Friflo.Engine.ECS.ForEachEntity<T1>)').

```csharp
public delegate void ForEachEntity<T1>(ref T1 component1, Friflo.Engine.ECS.Entity entity)
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.ForEachEntity_T1_(T1,Friflo.Engine.ECS.Entity).T1'></a>

`T1`
#### Parameters

<a name='Friflo.Engine.ECS.ForEachEntity_T1_(T1,Friflo.Engine.ECS.Entity).component1'></a>

`component1` [T1](ForEachEntity_T1_(T1,Entity).md#Friflo.Engine.ECS.ForEachEntity_T1_(T1,Friflo.Engine.ECS.Entity).T1 'Friflo.Engine.ECS.ForEachEntity<T1>(T1, Friflo.Engine.ECS.Entity).T1')

<a name='Friflo.Engine.ECS.ForEachEntity_T1_(T1,Friflo.Engine.ECS.Entity).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')