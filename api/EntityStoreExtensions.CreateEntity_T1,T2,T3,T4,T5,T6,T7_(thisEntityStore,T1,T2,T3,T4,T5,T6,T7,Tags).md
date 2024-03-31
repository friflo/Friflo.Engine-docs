#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStoreExtensions](EntityStoreExtensions.md 'Friflo.Engine.ECS.EntityStoreExtensions')

## EntityStoreExtensions.CreateEntity<T1,T2,T3,T4,T5,T6,T7>(this EntityStore, T1, T2, T3, T4, T5, T6, T7, Tags) Method

Create and return a new [Entity](Entity.md 'Friflo.Engine.ECS.Entity') with the passed components and [tags](EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisEntityStore,T1,T2,T3,T4,T5,T6,T7,Tags).md#Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity<T1,T2,T3,T4,T5,T6,T7>(this Friflo.Engine.ECS.EntityStore, T1, T2, T3, T4, T5, T6, T7, Friflo.Engine.ECS.Tags).tags').

```csharp
public static Friflo.Engine.ECS.Entity CreateEntity<T1,T2,T3,T4,T5,T6,T7>(this Friflo.Engine.ECS.EntityStore store, T1 component1, T2 component2, T3 component3, T4 component4, T5 component5, T6 component6, T7 component7, in Friflo.Engine.ECS.Tags tags=default(Friflo.Engine.ECS.Tags))
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T2 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T3 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T4 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T5 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T6 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType
    where T7 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).T1'></a>

`T1`

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).T2'></a>

`T2`

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).T3'></a>

`T3`

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).T4'></a>

`T4`

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).T5'></a>

`T5`

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).T6'></a>

`T6`

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).T7'></a>

`T7`
#### Parameters

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).component1'></a>

`component1` [T1](EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisEntityStore,T1,T2,T3,T4,T5,T6,T7,Tags).md#Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).T1 'Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity<T1,T2,T3,T4,T5,T6,T7>(this Friflo.Engine.ECS.EntityStore, T1, T2, T3, T4, T5, T6, T7, Friflo.Engine.ECS.Tags).T1')

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).component2'></a>

`component2` [T2](EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisEntityStore,T1,T2,T3,T4,T5,T6,T7,Tags).md#Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).T2 'Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity<T1,T2,T3,T4,T5,T6,T7>(this Friflo.Engine.ECS.EntityStore, T1, T2, T3, T4, T5, T6, T7, Friflo.Engine.ECS.Tags).T2')

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).component3'></a>

`component3` [T3](EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisEntityStore,T1,T2,T3,T4,T5,T6,T7,Tags).md#Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).T3 'Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity<T1,T2,T3,T4,T5,T6,T7>(this Friflo.Engine.ECS.EntityStore, T1, T2, T3, T4, T5, T6, T7, Friflo.Engine.ECS.Tags).T3')

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).component4'></a>

`component4` [T4](EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisEntityStore,T1,T2,T3,T4,T5,T6,T7,Tags).md#Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).T4 'Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity<T1,T2,T3,T4,T5,T6,T7>(this Friflo.Engine.ECS.EntityStore, T1, T2, T3, T4, T5, T6, T7, Friflo.Engine.ECS.Tags).T4')

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).component5'></a>

`component5` [T5](EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisEntityStore,T1,T2,T3,T4,T5,T6,T7,Tags).md#Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).T5 'Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity<T1,T2,T3,T4,T5,T6,T7>(this Friflo.Engine.ECS.EntityStore, T1, T2, T3, T4, T5, T6, T7, Friflo.Engine.ECS.Tags).T5')

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).component6'></a>

`component6` [T6](EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisEntityStore,T1,T2,T3,T4,T5,T6,T7,Tags).md#Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).T6 'Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity<T1,T2,T3,T4,T5,T6,T7>(this Friflo.Engine.ECS.EntityStore, T1, T2, T3, T4, T5, T6, T7, Friflo.Engine.ECS.Tags).T6')

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).component7'></a>

`component7` [T7](EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisEntityStore,T1,T2,T3,T4,T5,T6,T7,Tags).md#Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).T7 'Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity<T1,T2,T3,T4,T5,T6,T7>(this Friflo.Engine.ECS.EntityStore, T1, T2, T3, T4, T5, T6, T7, Friflo.Engine.ECS.Tags).T7')

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1,T2,T3,T4,T5,T6,T7_(thisFriflo.Engine.ECS.EntityStore,T1,T2,T3,T4,T5,T6,T7,Friflo.Engine.ECS.Tags).tags'></a>

`tags` [Tags](Tags.md 'Friflo.Engine.ECS.Tags')

#### Returns
[Entity](Entity.md 'Friflo.Engine.ECS.Entity')