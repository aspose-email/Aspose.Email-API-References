---
title: MapiMessage.AddCustomProperty
second_title: Aspose.Email for .NET API Reference
description: MapiMessage method. Adds a custom named property with a string name
type: docs
weight: 330
url: /net/aspose.email.mapi/mapimessage/addcustomproperty/
---
## AddCustomProperty(MapiProperty, string) {#addcustomproperty}

Adds a custom named property with a string name.

```csharp
public void AddCustomProperty(MapiProperty property, string stringNameId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| property | MapiProperty | The property, with its type and value. |
| stringNameId | String | The name of the property. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *property* is `null`. |
| ArgumentException | The data of the property is `null`. |
| NotSupportedException | The data type of the property is not supported. |

### See Also

* class [MapiProperty](../../mapiproperty/)
* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)

---

## AddCustomProperty(MapiPropertyType, byte[], string) {#addcustomproperty_1}

Adds a custom named property with a string name.

```csharp
public void AddCustomProperty(MapiPropertyType type, byte[] data, string stringNameId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | MapiPropertyType | The data type of the property. |
| data | Byte[] | The value of the property, as bytes. |
| stringNameId | String | The name of the property. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *data* is `null`. |
| NotSupportedException | *type* is not supported. |

### See Also

* enum [MapiPropertyType](../../mapipropertytype/)
* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)


