---
title: LinkedResource
second_title: Aspose.Email für .NET-API-Referenz
description: Stellt eine eingebettete Ressource in einer Nachricht dar.
type: docs
weight: 17640
url: /de/net/aspose.email/linkedresource/
---
## LinkedResource class

Stellt eine eingebettete Ressource in einer Nachricht dar.

```csharp
public class LinkedResource : AttachmentBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [LinkedResource](linkedresource#constructor)(Stream) | Initialisiert eine neue Instanz von[`LinkedResource`](../linkedresource) Klasse. |
| [LinkedResource](linkedresource#constructor_3)(string) | Initialisiert eine neue Instanz von[`LinkedResource`](../linkedresource) Klasse. |
| [LinkedResource](linkedresource#constructor_1)(Stream, ContentType) | Initialisiert eine neue Instanz von[`LinkedResource`](../linkedresource) Klasse. |
| [LinkedResource](linkedresource#constructor_2)(Stream, string) | Initialisiert eine neue Instanz von[`LinkedResource`](../linkedresource) Klasse. |
| [LinkedResource](linkedresource#constructor_4)(string, ContentType) | Initialisiert eine neue Instanz von[`LinkedResource`](../linkedresource) Klasse. |
| [LinkedResource](linkedresource#constructor_5)(string, string) | Initialisiert eine neue Instanz von[`LinkedResource`](../linkedresource) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ContentDisposition](../../aspose.email/linkedresource/contentdisposition) { get; } | erhält Inhaltsdisposition header |
| [ContentId](../../aspose.email/attachmentbase/contentid) { get; set; } | Ruft die Inhalts-ID ab oder legt sie fest. |
| [ContentLink](../../aspose.email/linkedresource/contentlink) { get; set; } | Ruft einen URI ab oder legt ihn fest, mit dem die Ressource übereinstimmen muss. |
| [ContentStream](../../aspose.email/attachmentbase/contentstream) { get; set; } | Ruft den Inhaltsstream ab oder legt ihn fest. |
| [ContentType](../../aspose.email/attachmentbase/contenttype) { get; set; } | Ruft den Inhaltstyp ab oder legt ihn fest. |
| virtual [Headers](../../aspose.email/attachmentbase/headers) { get; } | Ruft die Header-Sammlung des Anhangs ab. |
| [TransferEncoding](../../aspose.email/attachmentbase/transferencoding) { get; set; } | Ruft die Übertragungscodierung ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [CreateLinkedResourceFromString](../../aspose.email/linkedresource/createlinkedresourcefromstring#createlinkedresourcefromstring)(string) | Erstellt die verknüpfte Ressource aus Zeichenfolge. |
| static [CreateLinkedResourceFromString](../../aspose.email/linkedresource/createlinkedresourcefromstring#createlinkedresourcefromstring_1)(string, ContentType) | Erstellt die verknüpfte Ressource aus Zeichenfolge. |
| static [CreateLinkedResourceFromString](../../aspose.email/linkedresource/createlinkedresourcefromstring#createlinkedresourcefromstring_2)(string, Encoding, string) | Erstellt die verknüpfte Ressource aus Zeichenfolge. |
| [Dispose](../../aspose.email/attachmentbase/dispose)() | Führt anwendungsdefinierte Aufgaben im Zusammenhang mit dem Freigeben, Freigeben oder Zurücksetzen nicht verwalteter Ressourcen aus. |
| virtual [Save](../../aspose.email/attachmentbase/save)(Stream) | Speichert den angegebenen Stream. |
| virtual [Save](../../aspose.email/attachmentbase/save)(string) | Speichert den angegebenen Dateinamen. |

### Siehe auch

* class [AttachmentBase](../attachmentbase)
* namensraum [Aspose.Email](../../aspose.email)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->