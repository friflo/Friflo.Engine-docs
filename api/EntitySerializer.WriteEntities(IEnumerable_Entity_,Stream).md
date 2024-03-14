#### [Friflo.Engine.ECS](index.md 'index')
### [Friflo.Engine.ECS.Serialize](Friflo.Engine.ECS.Serialize.md 'Friflo.Engine.ECS.Serialize').[EntitySerializer](EntitySerializer.md 'Friflo.Engine.ECS.Serialize.EntitySerializer')

## EntitySerializer.WriteEntities(IEnumerable<Entity>, Stream) Method

Writes the given [entities](EntitySerializer.WriteEntities(IEnumerable_Entity_,Stream).md#Friflo.Engine.ECS.Serialize.EntitySerializer.WriteEntities(System.Collections.Generic.IEnumerable_Friflo.Engine.ECS.Entity_,System.IO.Stream).entities 'Friflo.Engine.ECS.Serialize.EntitySerializer.WriteEntities(System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.Entity>, System.IO.Stream).entities') as a JSON array to the passed [stream](EntitySerializer.WriteEntities(IEnumerable_Entity_,Stream).md#Friflo.Engine.ECS.Serialize.EntitySerializer.WriteEntities(System.Collections.Generic.IEnumerable_Friflo.Engine.ECS.Entity_,System.IO.Stream).stream 'Friflo.Engine.ECS.Serialize.EntitySerializer.WriteEntities(System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.Entity>, System.IO.Stream).stream').

```csharp
public void WriteEntities(System.Collections.Generic.IEnumerable<Friflo.Engine.ECS.Entity> entities, System.IO.Stream stream);
```
#### Parameters

<a name='Friflo.Engine.ECS.Serialize.EntitySerializer.WriteEntities(System.Collections.Generic.IEnumerable_Friflo.Engine.ECS.Entity_,System.IO.Stream).entities'></a>

`entities` [System.Collections.Generic.IEnumerable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1')[Entity](Entity.md 'Friflo.Engine.ECS.Entity')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1 'System.Collections.Generic.IEnumerable`1')

<a name='Friflo.Engine.ECS.Serialize.EntitySerializer.WriteEntities(System.Collections.Generic.IEnumerable_Friflo.Engine.ECS.Entity_,System.IO.Stream).stream'></a>

`stream` [System.IO.Stream](https://docs.microsoft.com/en-us/dotnet/api/System.IO.Stream 'System.IO.Stream')