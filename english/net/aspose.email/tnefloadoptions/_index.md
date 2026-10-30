---
title: Class TnefLoadOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.TnefLoadOptions class. Provides options for controlling how MailMessage instances are loaded from TNEF Transport Neutral Encapsulation Format format. This class is used primarily for handling Microsoft Outlook TNEF attachments winmail.dat that may contain rich text formatting and embedded objects
type: docs
weight: 19440
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
| [TnefLoadOptions](tnefloadoptions/)() | Initializes a new instance of the `TnefLoadOptions` class with the default options. |

## Properties

| Name | Description |
| --- | --- |
| [MessageFormat](../../aspose.email/loadoptions/messageformat/) { get; } | Gets the format this options object loads, as determined by its class: EML, MSG, MHTML, HTML and so on. |
| [PreferredTextEncoding](../../aspose.email/loadoptions/preferredtextencoding/) { get; set; } | Gets or sets the encoding used for the subject and the body regardless of what the message declares. The default is `null`: the declared encoding is used. |
| [PreserveEmbeddedMessageFormat](../../aspose.email/loadoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether embedded messages keep their original format (EML or MSG) when loaded. The default is `false`. |
| [RemoveSignature](../../aspose.email/loadoptions/removesignature/) { get; set; } | Gets or sets a value indicating whether the digital signature is removed from a signed message while it is loaded. |

## Remarks

Use this class with [`Load`](../mailmessage/load/) to load TNEF data. TNEF is a proprietary Microsoft format used by Outlook to encapsulate rich text messages and attachments. The TNEF format is typically encountered in winmail.dat attachments when emails are sent from Outlook to non-Outlook clients.

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


