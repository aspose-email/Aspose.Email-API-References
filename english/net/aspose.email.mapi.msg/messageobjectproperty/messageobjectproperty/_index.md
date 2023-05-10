---
title: MessageObjectProperty.MessageObjectProperty
second_title: Aspose.Email for .NET API Reference
description: MessageObjectProperty constructor. Initializes a new instance of the MessageObjectProperty class
type: docs
weight: 10
url: /net/aspose.email.mapi.msg/messageobjectproperty/messageobjectproperty/
---
## MessageObjectProperty(long, MapiPropertyFlags, object) {#constructor_1}

Initializes a new instance of the [`MessageObjectProperty`](../) class.

```csharp
public MessageObjectProperty(long propertyTag, MapiPropertyFlags flags, object value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| propertyTag | Int64 | The property tag. |
| flags | MapiPropertyFlags | The flags to be set on. |
| value | Object | The value of the property. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If *value* is null. |
| InvalidEnumArgumentException | If *propertyTag* contains invalid type definition." |

### See Also

* enum [MapiPropertyFlags](../../mapipropertyflags/)
* class [MessageObjectProperty](../)
* namespace [Aspose.Email.Mapi.Msg](../../messageobjectproperty/)
* assembly [Aspose.Email](../../../)

---

## MessageObjectProperty(int, MapiType, MapiPropertyFlags, object) {#constructor}

Initializes a new instance of the [`MessageObjectProperty`](../) class.

```csharp
public MessageObjectProperty(int id, MapiType type, MapiPropertyFlags flags, object value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | Int32 | The id. |
| type | MapiType | The type of the property. |
| flags | MapiPropertyFlags | The flags to be set on. |
| value | Object | The value of the property. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If *value* is null. |
| InvalidEnumArgumentException | If *type* is invalid." |

### See Also

* enum [MapiType](../../mapitype/)
* enum [MapiPropertyFlags](../../mapipropertyflags/)
* class [MessageObjectProperty](../)
* namespace [Aspose.Email.Mapi.Msg](../../messageobjectproperty/)
* assembly [Aspose.Email](../../../)


