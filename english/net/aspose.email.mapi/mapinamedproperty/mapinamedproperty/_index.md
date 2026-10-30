---
title: MapiNamedProperty.MapiNamedProperty
second_title: Aspose.Email for .NET API Reference
description: MapiNamedProperty constructor. Initializes a new instance of the MapiNamedProperty class
type: docs
weight: 10
url: /net/aspose.email.mapi/mapinamedproperty/mapinamedproperty/
---
## MapiNamedProperty() {#constructor}

Initializes a new instance of the [`MapiNamedProperty`](../) class.

```csharp
public MapiNamedProperty()
```

### See Also

* class [MapiNamedProperty](../)
* namespace [Aspose.Email.Mapi](../../mapinamedproperty/)
* assembly [Aspose.Email](../../../)

---

## MapiNamedProperty(long, string, Guid, byte[]) {#constructor_4}

Initializes a new instance of the [`MapiNamedProperty`](../) class for a property identified by a string name.

```csharp
public MapiNamedProperty(long propertyTag, string nameIdentifier, Guid propertyGuid, 
    byte[] propertyValue)
```

| Parameter | Type | Description |
| --- | --- | --- |
| propertyTag | Int64 | The tag the property is stored under: the property ID in the high-order 16 bits and the data type in the low-order 16 bits. |
| nameIdentifier | String | The name of the property. |
| propertyGuid | Guid | The GUID of the property set. |
| propertyValue | Byte[] | The value, as bytes. |

### See Also

* class [MapiNamedProperty](../)
* namespace [Aspose.Email.Mapi](../../mapinamedproperty/)
* assembly [Aspose.Email](../../../)

---

## MapiNamedProperty(long, long, Guid, byte[]) {#constructor_3}

Initializes a new instance of the [`MapiNamedProperty`](../) class for a property identified by a numeric ID.

```csharp
public MapiNamedProperty(long propertyTag, long nameIdentifier, Guid propertyGuid, 
    byte[] propertyValue)
```

| Parameter | Type | Description |
| --- | --- | --- |
| propertyTag | Int64 | The tag the property is stored under: the property ID in the high-order 16 bits and the data type in the low-order 16 bits. |
| nameIdentifier | Int64 | The numeric ID (LID) of the property. |
| propertyGuid | Guid | The GUID of the property set. |
| propertyValue | Byte[] | The value, as bytes. |

### See Also

* class [MapiNamedProperty](../)
* namespace [Aspose.Email.Mapi](../../mapinamedproperty/)
* assembly [Aspose.Email](../../../)

---

## MapiNamedProperty(INamedPropertyTagProvider, PidLidPropertyDescriptor, object) {#constructor_1}

Initializes a new instance of the [`MapiNamedProperty`](../) class from a descriptor of a property with a numeric ID.

```csharp
public MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidLidPropertyDescriptor pd, 
    object data)
```

| Parameter | Type | Description |
| --- | --- | --- |
| tagProvider | INamedPropertyTagProvider | The property collection that assigns the tag, such as the properties of the message. |
| pd | PidLidPropertyDescriptor | The descriptor of the property. |
| data | Object | The value. |

### See Also

* interface [INamedPropertyTagProvider](../../inamedpropertytagprovider/)
* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor/)
* class [MapiNamedProperty](../)
* namespace [Aspose.Email.Mapi](../../mapinamedproperty/)
* assembly [Aspose.Email](../../../)

---

## MapiNamedProperty(INamedPropertyTagProvider, PidNamePropertyDescriptor, object) {#constructor_2}

Initializes a new instance of the [`MapiNamedProperty`](../) class from a descriptor of a property with a string name.

```csharp
public MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidNamePropertyDescriptor pd, 
    object data)
```

| Parameter | Type | Description |
| --- | --- | --- |
| tagProvider | INamedPropertyTagProvider | The property collection that assigns the tag, such as the properties of the message. |
| pd | PidNamePropertyDescriptor | The descriptor of the property. |
| data | Object | The value. |

### See Also

* interface [INamedPropertyTagProvider](../../inamedpropertytagprovider/)
* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor/)
* class [MapiNamedProperty](../)
* namespace [Aspose.Email.Mapi](../../mapinamedproperty/)
* assembly [Aspose.Email](../../../)


