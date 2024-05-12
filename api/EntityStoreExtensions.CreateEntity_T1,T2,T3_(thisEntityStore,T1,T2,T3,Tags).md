#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStoreExtensions](EntityStoreExtensions.md 'Friflo.Engine.ECS.EntityStoreExtensions')

## EntityStoreExtensions.CreateEntity<T1,T2,T3>(this EntityStore, T1, T2, T3, Tags) Method

Create and return a new [Entity](Entity.md 'Friflo.Engine.ECS.Entity') with the passed components and [tags](EntityStoreExtensions.CreateEntity_T1,T2,T3_(thisEntityStore,T1,T2,T3,Tags).md#Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity<T1,T2,T3>(this Friflo.Engine.ECS.EntityStore, T1, T2, T3, Friflo.Engine.ECS.Tags).tags').

```csharp
public static Friflo.Engine.ECS.Entity CreateEntity<T1,T2,T3>(this Friflo.Engine.ECS.EntityStore store, T1 component1, T2 component2, T3 component3, in Friflo.Engine.ECS.Tags tags=default(Friflo.Engine.ECS.Tags))
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,Friflo.Engine.ECS.Tags).T1'></a>

`T1`

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,Friflo.Engine.ECS.Tags).T2'></a>

`T2`

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,Friflo.Engine.ECS.Tags).T3'></a>

`T3`
#### Parameters

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,Friflo.Engine.ECS.Tags).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,Friflo.Engine.ECS.Tags).component1'></a>

`component1` [T1](EntityStoreExtensions.CreateEntity_T1,T2,T3_(thisEntityStore,T1,T2,T3,Tags).md#Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,Friflo.Engine.ECS.Tags).T1 'Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity<T1,T2,T3>(this Friflo.Engine.ECS.EntityStore, T1, T2, T3, Friflo.Engine.ECS.Tags).T1')

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,Friflo.Engine.ECS.Tags).component2'></a>

`component2` [T2](EntityStoreExtensions.CreateEntity_T1,T2,T3_(thisEntityStore,T1,T2,T3,Tags).md#Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,Friflo.Engine.ECS.Tags).T2 'Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity<T1,T2,T3>(this Friflo.Engine.ECS.EntityStore, T1, T2, T3, Friflo.Engine.ECS.Tags).T2')

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,Friflo.Engine.ECS.Tags).component3'></a>

`component3` [T3](EntityStoreExtensions.CreateEntity_T1,T2,T3_(thisEntityStore,T1,T2,T3,Tags).md#Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,Friflo.Engine.ECS.Tags).T3 'Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity<T1,T2,T3>(this Friflo.Engine.ECS.EntityStore, T1, T2, T3, Friflo.Engine.ECS.Tags).T3')

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,Friflo.Engine.ECS.Tags).tags'></a>

`tags` [Tags](Tags.md 'Friflo.Engine.ECS.Tags')

#### Returns
[Entity](Entity.md 'Friflo.Engine.ECS.Entity')