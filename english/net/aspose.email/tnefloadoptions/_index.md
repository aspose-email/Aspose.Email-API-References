---
title: Class TnefLoadOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.TnefLoadOptions class. Provides options for controlling how MailMessage instances are loaded from TNEF Transport Neutral Encapsulation Format format. This class is used primarily for handling Microsoft Outlook TNEF attachments winmail.dat that may contain rich text formatting and embedded objects
type: docs
weight: 19430
url: /net/aspose.email/tnefloadoptions/
---
## TnefLoadOptions class

Provides options for controlling how [`MailMessage`](../mailmessage/) instances are loaded from TNEF (Transport Neutral Encapsulation Format) format. This class is used primarily for handling Microsoft Outlook TNEF attachments (winmail.dat) that may contain rich text formatting and embedded objects.

```csharp
public class TnefLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TnefLoadOptions](tnefloadoptions/)() | Initializes a new instance of this class that can be used to loading a MailMessage from Tnef format. |

## Properties

| Name | Description |
| --- | --- |
| [MessageFormat](../../aspose.email/loadoptions/messageformat/) { get; } | Represents the mail message format.It can be in eml,msg or mhtml format. The default value is Eml. |
| [PreferredTextEncoding](../../aspose.email/loadoptions/preferredtextencoding/) { get; set; } | Gets or sets preferred encoding for message. Forcibly sets the preferred encoding for message subject and body. The default value is null. |
| [PreserveEmbeddedMessageFormat](../../aspose.email/loadoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading. By default the value is false. |
| [RemoveSignature](../../aspose.email/loadoptions/removesignature/) { get; set; } | Gets or sets a value indicating whether signature will be removed while loading. |

## Remarks

Use this class with [`Load`](../mailmessage/load/) to load TNEF data. TNEF is a proprietary Microsoft format used by Outlook to encapsulate rich text messages and attachments. The TNEF format is typically encountered in winmail.dat attachments when emails are sent from Outlook to non-Outlook clients.

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


