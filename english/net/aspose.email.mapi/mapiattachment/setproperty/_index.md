---
title: MapiAttachment.SetProperty
second_title: Aspose.Email for .NET API Reference
description: MapiAttachment method. Adds the property to the attachment or replaces the property with the same tag
type: docs
weight: 240
url: /net/aspose.email.mapi/mapiattachment/setproperty/
---
## SetProperty(MapiProperty) {#setproperty}

Adds the property to the attachment, or replaces the property with the same tag.

```csharp
public override void SetProperty(MapiProperty value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| value | MapiProperty | The property to set. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *value* is `null`. |
| ArgumentException | The data of the property is `null`. |
| InvalidOperationException | The data type of the property is not supported. |

### See Also

* class [MapiProperty](../../mapiproperty/)
* class [MapiAttachment](../)
* namespace [Aspose.Email.Mapi](../../mapiattachment/)
* assembly [Aspose.Email](../../../)

---

## SetProperty(PropertyDescriptor, object) {#setproperty_1}

Sets the value of a MAPI property of the attachment.

```csharp
public override void SetProperty(PropertyDescriptor pd, object value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pd | PropertyDescriptor | The descriptor of the property, for example one from [`KnownPropertyList`](../../knownpropertylist/). |
| value | Object | The value, of a .NET type that matches the data type of the property. |

### See Also

* class [PropertyDescriptor](../../propertydescriptor/)
* class [MapiAttachment](../)
* namespace [Aspose.Email.Mapi](../../mapiattachment/)
* assembly [Aspose.Email](../../../)


