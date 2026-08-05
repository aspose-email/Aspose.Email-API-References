---
title: "Aspose::Email::MhtSaveOptions class"
linktitle: "MhtSaveOptions"
articleTitle: "MhtSaveOptions"
second_title: "Aspose.Email for C++"
description: "Allows to specify additional options when saving MailMessage to Mhtml format."
type: docs
weight: 10
url: /cpp/aspose.email/mhtsaveoptions/
---

## MhtSaveOptions class

**Inherits:** Aspose::Email::HeadersFormattingOptions

Allows to specify additional options when saving MailMessage to Mhtml format.

The following example shows how to save MailMessage as MHTML.

```csharp
var eml = MailMessage.Load("Message.eml");
eml.Save("target.mthml", SaveOptions.DefaultMhtml);
```

```vb
Dim eml = MailMessage.Load("Message.eml")
eml.Save("target.mthml", SaveOptions.DefaultMhtml)
```

## Constructors

| Name | Description |
| --- | --- |
| [MhtSaveOptions](./mhtsaveoptions/) | Initializes a new instance of this class that can be used to save a MailMessage in the Mhtml format. |

## Methods

| Name | Description |
| --- | --- |
| [get_CheckBodyContentEncoding](./get_checkbodycontentencoding/) | Defines whether need check message body content encoding when saving. By default the value is false. |
| [get_MhtFormatOptions](./get_mhtformatoptions/) | Defines additional options when saving in MHTML format. Default value is MhtFormatOptions.WriteHeader | MhtFormatOptions.WriteOutlineAttachments. |
| [get_PreserveOriginalBoundaries](./get_preserveoriginalboundaries/) | Defines whether need keep original boundaries in mail message when saving or not. |
| [get_PreserveOriginalDate](./get_preserveoriginaldate/) | Defines whether need keep original date in mail message when saving or not. Default value is true. |
| [get_SaveAllHeaders](./get_saveallheaders/) | Defines whether need to save all headers in output mhtml or not. Default value is false. |
| [get_SaveAttachments](./get_saveattachments/) | Gets a value indicating whether to save attachments. |
| [get_SavedHeaders](./get_savedheaders/) | Gets list of headers which will be present in saved mhtml content. Default value is empty list. |
| [get_SkipInlineImages](./get_skipinlineimages/) | Defines whether skip references on images at saving in mhtml or not. Default value is false. |
| [set_CheckBodyContentEncoding](./set_checkbodycontentencoding/) | Defines whether need check message body content encoding when saving. By default the value is false. |
| [set_MhtFormatOptions](./set_mhtformatoptions/) | Defines additional options when saving in MHTML format. Default value is MhtFormatOptions.WriteHeader | MhtFormatOptions.WriteOutlineAttachments. |
| [set_PreserveOriginalBoundaries](./set_preserveoriginalboundaries/) | Defines whether need keep original boundaries in mail message when saving or not. |
| [set_PreserveOriginalDate](./set_preserveoriginaldate/) | Defines whether need keep original date in mail message when saving or not. Default value is true. |
| [set_SaveAllHeaders](./set_saveallheaders/) | Defines whether need to save all headers in output mhtml or not. Default value is false. |
| [set_SaveAttachments](./set_saveattachments/) | Sets a value indicating whether to save attachments. |
| [set_SkipInlineImages](./set_skipinlineimages/) | Defines whether skip references on images at saving in mhtml or not. Default value is false. |

