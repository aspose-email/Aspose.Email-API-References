---
title: Class EmlSaveOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.EmlSaveOptions class. Allows to specify additional options when saving MailMessage to Eml and Emlx format
type: docs
weight: 17330
url: /net/aspose.email/emlsaveoptions/
---
## EmlSaveOptions class

Allows to specify additional options when saving MailMessage to Eml and Emlx format.

```csharp
public class EmlSaveOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [EmlSaveOptions](emlsaveoptions/)(MailMessageSaveType) | Initializes a new instance of this class that can be used to save a MailMessage in the Eml and Emlx format. |

## Properties

| Name | Description |
| --- | --- |
| [CheckBodyContentEncoding](../../aspose.email/emlsaveoptions/checkbodycontentencoding/) { get; set; } | Defines whether need check message body content encoding when saving. By default the value is false. |
| [CustomProgressHandler](../../aspose.email/saveoptions/customprogresshandler/) { get; set; } | Represents method that usually supplied by calling side and handles progress events. |
| [FileCompatibilityMode](../../aspose.email/emlsaveoptions/filecompatibilitymode/) { get; set; } | Defines inner conversions,that are necessarily to be done when saving a message. The default value is FileCompatibilityMode.None. |
| [MailMessageSaveType](../../aspose.email/saveoptions/mailmessagesavetype/) { get; set; } | Represents the mail message save type.It can be in eml,msg(ASCII or Unicode),mhtml or html format. The default value is Eml. |
| [PreserveEmbeddedMessageFormat](../../aspose.email/emlsaveoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether it is necessary to preserve MSG format of embedded message at converting to MailMessage. By default the value is false. |
| [PreserveSignedContent](../../aspose.email/emlsaveoptions/preservesignedcontent/) { get; set; } | Gets or sets a value indicating whether it is necessary to save signed message without changes of content to provide correctly structure of digital sign. By default the value is false. |

## Examples

The following example shows how to load and Save an EML message Preserving the embedded message format.

[C#]

```csharp
MailMessage mailMessage = MailMessage.Load("source.eml");
// Save as eml with preserved embedded message format
EmlSaveOptions emlSaveOptions = new EmlSaveOptions(MailMessageSaveType.EmlFormat)
{
     PreserveEmbeddedMessageFormat = true
};
mailMessage.Save("target.eml", emlSaveOptions);
```

[Visual Basic]

```csharp
Dim mailMessage As MailMessage = MailMessage.Load("source.eml")

' Save as eml with preserved embedded message format
Dim emlSaveOptions As EmlSaveOptions = New EmlSaveOptions(MailMessageSaveType.EmlFormat) With {
       .PreserveEmbeddedMessageFormat = True
       }
		}
mailMessage.Save("target.eml", emlSaveOptions)
```

### See Also

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


