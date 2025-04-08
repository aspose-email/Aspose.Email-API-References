---
title: Class EmlLoadOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.EmlLoadOptions class. Allows to specify additional options when loading MailMessage from Eml format
type: docs
weight: 17430
url: /net/aspose.email/emlloadoptions/
---
## EmlLoadOptions class

Allows to specify additional options when loading MailMessage from Eml format.

```csharp
public class EmlLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [EmlLoadOptions](emlloadoptions/)() | Initializes a new instance of this class that can be used to loading MailMessage from Eml format. |

## Properties

| Name | Description |
| --- | --- |
| [MessageFormat](../../aspose.email/loadoptions/messageformat/) { get; } | Represents the mail message format.It can be in eml,msg or mhtml format. The default value is Eml. |
| [PreferredTextEncoding](../../aspose.email/loadoptions/preferredtextencoding/) { get; set; } | Gets or sets preferred encoding for message. Forcibly sets the preferred encoding for message subject and body. The default value is null. |
| [PreserveEmbeddedMessageFormat](../../aspose.email/loadoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading. By default the value is false. |
| [PreserveTnefAttachments](../../aspose.email/emlloadoptions/preservetnefattachments/) { get; set; } | Controls TNEF attachment loading behaviour. By default the value is false. |
| [RemoveSignature](../../aspose.email/loadoptions/removesignature/) { get; set; } | Gets or sets a value indicating whether signature will be removed while loading. |

## Examples

The following example shows how to convert EML to MSG.

[C#]

```csharp
// Initialize EmlLoadOptions  
var emlLoadOptions = new EmlLoadOptions()
       {
               PreserveTnefAttachments = true,
               PreserveEmbeddedMessageFormat = true
       };

// Initialize MailMessage with EmlLoadOptions
using (MailMessage message = MailMessage.Load("TestEml.eml", emlLoadOptions))
{
	// Convert EML to MSG
	message.Save("output.msg", SaveOptions.DefaultMsg);
}
```

[Visual Basic]

```csharp
' Initialize EmlLoadOptions  
Dim emlLoadOptions = New EmlLoadOptions() With 
{
             .PreserveTnefAttachments = True,
             .PreserveEmbeddedMessageFormat = True
       }

' Initialize MailMessage with EmlLoadOptions
Using message As MailMessage = MailMessage.Load("TestEml.eml", emlLoadOptions)
	' Convert EML to MSG
	message.Save("output.msg", SaveOptions.DefaultMsg)
End Using
```

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


