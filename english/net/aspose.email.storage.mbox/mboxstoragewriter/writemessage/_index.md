---
title: MboxStorageWriter.WriteMessage
second_title: Aspose.Email for .NET API Reference
description: MboxStorageWriter method. Writes the message to underlying storage stream
type: docs
weight: 30
url: /net/aspose.email.storage.mbox/mboxstoragewriter/writemessage/
---
## WriteMessage(MailMessage) {#writemessage}

Writes the message to underlying storage stream.

```csharp
public abstract string WriteMessage(MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MailMessage | The message to write to. |

### Return Value

The string identifier of added message.

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [MboxStorageWriter](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxstoragewriter/)
* assembly [Aspose.Email](../../../)

---

## WriteMessage(MailMessage, out string) {#writemessage_1}

Writes the message to underlying storage stream.

```csharp
public abstract string WriteMessage(MailMessage message, out string fromMarker)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MailMessage | The message to write to. |
| fromMarker | String& | Gets the From Marker while writing the MBox Storage file. |

### Return Value

The string identifier of added message.

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [MboxStorageWriter](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxstoragewriter/)
* assembly [Aspose.Email](../../../)


