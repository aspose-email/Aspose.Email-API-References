---
title: MapiMessage.AddCustomProperty
second_title: Aspose.Email for .NET API Reference
description: MapiMessage method. Adds the custom property
type: docs
weight: 340
url: /net/aspose.email.mapi/mapimessage/addcustomproperty/
---
## AddCustomProperty(MapiProperty, string) {#addcustomproperty}

Adds the custom property.

```csharp
public void AddCustomProperty(MapiProperty property, string stringNameId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| property | MapiProperty | The property[`MapiProperty`](../../mapiproperty/). |
| stringNameId | String | The name of propertyString. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If *property* is null. |
| ArgumentException | If property data is null. |
| NotSupportedException | If data type is not supported yet. |

### See Also

* class [MapiProperty](../../mapiproperty/)
* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)

---

## AddCustomProperty(MapiPropertyType, byte[], string) {#addcustomproperty_1}

Adds the custom property.

```csharp
public void AddCustomProperty(MapiPropertyType type, byte[] data, string stringNameId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | MapiPropertyType | Type of MapiProperty[`MapiPropertyType`](../../mapipropertytype/) |
| data | Byte[] | MapiProperty data.Byte |
| stringNameId | String | The name of propertyString. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | If property data is null. |
| NotSupportedException | If data type is not supported yet. |

### See Also

* enum [MapiPropertyType](../../mapipropertytype/)
* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)


