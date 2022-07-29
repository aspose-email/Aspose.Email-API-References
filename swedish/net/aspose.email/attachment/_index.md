---
title: Attachment
second_title: Aspose.Email för .NET API-referens
description: Representerar en e-postbilaga.
type: docs
weight: 350
url: /sv/net/aspose.email/attachment/
---
## Attachment class

Representerar en e-postbilaga.

```csharp
public class Attachment : AttachmentBase, IAttachment, IPreferredTextEncodingProvider
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Attachment](attachment#constructor_3)(string) | Initierar en ny instans av[`Attachment`](../attachment) class. |
| [Attachment](attachment#constructor)(Stream, ContentType) | Initierar en ny instans av[`Attachment`](../attachment) class. |
| [Attachment](attachment#constructor_1)(Stream, string) | Initierar en ny instans av[`Attachment`](../attachment) class. |
| [Attachment](attachment#constructor_4)(string, ContentType) | Initierar en ny instans av[`Attachment`](../attachment) class. |
| [Attachment](attachment#constructor_5)(string, string) | Initierar en ny instans av[`Attachment`](../attachment) class. |
| [Attachment](attachment#constructor_2)(Stream, string, string) | Initierar en ny instans av[`Attachment`](../attachment) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ContentDisposition](../../aspose.email/attachment/contentdisposition) { get; } | Får Content-Disposition header |
| [ContentId](../../aspose.email/attachmentbase/contentid) { get; set; } | Hämtar eller ställer in innehålls-id. |
| [ContentStream](../../aspose.email/attachmentbase/contentstream) { get; set; } | Hämtar eller ställer in innehållsströmmen. |
| [ContentType](../../aspose.email/attachmentbase/contenttype) { get; set; } | Hämtar eller ställer in typen av innehåll. |
| virtual [Headers](../../aspose.email/attachmentbase/headers) { get; } | Får rubriksamling av bilagor. |
| [IsEmbeddedMessage](../../aspose.email/attachment/isembeddedmessage) { get; } | Får ett värde som indikerar om bilagan är ett inbäddat meddelande. |
| [IsUri](../../aspose.email/attachment/isuri) { get; } | Får ett värde som indikerar om bilagan är URI-attachment. |
| [Name](../../aspose.email/attachment/name) { get; set; } | Hämtar eller ställer in en bilaga name |
| [NameEncoding](../../aspose.email/attachment/nameencoding) { get; set; } | Hämtar eller ställer in en kodning av bilagans namn |
| [PreferredTextEncoding](../../aspose.email/attachment/preferredtextencoding) { get; set; } | Hämtar eller ställer in en föredragen textkodning |
| [TransferEncoding](../../aspose.email/attachmentbase/transferencoding) { get; set; } | Hämtar eller ställer in överföringskodningen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [CreateAttachmentFromString](../../aspose.email/attachment/createattachmentfromstring#createattachmentfromstring)(string, ContentType) | Skapar bilagan från sträng. |
| static [CreateAttachmentFromString](../../aspose.email/attachment/createattachmentfromstring#createattachmentfromstring_1)(string, string) | Skapar bilagan från sträng. |
| static [CreateAttachmentFromString](../../aspose.email/attachment/createattachmentfromstring#createattachmentfromstring_2)(string, string, Encoding, string) | Skapar bilagan från sträng. |
| [Dispose](../../aspose.email/attachmentbase/dispose)() | Utför programdefinierade uppgifter associerade med att frigöra, frigöra eller återställa ohanterade resurser. |
| virtual [Save](../../aspose.email/attachmentbase/save)(Stream) | Sparar den angivna strömmen. |
| virtual [Save](../../aspose.email/attachmentbase/save)(string) | Sparar det angivna filnamnet. |

### Se även

* class [AttachmentBase](../attachmentbase)
* interface [IAttachment](../iattachment)
* interface [IPreferredTextEncodingProvider](../ipreferredtextencodingprovider)
* namnutrymme [Aspose.Email](../../aspose.email)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->