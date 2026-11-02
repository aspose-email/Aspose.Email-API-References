---
title: MapiPropertyCollection.Remove
second_title: Aspose.Email for .NET API Reference
description: MapiPropertyCollection method. Removes the property with the specified tag
type: docs
weight: 140
url: /net/aspose.email.mapi/mapipropertycollection/remove/
---
## Remove(long) {#remove_1}

Removes the property with the specified tag.

```csharp
public bool Remove(long key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | Int64 | The tag of the property to remove. |

### Return Value

`true` if the property was removed; `false` if the collection does not contain it.

### See Also

* class [MapiPropertyCollection](../)
* namespace [Aspose.Email.Mapi](../../mapipropertycollection/)
* assembly [Aspose.Email](../../../)

---

## Remove(PropertyDescriptor) {#remove}

Removes the property with the specified descriptor.

```csharp
public bool Remove(PropertyDescriptor pd)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pd | PropertyDescriptor | The descriptor of the property to remove. |

### Return Value

`true` if the property was removed; `false` if the collection does not contain it.

### See Also

* class [PropertyDescriptor](../../propertydescriptor/)
* class [MapiPropertyCollection](../)
* namespace [Aspose.Email.Mapi](../../mapipropertycollection/)
* assembly [Aspose.Email](../../../)

---

## Remove(KeyValuePair&lt;long, MapiProperty&gt;) {#remove_2}

Removes the tag and property pair.

```csharp
public bool Remove(KeyValuePair<long, MapiProperty> item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| item | KeyValuePair`2 | The pair to remove. |

### Return Value

`true` if the pair was removed; otherwise, `false`.

### See Also

* class [MapiProperty](../../mapiproperty/)
* class [MapiPropertyCollection](../)
* namespace [Aspose.Email.Mapi](../../mapipropertycollection/)
* assembly [Aspose.Email](../../../)


