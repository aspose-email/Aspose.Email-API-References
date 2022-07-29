---
title: OOFMessage
second_title: Aspose.Email för .NET API-referens
description: Anger OOF-meddelandet för en viss publik. Exchange 2007 Exchange 2010 och Exchange 2013 kräver att svarsmeddelandet för okända externa och kända externa målgrupper är detsamma. Egenskapen stöder följande tre målgrupper för ett OOF-meddelande Intern  En användare som är i samma organisation som den sändande användaren. Känd extern  En användare som är utanför den sändande användarens organisation men som är representerad i den sändande användarens kontakter. Okänd extern  En användare som är utanför den sändande användarens organisation. organisation och är inte representerad i den avsändande användarens kontakter.
type: docs
weight: 1610
url: /sv/net/aspose.email.clients.activesync.transportlayer/oofmessage/
---
## OOFMessage class

Anger OOF-meddelandet för en viss publik. Exchange 2007, Exchange 2010 och Exchange 2013 kräver att svarsmeddelandet för okända externa och kända externa målgrupper är detsamma. Egenskapen stöder följande tre målgrupper för ett OOF-meddelande: Intern — En användare som är i samma organisation som den sändande användaren. Känd extern — En användare som är utanför den sändande användarens organisation, men som är representerad i den sändande användarens kontakter. Okänd extern — En användare som är utanför den sändande användarens organisation. organisation och är inte representerad i den avsändande användarens kontakter.

```csharp
public class OOFMessage
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [OOFMessage](oofmessage)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AppliesToExternalKnown](../../aspose.email.clients.activesync.transportlayer/oofmessage/appliestoexternalknown) { get; set; } | Indikerar att OOF-meddelandet gäller kända externa användare. |
| [AppliesToExternalUnknown](../../aspose.email.clients.activesync.transportlayer/oofmessage/appliestoexternalunknown) { get; set; } | Indikerar att OOF-meddelandet gäller okända externa användare. |
| [AppliesToInternal](../../aspose.email.clients.activesync.transportlayer/oofmessage/appliestointernal) { get; set; } | Indikerar att OOF-meddelandet gäller interna användare. |
| [BodyType](../../aspose.email.clients.activesync.transportlayer/oofmessage/bodytype) { get; set; } | Anger formatet för OOF-meddelandet. Följande är de tillåtna värdena för BodyType-elementet: - Text - HTML |
| [Enabled](../../aspose.email.clients.activesync.transportlayer/oofmessage/enabled) { get; set; } | Anger om ett OOF-meddelande skickas till denna publik medan den sändande användaren är OOF. |
| [ReplyMessage](../../aspose.email.clients.activesync.transportlayer/oofmessage/replymessage) { get; set; } | Anger meddelandet som ska visas för en viss publik när användaren är OOF. |

### Se även

* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->