---
title: Class MapiConversionOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiConversionOptions class. This class allows the user to specify additional options when converting from MailMessage to MapiMessage
type: docs
weight: 18380
url: /net/aspose.email.mapi/mapiconversionoptions/
---
## MapiConversionOptions class

This class allows the user to specify additional options when converting from MailMessage to MapiMessage.

```csharp
public class MapiConversionOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiConversionOptions](mapiconversionoptions/#constructor)() | Initializes a new instance of the `MapiConversionOptions` class. |
| [MapiConversionOptions](mapiconversionoptions/#constructor_1)(OutlookMessageFormat) | Initializes a new instance of the `MapiConversionOptions` class with specified OutlookMessageFormat. |

## Properties

| Name | Description |
| --- | --- |
| static [ASCIIFormat](../../aspose.email.mapi/mapiconversionoptions/asciiformat/) { get; } | Returns MapiConversionOptions with OutlookMessageFormat is ASCII(PreserveSignature is False, UseBodyCompression is False). |
| static [UnicodeFormat](../../aspose.email.mapi/mapiconversionoptions/unicodeformat/) { get; } | Returns MapiConversionOptions with OutlookMessageFormat is Unicode(PreserveSignature is False, UseBodyCompression is False). |
| [CustomProgressHandler](../../aspose.email.mapi/mapiconversionoptions/customprogresshandler/) { get; set; } |  |
| [ForcedRtfBodyForAppointment](../../aspose.email.mapi/mapiconversionoptions/forcedrtfbodyforappointment/) { get; set; } | Gets or sets a value indicating whether it is necessary to use forced RTF body for an appointment. Default value is true. |
| [Format](../../aspose.email.mapi/mapiconversionoptions/format/) { get; set; } | Represents outlook message format. |
| [PreserveEmbeddedMessageFormat](../../aspose.email.mapi/mapiconversionoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether it is necessary to preserve EML format of embedded message at converting to MapiMessage. By default the value is false. |
| [PreserveOriginalAddresses](../../aspose.email.mapi/mapiconversionoptions/preserveoriginaladdresses/) { get; set; } | Gets or sets a value indicating whether it is necessary to keep original value of mail addresses (without validation). |
| [PreserveOriginalDates](../../aspose.email.mapi/mapiconversionoptions/preserveoriginaldates/) { get; set; } | Gets or sets a value indicating whether it is necessary to generate new saving and modification dates when converting a message. |
| [PreserveSignature](../../aspose.email.mapi/mapiconversionoptions/preservesignature/) { get; set; } | Set to true, if signature is to be preserved. |
| [UseBodyCompression](../../aspose.email.mapi/mapiconversionoptions/usebodycompression/) { get; set; } | Set to true, if need RTF body compression. |

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


