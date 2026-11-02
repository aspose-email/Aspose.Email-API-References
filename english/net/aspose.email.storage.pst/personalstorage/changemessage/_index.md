---
title: PersonalStorage.ChangeMessage
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Changes properties of a message
type: docs
weight: 140
url: /net/aspose.email.storage.pst/personalstorage/changemessage/
---
## PersonalStorage.ChangeMessage method

Changes properties of a message.

```csharp
public void ChangeMessage(string entryId, MapiPropertyCollection updatedProperties)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryId | String | The entry ID of the message. |
| updatedProperties | MapiPropertyCollection | The properties to set. |

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |
| InvalidOperationException | The PST is open for reading only. |
| ArgumentNullException | *entryId* is `null` or empty. |
| ArgumentNullException | *updatedProperties* is `null`. |
| InvalidOperationException | *entryId* is not valid. |

### See Also

* class [MapiPropertyCollection](../../../aspose.email.mapi/mapipropertycollection/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


