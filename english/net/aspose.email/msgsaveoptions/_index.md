---
title: Class MsgSaveOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.MsgSaveOptions class. This class allows the user to specify additional settings when saving a MailMessage in the MsgASCII and MsgUnicode format
type: docs
weight: 19300
url: /net/aspose.email/msgsaveoptions/
---
## MsgSaveOptions class

This class allows the user to specify additional settings when saving a MailMessage in the Msg(ASCII) and Msg(Unicode) format.

```csharp
public class MsgSaveOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MsgSaveOptions](msgsaveoptions/)(MailMessageSaveType) | Initializes a new instance of this class that can be used to save a MailMessage in the Msg(ASCII) and Msg(Unicode) format. |

## Properties

| Name | Description |
| --- | --- |
| [CustomProgressHandler](../../aspose.email/saveoptions/customprogresshandler/) { get; set; } | Represents method that usually supplied by calling side and handles progress events. |
| [MailMessageSaveType](../../aspose.email/saveoptions/mailmessagesavetype/) { get; set; } | Represents the mail message save type.It can be in eml,msg(ASCII or Unicode),mhtml or html format. The default value is Eml. |
| [PreserveOriginalDates](../../aspose.email/msgsaveoptions/preserveoriginaldates/) { get; set; } | Gets or sets a value indicating whether it is necessary to generate new saving and modification dates when saving a message. By default the value is false, meaning the creation and modification dates will be set to DateTime.Now. |

## Examples

The following example shows how to save as MSG with preserved dates.

[C#]

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

[Visual Basic]

```csharp
' Initialize and Load an existing EML file by specifying the MessageFormat
Dim eml = MailMessage.Load("Message.eml")

' Save as msg with preserved dates
    Dim msgSaveOptions = New MsgSaveOptions(MailMessageSaveType.OutlookMessageFormatUnicode) With {
        .PreserveOriginalDates = True
    }

eml.Save("outTest_out.msg", msgSaveOptions)
```

### See Also

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


