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
| [MsgLoadOptions](msgloadoptions/)() | Initializes a new instance of the `MsgLoadOptions` class with the default options. |

## Properties

| Name | Description |
| --- | --- |
| [DeferAttachmentContent](../../aspose.email/msgloadoptions/deferattachmentcontent/) { get; set; } | Gets or sets a value indicating whether attachment content is read on demand instead of being loaded into memory while the message is being loaded. The default value is false. |
| [DeferralThreshold](../../aspose.email/msgloadoptions/deferralthreshold/) { get; set; } | Gets or sets the size, in bytes, from which [`DeferAttachmentContent`](./deferattachmentcontent/) applies; smaller attachments are always loaded at once. The default is 4096. |
| [KeepOriginalEmailAddresses](../../aspose.email/msgloadoptions/keeporiginalemailaddresses/) { get; set; } | Gets or sets a value indicating whether the sender and recipient addresses are taken from the transport headers of the message as they are. When `false` (the default), they are rebuilt from the MAPI properties of the message. |
| [MessageFormat](../../aspose.email/loadoptions/messageformat/) { get; } | Gets the format this options object loads, as determined by its class: EML, MSG, MHTML, HTML and so on. |
| [PreferredTextEncoding](../../aspose.email/loadoptions/preferredtextencoding/) { get; set; } | Gets or sets the encoding used for the subject and the body regardless of what the message declares. The default is `null`: the declared encoding is used. |
| [PreserveEmbeddedMessageFormat](../../aspose.email/loadoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether embedded messages keep their original format (EML or MSG) when loaded. The default is `false`. |
| [PreserveRtfContent](../../aspose.email/msgloadoptions/preservertfcontent/) { get; set; } | Gets or sets a value indicating whether the RTF body of the MSG file is kept in the loaded message. The default is `false`. |
| [PreserveTnefAttachments](../../aspose.email/msgloadoptions/preservetnefattachments/) { get; set; } | Gets or sets a value indicating whether a TNEF attachment (winmail.dat) is kept as it is instead of being decoded into its files. The default is `false`. |
| [RemoveSignature](../../aspose.email/loadoptions/removesignature/) { get; set; } | Gets or sets a value indicating whether the digital signature is removed from a signed message while it is loaded. |
| [Timeout](../../aspose.email/msgloadoptions/timeout/) { get; set; } | Gets or sets the time limit, in milliseconds, for formatting the body during the conversion. The default is 3000 (3 seconds). |

## Events

| Name | Description |
| --- | --- |
| event [TimeoutReached](../../aspose.email/msgloadoptions/timeoutreached/) | Occurs when formatting the body takes longer than [`Timeout`](./timeout/). |

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


