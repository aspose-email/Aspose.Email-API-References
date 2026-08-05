---
title: "Aspose::Email::EmlLoadOptions class"
linktitle: "EmlLoadOptions"
articleTitle: "EmlLoadOptions"
second_title: "Aspose.Email for C++"
description: "Allows to specify additional options when loading MailMessage from Eml format."
type: docs
weight: 10
url: /cpp/aspose.email/emlloadoptions/
---

## EmlLoadOptions class

**Inherits:** Aspose::Email::LoadOptions

Allows to specify additional options when loading MailMessage from Eml format.

The following example shows how to convert EML to MSG.

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

```vb
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

## Constructors

| Name | Description |
| --- | --- |
| [EmlLoadOptions](./emlloadoptions/) | Initializes a new instance of this class that can be used to loading MailMessage from Eml format. |

## Methods

| Name | Description |
| --- | --- |
| [get_PreserveTnefAttachments](./get_preservetnefattachments/) | Controls TNEF attachment loading behaviour. By default the value is false. |
| [set_PreserveTnefAttachments](./set_preservetnefattachments/) | Controls TNEF attachment loading behaviour. By default the value is false. |

