---
title: Class MailConversionOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MailConversionOptions class. Provides options for controlling how MapiMessage instances are converted to MailMessage objects. This class allows you to customize the conversion behavior for TNEF handling embedded message format preservation RTF content and email address management
type: docs
weight: 16660
url: /net/aspose.email.mapi/mailconversionoptions/
---
## MailConversionOptions class

Provides options for controlling how [`MapiMessage`](../mapimessage/) instances are converted to [`MailMessage`](../../aspose.email/mailmessage/) objects. This class allows you to customize the conversion behavior for TNEF handling, embedded message format preservation, RTF content, and email address management.

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
| [ConvertAsTnef](../../aspose.email.mapi/mailconversionoptions/convertastnef/) { get; set; } | Set to true to import the MapiMessage information into a MailMessage object with MapiMessage as TNEF attachment. |
| [KeepOriginalEmailAddresses](../../aspose.email.mapi/mailconversionoptions/keeporiginalemailaddresses/) { get; set; } | Gets or sets a value indicating whether need keep original email address. |
| [PreserveEmbeddedMessageFormat](../../aspose.email.mapi/mailconversionoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether it is necessary to preserve MSG format of embedded message at converting to MailMessage. By default the value is false. |
| [PreserveRtfContent](../../aspose.email.mapi/mailconversionoptions/preservertfcontent/) { get; set; } | Gets or sets a value indicating whether need keep rtf body in MailMessage. |
| [Timeout](../../aspose.email.mapi/mailconversionoptions/timeout/) { get; set; } | Limits the time in milliseconds of formatting message while converting. Default value 3 sec. |

## Events

| Name | Description |
| --- | --- |
| event [TimeoutReached](../../aspose.email.mapi/mailconversionoptions/timeoutreached/) | Raised if timed out while converting to MailMessage. |

## Remarks

Use this class with [`ToMailMessage`](../mapimessage/tomailmessage/) to specify custom conversion options. The [`ConvertAsTnef`](./convertastnef/) property enables TNEF attachment preservation, [`PreserveEmbeddedMessageFormat`](./preserveembeddedmessageformat/) maintains original embedded message formats, [`PreserveRtfContent`](./preservertfcontent/) retains RTF body formatting, and [`Timeout`](./timeout/) controls the conversion time limit.

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


