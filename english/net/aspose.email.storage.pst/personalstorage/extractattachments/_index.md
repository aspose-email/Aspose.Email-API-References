---
title: PersonalStorage.ExtractAttachments
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Reads the attachments of a message without loading the whole message
type: docs
weight: 200
url: /net/aspose.email.storage.pst/personalstorage/extractattachments/
---
## ExtractAttachments(MessageInfo) {#extractattachments}

Reads the attachments of a message without loading the whole message.

```csharp
public MapiAttachmentCollection ExtractAttachments(MessageInfo messageInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfo | MessageInfo | The message. |

### Return Value

The [`MapiAttachmentCollection`](../../../aspose.email.mapi/mapiattachmentcollection/) that represents the collection of attachments.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *messageInfo* is `null`. |
| InvalidOperationException | The entry ID of *messageInfo* is empty. |

### See Also

* class [MapiAttachmentCollection](../../../aspose.email.mapi/mapiattachmentcollection/)
* class [MessageInfo](../../messageinfo/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## ExtractAttachments(string) {#extractattachments_1}

Reads the attachments of a message without loading the whole message.

```csharp
public MapiAttachmentCollection ExtractAttachments(string entryId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryId | String | The entry ID of the message. |

### Return Value

The [`MapiAttachmentCollection`](../../../aspose.email.mapi/mapiattachmentcollection/) that represents the collection of attachments.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *entryId* is `null` or empty. |
| InvalidOperationException | *entryId* is not valid. |

### See Also

* class [MapiAttachmentCollection](../../../aspose.email.mapi/mapiattachmentcollection/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


