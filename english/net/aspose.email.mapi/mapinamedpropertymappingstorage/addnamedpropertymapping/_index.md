---
title: MapiNamedPropertyMappingStorage.AddNamedPropertyMapping
second_title: Aspose.Email for .NET API Reference
description: MapiNamedPropertyMappingStorage method. Registers a property as a named property with a numeric ID
type: docs
weight: 40
url: /net/aspose.email.mapi/mapinamedpropertymappingstorage/addnamedpropertymapping/
---
## AddNamedPropertyMapping(MapiProperty, long, Guid) {#addnamedpropertymapping}

Registers a property as a named property with a numeric ID.

```csharp
public void AddNamedPropertyMapping(MapiProperty property, long nameId, Guid guid)
```

| Parameter | Type | Description |
| --- | --- | --- |
| property | MapiProperty | The property; its tag must be in the named property range. |
| nameId | Int64 | The numeric ID (LID) of the named property. |
| guid | Guid | The GUID of the property set. |

## Remarks

*property* should have a valid id for named property, [`GetNextAvailablePropertyId`](../getnextavailablepropertyid/) can be used to generate one. Otherwise an exception will be thrown.

### See Also

* class [MapiProperty](../../mapiproperty/)
* class [MapiNamedPropertyMappingStorage](../)
* namespace [Aspose.Email.Mapi](../../mapinamedpropertymappingstorage/)
* assembly [Aspose.Email](../../../)

---

## AddNamedPropertyMapping(MapiProperty, string, Guid) {#addnamedpropertymapping_1}

Registers a property as a named property with a string name.

```csharp
public void AddNamedPropertyMapping(MapiProperty property, string nameId, Guid guid)
```

| Parameter | Type | Description |
| --- | --- | --- |
| property | MapiProperty | The property; its tag must be in the named property range. |
| nameId | String | The name of the named property. |
| guid | Guid | The GUID of the property set. |

## Remarks

*property* should have a valid id for named property, [`GetNextAvailablePropertyId`](../getnextavailablepropertyid/) can be used to generate one. Otherwise an exception will be thrown.

### See Also

* class [MapiProperty](../../mapiproperty/)
* class [MapiNamedPropertyMappingStorage](../)
* namespace [Aspose.Email.Mapi](../../mapinamedpropertymappingstorage/)
* assembly [Aspose.Email](../../../)


