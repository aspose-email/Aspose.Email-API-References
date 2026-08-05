---
title: "Aspose::Email::EmlSaveOptions class"
linktitle: "EmlSaveOptions"
articleTitle: "EmlSaveOptions"
second_title: "Aspose.Email for C++"
description: "Allows to specify additional options when saving MailMessage to Eml and Emlx format."
type: docs
weight: 10
url: /cpp/aspose.email/emlsaveoptions/
---

## EmlSaveOptions class

**Inherits:** Aspose::Email::SaveOptions

Allows to specify additional options when saving MailMessage to Eml and Emlx format.

The following example shows how to load and Save an EML message Preserving the embedded message format.

```csharp
MailMessage mailMessage = MailMessage.Load("source.eml");
// Save as eml with preserved embedded message format
EmlSaveOptions emlSaveOptions = new EmlSaveOptions(MailMessageSaveType.EmlFormat)
{
     PreserveEmbeddedMessageFormat = true
};
    mailMessage.Save("target.eml", emlSaveOptions);
```

```vb
Dim mailMessage As MailMessage = MailMessage.Load("source.eml")
 
' Save as eml with preserved embedded message format
Dim emlSaveOptions As EmlSaveOptions = New EmlSaveOptions(MailMessageSaveType.EmlFormat) With {
   .PreserveEmbeddedMessageFormat = True
   }
        }
mailMessage.Save("target.eml", emlSaveOptions)
```

## Constructors

| Name | Description |
| --- | --- |
| [EmlSaveOptions](./emlsaveoptions/) | Initializes a new instance of this class that can be used to save a MailMessage in the Eml and Emlx format. |

## Methods

| Name | Description |
| --- | --- |
| [get_BoundariesTemplate](./get_boundariestemplate/) | Gets the boundary template for the message. Default value is null. |
| [get_CheckBodyContentEncoding](./get_checkbodycontentencoding/) | Defines whether need check message body content encoding when saving. By default the value is false. |
| [get_FileCompatibilityMode](./get_filecompatibilitymode/) | Defines inner conversions,that are necessarily to be done when saving a message. The default value is FileCompatibilityMode.None. |
| [get_PreserveEmbeddedMessageFormat](./get_preserveembeddedmessageformat/) | Gets a value indicating whether it is necessary to preserve MSG format of embedded message at converting to MailMessage . By default the value is false. |
| [get_PreserveSignedContent](./get_preservesignedcontent/) | Gets a value indicating whether it is necessary to save signed message without changes of content to provide correctly structure of digital sign. By default the value is false. |
| [set_BoundariesTemplate](./set_boundariestemplate/) | Sets the boundary template for the message. Default value is null. |
| [set_CheckBodyContentEncoding](./set_checkbodycontentencoding/) | Defines whether need check message body content encoding when saving. By default the value is false. |
| [set_FileCompatibilityMode](./set_filecompatibilitymode/) | Defines inner conversions,that are necessarily to be done when saving a message. The default value is FileCompatibilityMode.None. |
| [set_PreserveEmbeddedMessageFormat](./set_preserveembeddedmessageformat/) | Sets a value indicating whether it is necessary to preserve MSG format of embedded message at converting to MailMessage . By default the value is false. |
| [set_PreserveSignedContent](./set_preservesignedcontent/) | Sets a value indicating whether it is necessary to save signed message without changes of content to provide correctly structure of digital sign. By default the value is false. |

