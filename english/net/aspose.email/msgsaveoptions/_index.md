---
title: Class MsgSaveOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.MsgSaveOptions class. Options for saving a MailMessage to Outlook MSG format with ANSI or Unicode strings or to an Outlook template OFT
type: docs
weight: 18140
url: /net/aspose.email/msgsaveoptions/
---
## MsgSaveOptions class

Options for saving a [`MailMessage`](../mailmessage/) to Outlook MSG format, with ANSI or Unicode strings, or to an Outlook template (OFT).

```csharp
public class MsgSaveOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MsgSaveOptions](msgsaveoptions/)(MailMessageSaveType) | Initializes a new instance of the `MsgSaveOptions` class for the specified format. |

## Properties

| Name | Description |
| --- | --- |
| [CustomProgressHandler](../../aspose.email/saveoptions/customprogresshandler/) { get; set; } | Gets or sets a handler that is called as the saving progresses. |
| [MailMessageSaveType](../../aspose.email/saveoptions/mailmessagesavetype/) { get; set; } | Gets or sets the format the options save to. |
| [PreserveOriginalDates](../../aspose.email/msgsaveoptions/preserveoriginaldates/) { get; set; } | Gets or sets a value indicating whether the dates of the message are kept. When `false`, the creation and modification dates are set to the time of saving. The default is `true`. |

## Remarks

Get ready-made options from [`DefaultMsgUnicode`](../saveoptions/defaultmsgunicode/), [`DefaultMsg`](../saveoptions/defaultmsg/) or [`DefaultOft`](../saveoptions/defaultoft/).

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


