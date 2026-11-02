---
title: MapiAttachmentCollection.Insert
second_title: Aspose.Email for .NET API Reference
description: MapiAttachmentCollection method. Inserts an attachment at the specified position
type: docs
weight: 40
url: /net/aspose.email.mapi/mapiattachmentcollection/insert/
---
## Insert(int, MapiAttachment) {#insert}

Inserts an attachment at the specified position.

```csharp
public void Insert(int index, MapiAttachment item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | The zero-based position to insert at. |
| item | MapiAttachment | The attachment to insert. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *index* is less than zero or greater than the number of attachments. |

### See Also

* class [MapiAttachment](../../mapiattachment/)
* class [MapiAttachmentCollection](../)
* namespace [Aspose.Email.Mapi](../../mapiattachmentcollection/)
* assembly [Aspose.Email](../../../)

---

## Insert(int, string, MapiMessage) {#insert_2}

Inserts a message as an embedded attachment at the specified position.

```csharp
public void Insert(int index, string name, MapiMessage msg)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | The zero-based position to insert at. |
| name | String | The name of the attachment. |
| msg | MapiMessage | The message to attach. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *msg* is `null`. |

### See Also

* class [MapiMessage](../../mapimessage/)
* class [MapiAttachmentCollection](../)
* namespace [Aspose.Email.Mapi](../../mapiattachmentcollection/)
* assembly [Aspose.Email](../../../)


