---
title: MapiPropertyContainer.SetProperty
second_title: Aspose.Email for .NET API Reference
description: MapiPropertyContainer method. Sets the value of a MAPI property creating the property if needed
type: docs
weight: 120
url: /net/aspose.email.mapi/mapipropertycontainer/setproperty/
---
## SetProperty(PropertyDescriptor, object) {#setproperty_1}

Sets the value of a MAPI property, creating the property if needed.

```csharp
public virtual void SetProperty(PropertyDescriptor pd, object value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pd | PropertyDescriptor | The descriptor of the property, for example one from [`KnownPropertyList`](../../knownpropertylist/). |
| value | Object | The value, of a .NET type that matches the data type of the property. |

### See Also

* class [PropertyDescriptor](../../propertydescriptor/)
* class [MapiPropertyContainer](../)
* namespace [Aspose.Email.Mapi](../../mapipropertycontainer/)
* assembly [Aspose.Email](../../../)

---

## SetProperty(MapiProperty) {#setproperty}

Adds the property, or replaces the property with the same tag.

```csharp
public virtual void SetProperty(MapiProperty value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| value | MapiProperty | The property to set. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If *value* is null. |
| ArgumentException | If property data is null. |
| InvalidOperationException | If data type is not supported. |

### See Also

* class [MapiProperty](../../mapiproperty/)
* class [MapiPropertyContainer](../)
* namespace [Aspose.Email.Mapi](../../mapipropertycontainer/)
* assembly [Aspose.Email](../../../)


