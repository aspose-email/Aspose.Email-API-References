---
title: Class MailConversionOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MailConversionOptions class. Options that control how a MapiMessage is converted to a MailMessage
type: docs
weight: 16660
url: /net/aspose.email.mapi/mailconversionoptions/
---
## MailConversionOptions class

Options that control how a [`MapiMessage`](../mapimessage/) is converted to a [`MailMessage`](../../aspose.email/mailmessage/).

```csharp
public class MailConversionOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MailConversionOptions](mailconversionoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ConvertAsTnef](../../aspose.email.mapi/mailconversionoptions/convertastnef/) { get; set; } | Gets or sets a value indicating whether the MAPI message is carried as a TNEF (winmail.dat) attachment of the resulting MailMessage, so that Outlook-specific data is kept. The default is `false`. |
| [KeepOriginalEmailAddresses](../../aspose.email.mapi/mailconversionoptions/keeporiginalemailaddresses/) { get; set; } | Gets or sets a value indicating whether the sender and recipient addresses are taken from the transport headers of the message as they are. When `false` (the default), they are rebuilt from the MAPI properties of the message. |
| [PreserveEmbeddedMessageFormat](../../aspose.email.mapi/mailconversionoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether embedded messages stay in MSG format instead of being converted to EML. The default is `false`. |
| [PreserveRtfContent](../../aspose.email.mapi/mailconversionoptions/preservertfcontent/) { get; set; } | Gets or sets a value indicating whether the RTF body of the message is kept in the MailMessage. The default is `false`. |
| [Timeout](../../aspose.email.mapi/mailconversionoptions/timeout/) { get; set; } | Gets or sets the time limit, in milliseconds, for formatting the message body during the conversion. The default is 3000 (3 seconds). |

## Events

| Name | Description |
| --- | --- |
| event [TimeoutReached](../../aspose.email.mapi/mailconversionoptions/timeoutreached/) | Occurs when formatting the message body takes longer than [`Timeout`](./timeout/). |

## Remarks

Pass an instance to [`ToMailMessage`](../mapimessage/tomailmessage/).

## Examples

The following example shows how to use MailConversionOptions to convert a MapiMessage to MailMessage with custom settings.

[C#]

```csharp
// Load a MapiMessage from file
MapiMessage mapiMessage = MapiMessage.FromFile("message.msg");

// Create conversion options with custom settings
var conversionOptions = new MailConversionOptions()
{
    ConvertAsTnef = true,
    PreserveEmbeddedMessageFormat = true,
    PreserveRtfContent = true,
    KeepOriginalEmailAddresses = true,
    Timeout = 5000
};

// Handle timeout event
conversionOptions.TimeoutReached += (sender, e) =>
{
    Console.WriteLine("Conversion timed out");
};

// Convert MapiMessage to MailMessage with custom options
MailMessage mailMessage = mapiMessage.ToMailMessage(conversionOptions);

// Save as EML
mailMessage.Save("output.eml", SaveOptions.DefaultEml);
```

[Visual Basic]

```csharp
' Load a MapiMessage from file
Dim mapiMessage As MapiMessage = MapiMessage.FromFile("message.msg")

' Create conversion options with custom settings
Dim conversionOptions As New MailConversionOptions() With {
    .ConvertAsTnef = True,
    .PreserveEmbeddedMessageFormat = True,
    .PreserveRtfContent = True,
    .KeepOriginalEmailAddresses = True,
    .Timeout = 5000
}

' Handle timeout event
AddHandler conversionOptions.TimeoutReached, Sub(sender, e)
                                                    Console.WriteLine("Conversion timed out")
                                                End Sub

' Convert MapiMessage to MailMessage with custom options
Dim mailMessage As MailMessage = mapiMessage.ToMailMessage(conversionOptions)

' Save as EML
mailMessage.Save("output.eml", SaveOptions.DefaultEml)
```

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


