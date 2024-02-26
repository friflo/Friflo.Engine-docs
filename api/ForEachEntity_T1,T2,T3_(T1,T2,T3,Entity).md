#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ForEachEntity<T1,T2,T3>(T1, T2, T3, Entity) Delegate

Provide the state of an [entity](ForEachEntity_T1,T2,T3_(T1,T2,T3,Entity).md#Friflo.Engine.ECS.ForEachEntity_T1,T2,T3_(T1,T2,T3,Friflo.Engine.ECS.Entity).entity 'Friflo.Engine.ECS.ForEachEntity<T1,T2,T3>(T1, T2, T3, Friflo.Engine.ECS.Entity).entity') within [ForEachEntity(ForEachEntity&lt;T1,T2,T3&gt;)](ArchetypeQuery_T1,T2,T3_.ForEachEntity(ForEachEntity_T1,T2,T3_).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3>.ForEachEntity(Friflo.Engine.ECS.ForEachEntity<T1,T2,T3>)').

```csharp
public delegate void ForEachEntity<T1,T2,T3>(ref T1 component1, ref T2 component2, ref T3 component3, Friflo.Engine.ECS.Entity entity)
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.ForEachEntity_T1,T2,T3_(T1,T2,T3,Friflo.Engine.ECS.Entity).T1'></a>

`T1`

<a name='Friflo.Engine.ECS.ForEachEntity_T1,T2,T3_(T1,T2,T3,Friflo.Engine.ECS.Entity).T2'></a>

`T2`

<a name='Friflo.Engine.ECS.ForEachEntity_T1,T2,T3_(T1,T2,T3,Friflo.Engine.ECS.Entity).T3'></a>

`T3`
#### Parameters

<a name='Friflo.Engine.ECS.ForEachEntity_T1,T2,T3_(T1,T2,T3,Friflo.Engine.ECS.Entity).component1'></a>

`component1` [T1](ForEachEntity_T1,T2,T3_(T1,T2,T3,Entity).md#Friflo.Engine.ECS.ForEachEntity_T1,T2,T3_(T1,T2,T3,Friflo.Engine.ECS.Entity).T1 'Friflo.Engine.ECS.ForEachEntity<T1,T2,T3>(T1, T2, T3, Friflo.Engine.ECS.Entity).T1')

<a name='Friflo.Engine.ECS.ForEachEntity_T1,T2,T3_(T1,T2,T3,Friflo.Engine.ECS.Entity).component2'></a>

`component2` [T2](ForEachEntity_T1,T2,T3_(T1,T2,T3,Entity).md#Friflo.Engine.ECS.ForEachEntity_T1,T2,T3_(T1,T2,T3,Friflo.Engine.ECS.Entity).T2 'Friflo.Engine.ECS.ForEachEntity<T1,T2,T3>(T1, T2, T3, Friflo.Engine.ECS.Entity).T2')

<a name='Friflo.Engine.ECS.ForEachEntity_T1,T2,T3_(T1,T2,T3,Friflo.Engine.ECS.Entity).component3'></a>

`component3` [T3](ForEachEntity_T1,T2,T3_(T1,T2,T3,Entity).md#Friflo.Engine.ECS.ForEachEntity_T1,T2,T3_(T1,T2,T3,Friflo.Engine.ECS.Entity).T3 'Friflo.Engine.ECS.ForEachEntity<T1,T2,T3>(T1, T2, T3, Friflo.Engine.ECS.Entity).T3')

<a name='Friflo.Engine.ECS.ForEachEntity_T1,T2,T3_(T1,T2,T3,Friflo.Engine.ECS.Entity).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')