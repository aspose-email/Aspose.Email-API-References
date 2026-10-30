---
title: Enum MhtFormatOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.MhtFormatOptions enum. Defines options for saving a message to MHTML. The values can be combined
type: docs
weight: 17950
url: /net/aspose.email/mhtformatoptions/
---
## MhtFormatOptions enumeration

Defines options for saving a message to MHTML. The values can be combined.

```csharp
[Flags]
public enum MhtFormatOptions
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | No options. |
| WriteHeader | `1` | Write the headers of the message above the body. |
| WriteOutlineAttachments | `2` | Write the list of attachments in the headers. |
| WriteCompleteEmailAddress | `4` | Write the full e-mail addresses, not only the display names, in all headers. |
| NoEncodeCharacters | `8` | Do not apply a transfer encoding to the characters of the body. |
| HideExtraPrintHeader | `10` | Hide the page header. |
| WriteCompleteToEmailAddress | `20` | Write the full e-mail address, not only the display name, in the `To` header. |
| WriteCompleteFromEmailAddress | `40` | Write the full e-mail address, not only the display name, in the `From` header. |
| WriteCompleteCcEmailAddress | `80` | Write the full e-mail address, not only the display name, in the `Cc` header. |
| WriteCompleteBccEmailAddress | `100` | Write the full e-mail address, not only the display name, in the `Bcc` header. |
| RenderCalendarEvent | `200` | Write the details of a calendar event the message carries. |
| SkipByteOrderMarkInBody | `400` | Do not write a byte order mark (BOM) at the start of the body. |
| RenderVCardInfo | `800` | Write the details of a vCard the message carries. |
| DisplayAsOutlook | `1000` | Write the `From` header the way Outlook shows it. |
| RenderTaskFields | `2000` | Write the fields of a task. |

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


