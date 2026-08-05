---
title: "Aspose::Email::MsgSaveOptions class"
linktitle: "MsgSaveOptions"
articleTitle: "MsgSaveOptions"
second_title: "Aspose.Email for C++"
description: "This class allows the user to specify additional settings when saving a MailMessage in the Msg(ASCII) and Msg(Unicode) format."
type: docs
weight: 10
url: /cpp/aspose.email/msgsaveoptions/
---

## MsgSaveOptions class

**Inherits:** Aspose::Email::SaveOptions

This class allows the user to specify additional settings when saving a MailMessage in the Msg(ASCII) and Msg(Unicode) format.

The following example shows how to save as MSG with preserved dates.

```csharp
// Initialize and Load an existing EML file by specifying the MessageFormat
var eml = MailMessage.Load("Message.eml");
 
// Save as msg with preserved dates
var msgSaveOptions = new MsgSaveOptions(MailMessageSaveType.OutlookMessageFormatUnicode)
{
    PreserveOriginalDates = true
};
 
eml.Save("outTest_out.msg", msgSaveOptions);
```

```vb
' Initialize and Load an existing EML file by specifying the MessageFormat
Dim eml = MailMessage.Load("Message.eml")
 
' Save as msg with preserved dates
    Dim msgSaveOptions = New MsgSaveOptions(MailMessageSaveType.OutlookMessageFormatUnicode) With {
        .PreserveOriginalDates = True
    }
 
eml.Save("outTest_out.msg", msgSaveOptions)
```

## Constructors

| Name | Description |
| --- | --- |
| [MsgSaveOptions](./msgsaveoptions/) | Initializes a new instance of this class that can be used to save a MailMessage in the Msg(ASCII) and Msg(Unicode) format. |

## Methods

| Name | Description |
| --- | --- |
| [get_PreserveOriginalDates](./get_preserveoriginaldates/) | Gets a value indicating whether it is necessary to generate new saving and modification dates when saving a message. By default the value is true, meaning the creation and modification dates will be not set to DateTime.Now. |
| [get_PreserveSignature](./get_preservesignature/) | Set to true, if signature is to be preserved. |
| [get_SaveAsTemplate](./get_saveastemplate/) | Set to true, if need to be saved as Outlook File Template(OFT format). |
| [set_PreserveOriginalDates](./set_preserveoriginaldates/) | Sets a value indicating whether it is necessary to generate new saving and modification dates when saving a message. By default the value is true, meaning the creation and modification dates will be not set to DateTime.Now. |
| [set_PreserveSignature](./set_preservesignature/) | Set to true, if signature is to be preserved. |
| [set_SaveAsTemplate](./set_saveastemplate/) | Set to true, if need to be saved as Outlook File Template(OFT format). |

