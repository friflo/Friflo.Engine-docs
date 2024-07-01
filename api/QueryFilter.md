#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS](Friflo.Engine.ECS.md 'Friflo.Engine.ECS')

## QueryFilter Class

Contains component and tags filters added to an [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery').<br/>
Multiple [ArchetypeQuery](ArchetypeQuery.md 'Friflo.Engine.ECS.ArchetypeQuery')'s can share a single [QueryFilter](QueryFilter.md 'Friflo.Engine.ECS.QueryFilter') instance.

```csharp
public class QueryFilter
```

Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; QueryFilter

| Constructors | |
| :--- | :--- |
| [QueryFilter()](QueryFilter.QueryFilter().md 'Friflo.Engine.ECS.QueryFilter.QueryFilter()') | Create a filter returning all [Enabled](Entity.Enabled.md 'Friflo.Engine.ECS.Entity.Enabled') entities. |

| Fields | |
| :--- | :--- |
| [Condition](QueryFilter.Condition.md 'Friflo.Engine.ECS.QueryFilter.Condition') | Return all filter conditions of [QueryFilter](QueryFilter.md 'Friflo.Engine.ECS.QueryFilter'). |

| Methods | |
| :--- | :--- |
| [AllComponents(ComponentTypes)](QueryFilter.AllComponents(ComponentTypes).md 'Friflo.Engine.ECS.QueryFilter.AllComponents(Friflo.Engine.ECS.ComponentTypes)') | Include entities containing all specified component [types](QueryFilter.AllComponents(ComponentTypes).md#Friflo.Engine.ECS.QueryFilter.AllComponents(Friflo.Engine.ECS.ComponentTypes).types 'Friflo.Engine.ECS.QueryFilter.AllComponents(Friflo.Engine.ECS.ComponentTypes).types'). |
| [AllTags(Tags)](QueryFilter.AllTags(Tags).md 'Friflo.Engine.ECS.QueryFilter.AllTags(Friflo.Engine.ECS.Tags)') | Include entities containing all specified [tags](QueryFilter.AllTags(Tags).md#Friflo.Engine.ECS.QueryFilter.AllTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.QueryFilter.AllTags(Friflo.Engine.ECS.Tags).tags'). |
| [AnyComponents(ComponentTypes)](QueryFilter.AnyComponents(ComponentTypes).md 'Friflo.Engine.ECS.QueryFilter.AnyComponents(Friflo.Engine.ECS.ComponentTypes)') | Include entities containing any of the specified component [types](QueryFilter.AnyComponents(ComponentTypes).md#Friflo.Engine.ECS.QueryFilter.AnyComponents(Friflo.Engine.ECS.ComponentTypes).types 'Friflo.Engine.ECS.QueryFilter.AnyComponents(Friflo.Engine.ECS.ComponentTypes).types'). |
| [AnyTags(Tags)](QueryFilter.AnyTags(Tags).md 'Friflo.Engine.ECS.QueryFilter.AnyTags(Friflo.Engine.ECS.Tags)') | Include entities containing any of the specified [tags](QueryFilter.AnyTags(Tags).md#Friflo.Engine.ECS.QueryFilter.AnyTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.QueryFilter.AnyTags(Friflo.Engine.ECS.Tags).tags'). |
| [FreezeFilter()](QueryFilter.FreezeFilter().md 'Friflo.Engine.ECS.QueryFilter.FreezeFilter()') | [QueryFilter](QueryFilter.md 'Friflo.Engine.ECS.QueryFilter') cannot be changed anymore. |
| [HasValue&lt;TComponent,TValue&gt;(TValue)](QueryFilter.HasValue_TComponent,TValue_(TValue).md 'Friflo.Engine.ECS.QueryFilter.HasValue<TComponent,TValue>(TValue)') | Include entities having a component with the specified value.<br/> Executes in O(1). |
| [ValueInRange&lt;TComponent,TValue&gt;(TValue, TValue)](QueryFilter.ValueInRange_TComponent,TValue_(TValue,TValue).md 'Friflo.Engine.ECS.QueryFilter.ValueInRange<TComponent,TValue>(TValue, TValue)') | Include entities having a component value in the specified range.<br/> Executes O(N ⋅ log N) N: all unique values. |
| [WithDisabled()](QueryFilter.WithDisabled().md 'Friflo.Engine.ECS.QueryFilter.WithDisabled()') | A query will return [Enabled](Entity.Enabled.md 'Friflo.Engine.ECS.Entity.Enabled') as well as disabled entities. |
| [WithoutAllComponents(ComponentTypes)](QueryFilter.WithoutAllComponents(ComponentTypes).md 'Friflo.Engine.ECS.QueryFilter.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes)') | Exclude entities containing all specified component [types](QueryFilter.WithoutAllComponents(ComponentTypes).md#Friflo.Engine.ECS.QueryFilter.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes).types 'Friflo.Engine.ECS.QueryFilter.WithoutAllComponents(Friflo.Engine.ECS.ComponentTypes).types'). |
| [WithoutAllTags(Tags)](QueryFilter.WithoutAllTags(Tags).md 'Friflo.Engine.ECS.QueryFilter.WithoutAllTags(Friflo.Engine.ECS.Tags)') | Exclude entities containing all specified [tags](QueryFilter.WithoutAllTags(Tags).md#Friflo.Engine.ECS.QueryFilter.WithoutAllTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.QueryFilter.WithoutAllTags(Friflo.Engine.ECS.Tags).tags'). |
| [WithoutAnyComponents(ComponentTypes)](QueryFilter.WithoutAnyComponents(ComponentTypes).md 'Friflo.Engine.ECS.QueryFilter.WithoutAnyComponents(Friflo.Engine.ECS.ComponentTypes)') | Exclude entities containing any of the specified  component [types](QueryFilter.WithoutAnyComponents(ComponentTypes).md#Friflo.Engine.ECS.QueryFilter.WithoutAnyComponents(Friflo.Engine.ECS.ComponentTypes).types 'Friflo.Engine.ECS.QueryFilter.WithoutAnyComponents(Friflo.Engine.ECS.ComponentTypes).types'). |
| [WithoutAnyTags(Tags)](QueryFilter.WithoutAnyTags(Tags).md 'Friflo.Engine.ECS.QueryFilter.WithoutAnyTags(Friflo.Engine.ECS.Tags)') | Exclude entities containing any of the specified [tags](QueryFilter.WithoutAnyTags(Tags).md#Friflo.Engine.ECS.QueryFilter.WithoutAnyTags(Friflo.Engine.ECS.Tags).tags 'Friflo.Engine.ECS.QueryFilter.WithoutAnyTags(Friflo.Engine.ECS.Tags).tags'). |
