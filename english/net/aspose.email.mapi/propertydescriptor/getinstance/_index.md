---
title: PropertyDescriptor.GetInstance
second_title: Aspose.Email for .NET API Reference
description: PropertyDescriptor method. Gets the descriptor of a tagged property by its ID and data type
type: docs
weight: 80
url: /net/aspose.email.mapi/propertydescriptor/getinstance/
---
## GetInstance(int, PropertyDataType) {#getinstance_2}

Gets the descriptor of a tagged property by its ID and data type.

```csharp
public static PidTagPropertyDescriptor GetInstance(int id, PropertyDataType dataType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | Int32 | The 16-bit ID of the property. |
| dataType | PropertyDataType | The data type of the property. |

### Return Value

The descriptor: the one from [`KnownPropertyList`](../../knownpropertylist/) if the property is known; otherwise a new one.

### See Also

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor/)
* enum [PropertyDataType](../../propertydatatype/)
* class [PropertyDescriptor](../)
* namespace [Aspose.Email.Mapi](../../propertydescriptor/)
* assembly [Aspose.Email](../../../)

---

## GetInstance(long) {#getinstance_3}

Gets the descriptor of a tagged property by its tag.

```csharp
public static PidTagPropertyDescriptor GetInstance(long tag)
```

| Parameter | Type | Description |
| --- | --- | --- |
| tag | Int64 | The tag of the property. |

### Return Value

The descriptor: the one from [`KnownPropertyList`](../../knownpropertylist/) if the property is known; otherwise a new one.

### See Also

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor/)
* class [PropertyDescriptor](../)
* namespace [Aspose.Email.Mapi](../../propertydescriptor/)
* assembly [Aspose.Email](../../../)

---

## GetInstance(long, PropertyDataType, Guid) {#getinstance}

Gets the descriptor of a named property by its numeric ID (LID).

```csharp
public static PidLidPropertyDescriptor GetInstance(long lid, PropertyDataType dataType, 
    Guid propertySet)
```

| Parameter | Type | Description |
| --- | --- | --- |
| lid | Int64 | The numeric ID of the property. |
| dataType | PropertyDataType | The data type of the property. |
| propertySet | Guid | The GUID of the property set. |

### Return Value

The descriptor: the one from [`KnownPropertyList`](../../knownpropertylist/) if the property is known; otherwise a new one.

### See Also

* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor/)
* enum [PropertyDataType](../../propertydatatype/)
* class [PropertyDescriptor](../)
* namespace [Aspose.Email.Mapi](../../propertydescriptor/)
* assembly [Aspose.Email](../../../)

---

## GetInstance(string, PropertyDataType, Guid) {#getinstance_1}

Gets the descriptor of a named property by its name.

```csharp
public static PidNamePropertyDescriptor GetInstance(string name, PropertyDataType dataType, 
    Guid propertySet)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of the property. |
| dataType | PropertyDataType | The data type of the property. |
| propertySet | Guid | The GUID of the property set. |

### Return Value

The descriptor: the one from [`KnownPropertyList`](../../knownpropertylist/) if the property is known; otherwise a new one.

### See Also

* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor/)
* enum [PropertyDataType](../../propertydatatype/)
* class [PropertyDescriptor](../)
* namespace [Aspose.Email.Mapi](../../propertydescriptor/)
* assembly [Aspose.Email](../../../)

---

## GetInstance(MapiProperty) {#getinstance_4}

Gets the descriptor of a MAPI property.

```csharp
public static PropertyDescriptor GetInstance(MapiProperty property)
```

| Parameter | Type | Description |
| --- | --- | --- |
| property | MapiProperty | The property. |

### Return Value

The descriptor of *property*.

### See Also

* class [MapiProperty](../../mapiproperty/)
* class [PropertyDescriptor](../)
* namespace [Aspose.Email.Mapi](../../propertydescriptor/)
* assembly [Aspose.Email](../../../)


