---
title: PersonalStorage.SaveMessageToStream
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Saves a message to a stream in Outlook MSG format without loading it into a MapiMessage
type: docs
weight: 370
url: /net/aspose.email.storage.pst/personalstorage/savemessagetostream/
---
## PersonalStorage.SaveMessageToStream method

Saves a message to a stream in Outlook MSG format, without loading it into a `MapiMessage`.

```csharp
public void SaveMessageToStream(string entryId, Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryId | String | The entry ID of the message. |
| stream | Stream | The stream to write to. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *entryId* is `null` or empty. |
| ArgumentNullException | *stream* is `null`. |

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


