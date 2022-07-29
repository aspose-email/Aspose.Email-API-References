---
title: BodyPart
second_title: Aspose.Email för .NET API-referens
description: Anger detaljer om meddelandedelen av ett e-postmeddelande i ett svar. BodyPart-elementet MÅSTE inkluderas i ett kommandosvar när BodyPartPreference anges i en begäran.
type: docs
weight: 1040
url: /sv/net/aspose.email.clients.activesync.transportlayer/bodypart/
---
## BodyPart class

Anger detaljer om meddelandedelen av ett e-postmeddelande i ett svar. BodyPart-elementet MÅSTE inkluderas i ett kommandosvar när BodyPartPreference anges i en begäran.

```csharp
public class BodyPart
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [BodyPart](bodypart)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Data](../../aspose.email.clients.activesync.transportlayer/bodypart/data) { get; set; } | Innehållet i dataelementet är en sträng i det format som specificeras av egenskapen Type. Om värdet för typen är RTF, kodas värdet på dataelementet med hjälp av base64-kodning. Om egenskapen Truncated är inställd på sant, trunkeras data i dataelementet. Egenskapen EstimatedDataSize ger en grov uppskattning av den faktiska storleken på hela innehållet i datasträngen. |
| [EstimatedDataSize](../../aspose.email.clients.activesync.transportlayer/bodypart/estimateddatasize) { get; set; } | Anger en informativ uppskattning av storleken på data som är associerade med det överordnade elementet. Elementet EstimatedDataSize SKA presenteras närhelst Trunkated-elementet är satt till TRUE |
| [Preview](../../aspose.email.clients.activesync.transportlayer/bodypart/preview) { get; set; } | Innehåller Unicode-textmeddelandet eller förhandsgranskningen av meddelandedelen som returnerats till klienten. |
| [Status](../../aspose.email.clients.activesync.transportlayer/bodypart/status) { get; set; } | Innehåller en kod och beskrivning som indikerar framgång eller misslyckande av operationen |
| [Truncated](../../aspose.email.clients.activesync.transportlayer/bodypart/truncated) { get; set; } | Anger om objektets brödtext har trunkerats enligt BodyPreference-elementet som anges av klienten. Om värdet är TRUE, har objektets brödtext trunkerats. Om värdet är FALSE eller Truncated-egenskapen inte har angetts, har objektets brödtext inte trunkerats. |
| [Type](../../aspose.email.clients.activesync.transportlayer/bodypart/type) { get; set; } | Anger formattypen för objektets innehåll. |

### Se även

* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->