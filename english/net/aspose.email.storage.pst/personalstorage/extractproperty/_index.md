---
title: PersonalStorage.ExtractProperty
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Reads one property of an item without loading the whole item
type: docs
weight: 220
url: /net/aspose.email.storage.pst/personalstorage/extractproperty/
---
## PersonalStorage.ExtractProperty method

Reads one property of an item without loading the whole item.

```csharp
public MapiProperty ExtractProperty(byte[] entryId, long tag)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryId | Byte[] | The entry ID of the item. |
| tag | Int64 | The tag of the property. |

### Return Value

The property, or `null` if the item does not have it.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *entryId* is `null`. |

## Remarks

If a property is not found, null is returned.

### See Also

* class [MapiProperty](../../../aspose.email.mapi/mapiproperty/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


