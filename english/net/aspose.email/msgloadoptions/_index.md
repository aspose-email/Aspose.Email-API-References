---
title: Class MsgLoadOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.MsgLoadOptions class. Provides options for controlling how MailMessage instances are loaded from MSG format. This class allows you to customize the loading behavior for Outlook MSG files including TNEF attachment handling RTF body preservation email address preservation and timeout configuration
type: docs
weight: 18130
url: /net/aspose.email/msgloadoptions/
---
## MsgLoadOptions class

Provides options for controlling how [`MailMessage`](../mailmessage/) instances are loaded from MSG format. This class allows you to customize the loading behavior for Outlook MSG files, including TNEF attachment handling, RTF body preservation, email address preservation, and timeout configuration.

```csharp
public class MsgLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MsgLoadOptions](msgloadoptions/)() | Initializes a new instance of this class that can be used to loading MailMessage from Msg format. |

## Properties

| Name | Description |
| --- | --- |
| [KeepOriginalEmailAddresses](../../aspose.email/msgloadoptions/keeporiginalemailaddresses/) { get; set; } | Gets or sets a value indicating whether need keep original email address. |
| [MessageFormat](../../aspose.email/loadoptions/messageformat/) { get; } | Represents the mail message format.It can be in eml,msg or mhtml format. The default value is Eml. |
| [PreferredTextEncoding](../../aspose.email/loadoptions/preferredtextencoding/) { get; set; } | Gets or sets preferred encoding for message. Forcibly sets the preferred encoding for message subject and body. The default value is null. |
| [PreserveEmbeddedMessageFormat](../../aspose.email/loadoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading. By default the value is false. |
| [PreserveRtfContent](../../aspose.email/msgloadoptions/preservertfcontent/) { get; set; } | Gets or sets a value indicating whether need keep rtf body in MailMessage. |
| [PreserveTnefAttachments](../../aspose.email/msgloadoptions/preservetnefattachments/) { get; set; } | Controls loading TNEF attachment behaviour. By default the value is false. |
| [RemoveSignature](../../aspose.email/loadoptions/removesignature/) { get; set; } | Gets or sets a value indicating whether signature will be removed while loading. |
| [Timeout](../../aspose.email/msgloadoptions/timeout/) { get; set; } | Limits the time in milliseconds of formatting message while converting. Default value 3 sec. |

## Events

| Name | Description |
| --- | --- |
| event [TimeoutReached](../../aspose.email/msgloadoptions/timeoutreached/) | Raised if timed out while converting to MailMessage. |

## Remarks

Use this class with [`Load`](../mailmessage/load/) to load Outlook MSG files and control various loading options. MSG is the native format for Outlook messages and can contain various Outlook-specific features. The [`PreserveTnefAttachments`](./preservetnefattachments/) property controls TNEF handling, [`PreserveRtfContent`](./preservertfcontent/) preserves RTF body formatting, and [`Timeout`](./timeout/) limits the conversion time.

## Examples

The following example shows how to use MsgLoadOptions to load an Outlook MSG file with custom settings.

[C#]

```csharp
// Create MSG load options with custom settings
var loadOptions = new MsgLoadOptions()
{
    PreserveTnefAttachments = true,
    PreserveRtfContent = true,
    KeepOriginalEmailAddresses = true,
    Timeout = 5000
};

// Handle timeout event
loadOptions.TimeoutReached += (sender, e) =>
{
    Console.WriteLine("Message loading timed out");
};

// Load MSG file with custom options
using (MailMessage message = MailMessage.Load("message.msg", loadOptions))
{
    // Convert to EML format
    message.Save("output.eml", SaveOptions.DefaultEml);
}
```

[Visual Basic]

```csharp
' Create MSG load options with custom settings
Dim loadOptions As New MsgLoadOptions() With {
    .PreserveTnefAttachments = True,
    .PreserveRtfContent = True,
    .KeepOriginalEmailAddresses = True,
    .Timeout = 5000
}

' Handle timeout event
AddHandler loadOptions.TimeoutReached, Sub(sender, e)
                                            Console.WriteLine("Message loading timed out")
                                        End Sub

' Load MSG file with custom options
Using message As MailMessage = MailMessage.Load("message.msg", loadOptions)
    ' Convert to EML format
    message.Save("output.eml", SaveOptions.DefaultEml)
End Using
```

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


