---
title: Enum HtmlFormatOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.HtmlFormatOptions enum. Defines options for saving a message to HTML. The values can be combined
type: docs
weight: 16280
url: /net/aspose.email/htmlformatoptions/
---
## HtmlFormatOptions enumeration

Defines options for saving a message to HTML. The values can be combined.

```csharp
[Flags]
public enum HtmlFormatOptions
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | No options. |
| WriteHeader | `1` | Write the headers of the message above the body. |
| WriteCompleteEmailAddress | `2` | Write the full e-mail addresses, not only the display names, in all headers. |
| WriteCompleteToEmailAddress | `4` | Write the full e-mail address, not only the display name, in the `To` header. |
| WriteCompleteFromEmailAddress | `8` | Write the full e-mail address, not only the display name, in the `From` header. |
| WriteCompleteCcEmailAddress | `10` | Write the full e-mail address, not only the display name, in the `Cc` header. |
| WriteCompleteBccEmailAddress | `20` | Write the full e-mail address, not only the display name, in the `Bcc` header. |
| DisplayAsOutlook | `40` | Write the `From` header the way Outlook shows it. |
| RenderCalendarEvent | `80` | Write the details of a calendar event the message carries. |
| RenderVCardInfo | `100` | Write the details of a vCard the message carries. |
| RenderTaskFields | `200` | Write the fields of a task. |
| PrintFormat | `400` | Format the output for printing. |

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


