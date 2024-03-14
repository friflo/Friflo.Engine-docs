#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Serialize](Friflo.Engine.ECS.Serialize.md 'Friflo.Engine.ECS.Serialize').[EntitySerializer](EntitySerializer.md 'Friflo.Engine.ECS.Serialize.EntitySerializer')

## EntitySerializer.ReadEntities(List<DataEntity>, Stream) Method

Reads the JSON array of the given [stream](EntitySerializer.ReadEntities(List_DataEntity_,Stream).md#Friflo.Engine.ECS.Serialize.EntitySerializer.ReadEntities(System.Collections.Generic.List_Friflo.Engine.ECS.Serialize.DataEntity_,System.IO.Stream).stream 'Friflo.Engine.ECS.Serialize.EntitySerializer.ReadEntities(System.Collections.Generic.List<Friflo.Engine.ECS.Serialize.DataEntity>, System.IO.Stream).stream') into the passed [entities](EntitySerializer.ReadEntities(List_DataEntity_,Stream).md#Friflo.Engine.ECS.Serialize.EntitySerializer.ReadEntities(System.Collections.Generic.List_Friflo.Engine.ECS.Serialize.DataEntity_,System.IO.Stream).entities 'Friflo.Engine.ECS.Serialize.EntitySerializer.ReadEntities(System.Collections.Generic.List<Friflo.Engine.ECS.Serialize.DataEntity>, System.IO.Stream).entities') list.

```csharp
public Friflo.Engine.ECS.Serialize.ReadResult ReadEntities(System.Collections.Generic.List<Friflo.Engine.ECS.Serialize.DataEntity> entities, System.IO.Stream stream);
```
#### Parameters

<a name='Friflo.Engine.ECS.Serialize.EntitySerializer.ReadEntities(System.Collections.Generic.List_Friflo.Engine.ECS.Serialize.DataEntity_,System.IO.Stream).entities'></a>

`entities` [System.Collections.Generic.List&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.List-1 'System.Collections.Generic.List`1')[DataEntity](DataEntity.md 'Friflo.Engine.ECS.Serialize.DataEntity')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.List-1 'System.Collections.Generic.List`1')

<a name='Friflo.Engine.ECS.Serialize.EntitySerializer.ReadEntities(System.Collections.Generic.List_Friflo.Engine.ECS.Serialize.DataEntity_,System.IO.Stream).stream'></a>

`stream` [System.IO.Stream](https://docs.microsoft.com/en-us/dotnet/api/System.IO.Stream 'System.IO.Stream')

#### Returns
[ReadResult](ReadResult.md 'Friflo.Engine.ECS.Serialize.ReadResult')