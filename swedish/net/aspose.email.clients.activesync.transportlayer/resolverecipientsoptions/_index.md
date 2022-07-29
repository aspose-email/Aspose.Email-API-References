---
title: ResolveRecipientsOptions
second_title: Aspose.Email för .NET API-referens
description: Innehåller alternativen för att lösa listan över mottagare.
type: docs
weight: 1850
url: /sv/net/aspose.email.clients.activesync.transportlayer/resolverecipientsoptions/
---
## ResolveRecipientsOptions class

Innehåller alternativen för att lösa listan över mottagare.

```csharp
public class ResolveRecipientsOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ResolveRecipientsOptions](resolverecipientsoptions)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Availability](../../aspose.email.clients.activesync.transportlayer/resolverecipientsoptions/availability) { get; set; } | Indikerar för servern att ledig/upptagen-data begärs av klienten och identifierar start- och sluttid för ledig/upptagen-data som ska hämtas. När tillgängligheten ingår i en ResolveRecipients-begäran, hämtar servern ledig/upptagen information för användarna som identifieras i To-elementen som ingår i begäran, och returnerar ledig/upptagen-informationen i MergedFreeBusy i svaret. Om Availability-elementet ingår i ResolveRecipients-begäran, MÅSTE begäran även innehålla ett giltigt StartTime-värde och EndTime-värde. När servern analyserar begäran löser servern först mottagarna som identifierats av To-elementen och bestämmer sedan användarens ledig/upptagen-information för den angivna tidsperioden, innan den returnerar ledig/upptagen-data i MergedFreeBusy. |
| [CertificateRetrieval](../../aspose.email.clients.activesync.transportlayer/resolverecipientsoptions/certificateretrieval) { get; set; } | Anger om S/MIME-certifikat SKA returneras av servern för varje löst mottagare. |
| [MaxAmbiguousRecipients](../../aspose.email.clients.activesync.transportlayer/resolverecipientsoptions/maxambiguousrecipients) { get; set; } | Begränsar antalet förslag som returneras för varje tvetydig mottagarnod i svaret. Värdet på MaxAmbiguousRecipients är begränsat till intervallet 0–9999. Varje tvetydig mottagarnod får bara så många förslag och inte fler. Mottagarantalet, som returneras i RecipientCount, kan användas av klienten för att bestämma det totala antalet förslag som är tillgängliga för den mottagaren. |
| [MaxCertificates](../../aspose.email.clients.activesync.transportlayer/resolverecipientsoptions/maxcertificates) { get; set; } | Begränsar det totala antalet certifikat som returneras av servern. Värdet på MaxCertificates är begränsat till intervallet 0–9999. Denna gräns säkerställer att ingen enskild mottagare får en ofullständig uppsättning certifikat. Om gränsen för Maxcertifikat nås när certifikat för en adresslista räknas upp, kommer den adresslistan inte att få tillbaka några certifikat och ett statusvärde på 8 returneras. |
| [Picture](../../aspose.email.clients.activesync.transportlayer/resolverecipientsoptions/picture) { get; set; } | Indikerar att klienten begär att kontaktfoton ska returneras i serversvaret. Bilden stöds inte när protokollversionen är 12.1 eller 14.0. Innehåller data relaterade till kontaktfoton. |

### Se även

* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->