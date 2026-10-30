---
title: Class MessageStore
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Storage.Pst.MessageStore class. The message store of a PST its toplevel object which holds the display name password and other settings of the file
type: docs
weight: 19240
url: /net/aspose.email.storage.pst/messagestore/
---
## MessageStore class

The message store of a PST: its top-level object, which holds the display name, password and other settings of the file.

```csharp
public class MessageStore
```

## Properties

| Name | Description |
| --- | --- |
| [DisplayName](../../aspose.email.storage.pst/messagestore/displayname/) { get; } | Gets the display name of the PST, which Outlook shows as the name of the data file. |
| [IsPasswordProtected](../../aspose.email.storage.pst/messagestore/ispasswordprotected/) { get; } | Gets a value indicating whether the storage is password protected. |
| [Properties](../../aspose.email.storage.pst/messagestore/properties/) { get; } | Gets the MAPI properties of message store object. The message store contains the top-level PST settings and metadata that are required to access and manage the PST contents. |

## Methods

| Name | Description |
| --- | --- |
| [ChangeDisplayName](../../aspose.email.storage.pst/messagestore/changedisplayname/)(string) | Changes the display name of the PST. |
| [ChangePassword](../../aspose.email.storage.pst/messagestore/changepassword/)(string) | Sets or changes the password of the PST. |
| [GetTotalItemsCount](../../aspose.email.storage.pst/messagestore/gettotalitemscount/)() | Gets the total number of message items in the PST. |
| [IsPasswordValid](../../aspose.email.storage.pst/messagestore/ispasswordvalid/)(string) | Checks whether the specified password is the password of the PST. |
| [SetProperty](../../aspose.email.storage.pst/messagestore/setproperty/)(MapiProperty) | Sets a property of the message store. |

### See Also

* namespace [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst/)
* assembly [Aspose.Email](../../)


