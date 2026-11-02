---
title: PersonalStorage.ExtractRecipients
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Reads the recipients of a message without loading the whole message
type: docs
weight: 230
url: /net/aspose.email.storage.pst/personalstorage/extractrecipients/
---
## ExtractRecipients(MessageInfo) {#extractrecipients}

Reads the recipients of a message without loading the whole message.

```csharp
public MapiRecipientCollection ExtractRecipients(MessageInfo messageInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageInfo | MessageInfo | The message. |

### Return Value

The [`MapiRecipientCollection`](../../../aspose.email.mapi/mapirecipientcollection/) that represents the collection of recipients.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *messageInfo* is `null`. |
| InvalidOperationException | The entry ID of *messageInfo* is empty. |

### See Also

* class [MapiRecipientCollection](../../../aspose.email.mapi/mapirecipientcollection/)
* class [MessageInfo](../../messageinfo/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## ExtractRecipients(string) {#extractrecipients_1}

Reads the recipients of a message without loading the whole message.

```csharp
public MapiRecipientCollection ExtractRecipients(string entryId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryId | String | The entry ID of the message. |

### Return Value

The [`MapiRecipientCollection`](../../../aspose.email.mapi/mapirecipientcollection/) that represents the collection of recipients.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *entryId* is `null` or empty. |
| InvalidOperationException | *entryId* is not valid. |

### See Also

* class [MapiRecipientCollection](../../../aspose.email.mapi/mapirecipientcollection/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


