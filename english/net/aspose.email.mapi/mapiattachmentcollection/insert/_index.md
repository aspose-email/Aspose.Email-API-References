---
title: MapiAttachmentCollection.Insert
second_title: Aspose.Email for .NET API Reference
description: MapiAttachmentCollection method. Inserts an element into the Collection at the specified index
type: docs
weight: 30
url: /net/aspose.email.mapi/mapiattachmentcollection/insert/
---
## Insert(int, MapiAttachment) {#insert}

Inserts an element into the Collection at the specified index.

```csharp
public void Insert(int index, MapiAttachment item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | The zero-based index at which *item* should be inserted. |
| item | MapiAttachment | The object to insert. The value can be null for reference types. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *index* is less than zero. |

### See Also

* class [MapiAttachment](../../mapiattachment/)
* class [MapiAttachmentCollection](../)
* namespace [Aspose.Email.Mapi](../../mapiattachmentcollection/)
* assembly [Aspose.Email](../../../)

---

## Insert(int, string, MapiMessage) {#insert_2}

Inserts a message as attachment into the [`MapiAttachmentCollection`](../) at the specified index.

```csharp
public void Insert(int index, string name, MapiMessage msg)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | The zero-based index at which should be inserted. |
| name | String | The name of attachment. |
| msg | MapiMessage | The [`MapiMessage`](../../mapimessage/) that represents the attached message. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | throws if message is null. |

### See Also

* class [MapiMessage](../../mapimessage/)
* class [MapiAttachmentCollection](../)
* namespace [Aspose.Email.Mapi](../../mapiattachmentcollection/)
* assembly [Aspose.Email](../../../)


