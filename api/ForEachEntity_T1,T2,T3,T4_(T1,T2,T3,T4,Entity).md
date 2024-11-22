#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## ForEachEntity<T1,T2,T3,T4>(T1, T2, T3, T4, Entity) Delegate

Provide the state of an [entity](ForEachEntity_T1,T2,T3,T4_(T1,T2,T3,T4,Entity).md#Friflo.Engine.ECS.ForEachEntity_T1,T2,T3,T4_(T1,T2,T3,T4,Friflo.Engine.ECS.Entity).entity 'Friflo.Engine.ECS.ForEachEntity<T1,T2,T3,T4>(T1, T2, T3, T4, Friflo.Engine.ECS.Entity).entity') within [ForEachEntity(ForEachEntity&lt;T1,T2,T3,T4&gt;)](ArchetypeQuery_T1,T2,T3,T4_.ForEachEntity(ForEachEntity_T1,T2,T3,T4_).md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4>.ForEachEntity(Friflo.Engine.ECS.ForEachEntity<T1,T2,T3,T4>)').

```csharp
public delegate void ForEachEntity<T1,T2,T3,T4>(ref T1 component1, ref T2 component2, ref T3 component3, ref T4 component4, Friflo.Engine.ECS.Entity entity)
    where T1 : struct, System.ValueType, System.ValueType
    where T2 : struct, System.ValueType, System.ValueType
    where T3 : struct, System.ValueType, System.ValueType
    where T4 : struct, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.ForEachEntity_T1,T2,T3,T4_(T1,T2,T3,T4,Friflo.Engine.ECS.Entity).T1'></a>

`T1`

<a name='Friflo.Engine.ECS.ForEachEntity_T1,T2,T3,T4_(T1,T2,T3,T4,Friflo.Engine.ECS.Entity).T2'></a>

`T2`

<a name='Friflo.Engine.ECS.ForEachEntity_T1,T2,T3,T4_(T1,T2,T3,T4,Friflo.Engine.ECS.Entity).T3'></a>

`T3`

<a name='Friflo.Engine.ECS.ForEachEntity_T1,T2,T3,T4_(T1,T2,T3,T4,Friflo.Engine.ECS.Entity).T4'></a>

`T4`
#### Parameters

<a name='Friflo.Engine.ECS.ForEachEntity_T1,T2,T3,T4_(T1,T2,T3,T4,Friflo.Engine.ECS.Entity).component1'></a>

`component1` [T1](ForEachEntity_T1,T2,T3,T4_(T1,T2,T3,T4,Entity).md#Friflo.Engine.ECS.ForEachEntity_T1,T2,T3,T4_(T1,T2,T3,T4,Friflo.Engine.ECS.Entity).T1 'Friflo.Engine.ECS.ForEachEntity<T1,T2,T3,T4>(T1, T2, T3, T4, Friflo.Engine.ECS.Entity).T1')

<a name='Friflo.Engine.ECS.ForEachEntity_T1,T2,T3,T4_(T1,T2,T3,T4,Friflo.Engine.ECS.Entity).component2'></a>

`component2` [T2](ForEachEntity_T1,T2,T3,T4_(T1,T2,T3,T4,Entity).md#Friflo.Engine.ECS.ForEachEntity_T1,T2,T3,T4_(T1,T2,T3,T4,Friflo.Engine.ECS.Entity).T2 'Friflo.Engine.ECS.ForEachEntity<T1,T2,T3,T4>(T1, T2, T3, T4, Friflo.Engine.ECS.Entity).T2')

<a name='Friflo.Engine.ECS.ForEachEntity_T1,T2,T3,T4_(T1,T2,T3,T4,Friflo.Engine.ECS.Entity).component3'></a>

`component3` [T3](ForEachEntity_T1,T2,T3,T4_(T1,T2,T3,T4,Entity).md#Friflo.Engine.ECS.ForEachEntity_T1,T2,T3,T4_(T1,T2,T3,T4,Friflo.Engine.ECS.Entity).T3 'Friflo.Engine.ECS.ForEachEntity<T1,T2,T3,T4>(T1, T2, T3, T4, Friflo.Engine.ECS.Entity).T3')

<a name='Friflo.Engine.ECS.ForEachEntity_T1,T2,T3,T4_(T1,T2,T3,T4,Friflo.Engine.ECS.Entity).component4'></a>

`component4` [T4](ForEachEntity_T1,T2,T3,T4_(T1,T2,T3,T4,Entity).md#Friflo.Engine.ECS.ForEachEntity_T1,T2,T3,T4_(T1,T2,T3,T4,Friflo.Engine.ECS.Entity).T4 'Friflo.Engine.ECS.ForEachEntity<T1,T2,T3,T4>(T1, T2, T3, T4, Friflo.Engine.ECS.Entity).T4')

<a name='Friflo.Engine.ECS.ForEachEntity_T1,T2,T3,T4_(T1,T2,T3,T4,Friflo.Engine.ECS.Entity).entity'></a>

`entity` [Entity](Entity.md 'Friflo.Engine.ECS.Entity')