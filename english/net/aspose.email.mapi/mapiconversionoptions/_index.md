---
title: Class MapiConversionOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiConversionOptions class. Options that control how a MailMessage is converted to a MapiMessage
type: docs
weight: 17170
url: /net/aspose.email.mapi/mapiconversionoptions/
---
## MapiConversionOptions class

Options that control how a [`MailMessage`](../../aspose.email/mailmessage/) is converted to a [`MapiMessage`](../mapimessage/).

```csharp
public class MapiConversionOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiConversionOptions](mapiconversionoptions/#constructor)() | Initializes a new instance of the `MapiConversionOptions` class that produces an ANSI message. |
| [MapiConversionOptions](mapiconversionoptions/#constructor_1)(OutlookMessageFormat) | Initializes a new instance of the `MapiConversionOptions` class that produces a message in the specified format. |

## Properties

| Name | Description |
| --- | --- |
| static [ASCIIFormat](../../aspose.email.mapi/mapiconversionoptions/asciiformat/) { get; } | Gets new options that produce a message in ANSI (8-bit) format. |
| static [UnicodeFormat](../../aspose.email.mapi/mapiconversionoptions/unicodeformat/) { get; } | Gets new options that produce a message in Unicode format. |
| [CustomProgressHandler](../../aspose.email.mapi/mapiconversionoptions/customprogresshandler/) { get; set; } | Gets or sets a handler that is called as the conversion progresses. |
| [ForcedRtfBodyForAppointment](../../aspose.email.mapi/mapiconversionoptions/forcedrtfbodyforappointment/) { get; set; } | Gets or sets a value indicating whether an appointment or a meeting request gets an RTF body built from the body of the source message. The default is `false`. |
| [Format](../../aspose.email.mapi/mapiconversionoptions/format/) { get; set; } | Gets or sets the format of the resulting message: Unicode or ANSI. The default is ANSI. |
| [PreserveEmbeddedMessageFormat](../../aspose.email.mapi/mapiconversionoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether embedded messages stay in EML format instead of being converted to MSG. The default is `false`. |
| [PreserveEmptyDates](../../aspose.email.mapi/mapiconversionoptions/preserveemptydates/) { get; set; } | Gets or sets a value indicating whether the creation and modification dates are left unset. When `false` (the default), both are set to the time of the conversion. |
| [PreserveOriginalAddresses](../../aspose.email.mapi/mapiconversionoptions/preserveoriginaladdresses/) { get; set; } | Gets or sets a value indicating whether the addresses are kept exactly as in the source message, without validation. The default is `false`. |
| [PreserveOriginalDates](../../aspose.email.mapi/mapiconversionoptions/preserveoriginaldates/) { get; set; } | Gets or sets a value indicating whether the sent date of the source message is kept. When `false`, the time of the conversion is used. The default is `true`. |
| [RemoveSignature](../../aspose.email.mapi/mapiconversionoptions/removesignature/) { get; set; } | Gets or sets a value indicating whether the digital signature is removed from a signed message during the conversion. |
| [UseBodyCompression](../../aspose.email.mapi/mapiconversionoptions/usebodycompression/) { get; set; } | Gets or sets a value indicating whether the RTF body is stored compressed. The default is `false`. |

## Remarks

Pass an instance to [`FromMailMessage`](../mapimessage/frommailmessage/). [`UnicodeFormat`](./unicodeformat/) and [`ASCIIFormat`](./asciiformat/) return ready-made options for the two MSG formats.

## Examples

This example converts an EML file to a Unicode MSG file, keeping the original dates.

[C#]

```csharp
var eml = MailMessage.Load("message.eml");

var options = MapiConversionOptions.UnicodeFormat;
options.PreserveOriginalDates = true;

using (MapiMessage msg = MapiMessage.FromMailMessage(eml, options))
{
    msg.Save("message.msg");
}
```

[Visual Basic]

```csharp
Dim eml = MailMessage.Load("message.eml")

Dim options = MapiConversionOptions.UnicodeFormat
options.PreserveOriginalDates = True

Using msg As MapiMessage = MapiMessage.FromMailMessage(eml, options)
    msg.Save("message.msg")
End Using
```

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


