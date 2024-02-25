#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStoreBase](EntityStoreBase.md 'Friflo.Engine.ECS.EntityStoreBase')

## EntityStoreBase.Query<T1,T2,T3,T4,T5>() Method

Create a reusable [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery') for the given component types.<br/>
See <a href="https://github.com/friflo/Friflo.Json.Fliox/blob/main/Engine/README.md#query-entities">Example.</a>

```csharp
public Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5> Query<T1,T2,T3,T4,T5>()
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T4 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T5 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3,T4,T5_().T1'></a>

`T1`

<a name='Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3,T4,T5_().T2'></a>

`T2`

<a name='Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3,T4,T5_().T3'></a>

`T3`

<a name='Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3,T4,T5_().T4'></a>

`T4`

<a name='Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3,T4,T5_().T5'></a>

`T5`

#### Returns
[Friflo.Engine.ECS.ArchetypeQuery&lt;](ArchetypeQuery_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>')[T1](EntityStoreBase.Query_T1,T2,T3,T4,T5_().md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3,T4,T5_().T1 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3,T4,T5>().T1')[,](ArchetypeQuery_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>')[T2](EntityStoreBase.Query_T1,T2,T3,T4,T5_().md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3,T4,T5_().T2 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3,T4,T5>().T2')[,](ArchetypeQuery_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>')[T3](EntityStoreBase.Query_T1,T2,T3,T4,T5_().md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3,T4,T5_().T3 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3,T4,T5>().T3')[,](ArchetypeQuery_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>')[T4](EntityStoreBase.Query_T1,T2,T3,T4,T5_().md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3,T4,T5_().T4 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3,T4,T5>().T4')[,](ArchetypeQuery_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>')[T5](EntityStoreBase.Query_T1,T2,T3,T4,T5_().md#Friflo.Engine.ECS.EntityStoreBase.Query_T1,T2,T3,T4,T5_().T5 'Friflo.Engine.ECS.EntityStoreBase.Query<T1,T2,T3,T4,T5>().T5')[&gt;](ArchetypeQuery_T1,T2,T3,T4,T5_.md 'Friflo.Engine.ECS.ArchetypeQuery<T1,T2,T3,T4,T5>')