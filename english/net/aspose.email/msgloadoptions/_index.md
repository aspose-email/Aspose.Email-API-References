---
title: Class MsgLoadOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.MsgLoadOptions class. Allows to specify additional options when loading MailMessage from Msg format
type: docs
weight: 19290
url: /net/aspose.email/msgloadoptions/
---
## MsgLoadOptions class

Allows to specify additional options when loading MailMessage from Msg format.

```csharp
public class MsgLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MsgLoadOptions](msgloadoptions/)() | Initializes a new instance of this class that can be used to loading MailMessage from Msg format. |

## Properties

| Name | Description |
| --- | --- |
| [DecodeSignedContent](../../aspose.email/msgloadoptions/decodesignedcontent/) { get; set; } | Gets or sets a value indicating whether signed message will be decoded. |
| [KeepOriginalEmailAddresses](../../aspose.email/msgloadoptions/keeporiginalemailaddresses/) { get; set; } | Gets or sets a value indicating whether need keep original email address. |
| [MessageFormat](../../aspose.email/loadoptions/messageformat/) { get; } | Represents the mail message format.It can be in eml,msg or mhtml format. The default value is Eml. |
| [PreferredTextEncoding](../../aspose.email/loadoptions/preferredtextencoding/) { get; set; } | Gets or sets preferred encoding for message. Forcibly sets the preferred encoding for message subject and body. The default value is null. |
| [PreserveEmbeddedMessageFormat](../../aspose.email/loadoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading. By default the value is false. |
| [PreserveRtfContent](../../aspose.email/msgloadoptions/preservertfcontent/) { get; set; } | Gets or sets a value indicating whether need keep rtf body in MailMessage. |
| [PreserveTnefAttachments](../../aspose.email/msgloadoptions/preservetnefattachments/) { get; set; } | Controls loading TNEF attachment behaviour. By default the value is false. |
| [Timeout](../../aspose.email/msgloadoptions/timeout/) { get; set; } | Limits the time in milliseconds of formatting message while converting. Default value 3 sec. |

## Events

| Name | Description |
| --- | --- |
| event [TimeoutReached](../../aspose.email/msgloadoptions/timeoutreached/) | Raised if timed out while converting to MailMessage. |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


