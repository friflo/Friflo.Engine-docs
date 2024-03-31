#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS').[EntityStoreExtensions](EntityStoreExtensions.md 'Friflo.Engine.ECS.EntityStoreExtensions')

## EntityStoreExtensions.CreateEntity<T1>(this EntityStore, T1, Tags) Method

Create and return a new [Entity](Entity.md 'Friflo.Engine.ECS.Entity') with the passed component and [tags](EntityStoreExtensions.CreateEntity_T1_(thisEntityStore,T1,Tags).md#Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1_(thisFriflo.Engine.ECS.EntityStore,T1,Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity<T1>(this Friflo.Engine.ECS.EntityStore, T1, Friflo.Engine.ECS.Tags).tags').

```csharp
public static Friflo.Engine.ECS.Entity CreateEntity<T1>(this Friflo.Engine.ECS.EntityStore store, T1 component, in Friflo.Engine.ECS.Tags tags=default(Friflo.Engine.ECS.Tags))
    where T1 : struct, Friflo.Engine.ECS.IComponent, System.ValueType, System.ValueType;
```
#### Type parameters

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1_(thisFriflo.Engine.ECS.EntityStore,T1,Friflo.Engine.ECS.Tags).T1'></a>

`T1`
#### Parameters

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1_(thisFriflo.Engine.ECS.EntityStore,T1,Friflo.Engine.ECS.Tags).store'></a>

`store` [EntityStore](EntityStore.md 'Friflo.Engine.ECS.EntityStore')

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1_(thisFriflo.Engine.ECS.EntityStore,T1,Friflo.Engine.ECS.Tags).component'></a>

`component` [T1](EntityStoreExtensions.CreateEntity_T1_(thisEntityStore,T1,Tags).md#Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1_(thisFriflo.Engine.ECS.EntityStore,T1,Friflo.Engine.ECS.Tags).T1 'Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity<T1>(this Friflo.Engine.ECS.EntityStore, T1, Friflo.Engine.ECS.Tags).T1')

<a name='Friflo.Engine.ECS.EntityStoreExtensions.CreateEntity_T1_(thisFriflo.Engine.ECS.EntityStore,T1,Friflo.Engine.ECS.Tags).tags'></a>

`tags` [Tags](Tags.md 'Friflo.Engine.ECS.Tags')

#### Returns
[Entity](Entity.md 'Friflo.Engine.ECS.Entity')