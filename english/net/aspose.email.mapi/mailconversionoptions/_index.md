---
title: Class MailConversionOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MailConversionOptions class. Specify additional options when converting from MapiMessage to MailMessage
type: docs
weight: 18040
url: /net/aspose.email.mapi/mailconversionoptions/
---
## MailConversionOptions class

Specify additional options when converting from MapiMessage to MailMessage.

```csharp
public class MailConversionOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MailConversionOptions](mailconversionoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ConvertAsTnef](../../aspose.email.mapi/mailconversionoptions/convertastnef/) { get; set; } | Set to true to import the MapiMessage information into a MailMessage object with MapiMessage as TNEF attachment. |
| [KeepOriginalEmailAddresses](../../aspose.email.mapi/mailconversionoptions/keeporiginalemailaddresses/) { get; set; } | Gets or sets a value indicating whether need keep original email address. |
| [PreserveEmbeddedMessageFormat](../../aspose.email.mapi/mailconversionoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether it is necessary to preserve MSG format of embedded message at converting to MailMessage. By default the value is false. |
| [PreserveRtfContent](../../aspose.email.mapi/mailconversionoptions/preservertfcontent/) { get; set; } | Gets or sets a value indicating whether need keep rtf body in MailMessage. |
| [Timeout](../../aspose.email.mapi/mailconversionoptions/timeout/) { get; set; } | Limits the time in milliseconds of formatting message while converting. Default value 3 sec. |

## Events

| Name | Description |
| --- | --- |
| event [TimeoutReached](../../aspose.email.mapi/mailconversionoptions/timeoutreached/) | Raised if timed out while converting to MailMessage. |

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


