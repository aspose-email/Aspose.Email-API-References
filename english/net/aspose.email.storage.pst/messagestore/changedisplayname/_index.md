---
title: MessageStore.ChangeDisplayName
second_title: Aspose.Email for .NET API Reference
description: MessageStore method. Changes the display name of the PST
type: docs
weight: 40
url: /net/aspose.email.storage.pst/messagestore/changedisplayname/
---
## MessageStore.ChangeDisplayName method

Changes the display name of the PST.

```csharp
public void ChangeDisplayName(string newName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newName | String | The new display name. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *newName* is `null` or empty. |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |
| InvalidOperationException | The message store has no display name property to change. |

### See Also

* class [MessageStore](../)
* namespace [Aspose.Email.Storage.Pst](../../messagestore/)
* assembly [Aspose.Email](../../../)


