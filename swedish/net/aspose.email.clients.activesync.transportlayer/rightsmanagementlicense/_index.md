---
title: RightsManagementLicense
second_title: Aspose.Email för .NET API-referens
description: Innehåller inställningarna för rättighetspolicymall för mallen som tillämpas på e-postmeddelandet som synkroniseras.
type: docs
weight: 1900
url: /sv/net/aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/
---
## RightsManagementLicense class

Innehåller inställningarna för rättighetspolicymall för mallen som tillämpas på e-postmeddelandet som synkroniseras.

```csharp
public class RightsManagementLicense
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [RightsManagementLicense](rightsmanagementlicense)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ContentExpiryDate](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/contentexpirydate) { get; set; } | Anger utgångsdatum för licensen. ContentExpiryDate-elementet är satt till "9999-12-30T23:59:59.999Z" om rättighetshanteringslicensen inte har något utgångsdatum angivet. |
| [ContentOwner](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/contentowner) { get; set; } | Anger om innehållet i det ursprungliga e-postmeddelandet kan ändras av användaren när användaren vidarebefordrar, svarar eller svarar på allt på e-postmeddelandet. Värdet är TRUE om e-postmeddelandet kan ändras av användaren; annars, FALSE. Ett värde på FALSE kräver att klienten MÅSTE utesluta det ursprungliga rättighetshanterade e-postmeddelandet från SmartForward- eller SmartReply-begäran. Följaktligen är inline-svar inte tillåtna om EditAllowed-elementet är inställt på FALSE. När EditAllowed är inställt på FALSE och ReplaceMime inte finns i en SmartForward- eller SmartReply-förfrågan, kommer servern att lägga till det ursprungliga rättighetshanterade e-postmeddelandet som en bilaga till det nya meddelandet. Omvänt, om ReplaceMime finns, kommer servern inte att bifoga det ursprungliga rättighetshanterade e-postmeddelandet som en bilaga. |
| [EditAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/editallowed) { get; set; } | Anger om innehållet i det ursprungliga e-postmeddelandet kan ändras av användaren när användaren vidarebefordrar, svarar eller svarar på allt på e-postmeddelandet. Värdet är TRUE om e-postmeddelandet kan ändras av användaren; annars, FALSE. Ett värde på FALSE kräver att klienten MÅSTE utesluta det ursprungliga rättighetshanterade e-postmeddelandet från SmartForward- eller SmartReply-begäran. Följaktligen är inline-svar inte tillåtna om EditAllowed-elementet är inställt på FALSE. När EditAllowed är inställt på FALSE och ReplaceMime inte finns i en SmartForward- eller SmartReply-förfrågan, kommer servern att lägga till det ursprungliga rättighetshanterade e-postmeddelandet som en bilaga till det nya meddelandet. Omvänt, om composemail:ReplaceMime finns, kommer inte servern att bifoga det ursprungliga rättighetshanterade e-postmeddelandet som en bilaga. |
| [ExportAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/exportallowed) { get; set; } | Anger om IRM-skyddet på e-postmeddelandet kan tas bort av användaren. Värdet är TRUE om användaren kan ta bort IRM-skyddet när användaren vidarebefordrar, svarar eller svarar på allt på e-postmeddelandet; annars, FALSE. Om ett rättighetshanterat e-postmeddelande vidarebefordras eller besvaras med kommandot SmartForward eller SmartReply, utvärderas följande villkor: - Den ursprungliga rättighetspolicymallen har ExportAllowed-elementet satt till TRUE - TemplateID på den nya meddelande är satt till mallen "Ingen begränsning" (MallID-värde "00000000-0000-0000-0000-000000000000") Om båda villkoren är sanna tas IRM-skyddet bort från det utgående meddelandet. Det ursprungliga meddelandet behåller sitt IRM-skydd. |
| [ExtractAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/extractallowed) { get; set; } | Anger om användaren kan kopiera innehåll från e-postmeddelandet. Värdet är TRUE om innehållet i e-postmeddelandet kan klippas ut, kopieras eller en skärmdump kan tas av innehållet; annars, FALSE. |
| [ForwardAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/forwardallowed) { get; set; } | Anger om användaren kan vidarebefordra e-postmeddelandet. Värdet är TRUE om användaren kan vidarebefordra e-postmeddelandet; annars, FALSE. |
| [ModifyRecipientsAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/modifyrecipientsallowed) { get; set; } | Anger om användaren kan ändra mottagarlistan när användaren vidarebefordrar, eller svara på e-postmeddelandet. Värdet är TRUE om användaren kan ändra mottagarlistan (1); annars, FALSE. |
| [Owner](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/owner) { get; set; } | Anger om användaren är ägaren till e-postmeddelandet. Värdet är TRUE om användaren är ägaren till e-postmeddelandet; annars FALSKT. Värdet TRUE indikerar att den autentiserade användaren har ägarrättigheter till detta meddelande. Detta element används endast för informationspresentation. De tillåtna elementen (EditAllowed, ReplyAllowed, etc.) används för att utvärdera om en viss åtgärd är tillåten eller begränsad. |
| [PrintAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/printallowed) { get; set; } | Anger om e-postmeddelandet kan skrivas ut av användaren. Detta element indikerar inte klientstöd för att skriva ut ett e-postmeddelande; den anger bara om e-postmeddelandet kan skrivas ut om klienten stöder utskrift. Värdet är TRUE om e-postmeddelandet kan skrivas ut av användaren; annars, FALSE. |
| [ProgrammaticAccessAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/programmaticaccessallowed) { get; set; } | Anger om innehållet i e-postmeddelandet kan nås programmatiskt av tredjepartsprogram. Värdet är TRUE om tredjepartsprogram kan komma åt innehållet i e-postmeddelandet programmatiskt; annars FALSKT. Värdet TRUE anger om det skyddade innehållet är tillgängligt för andra applikationer. Skyddat innehåll består av meddelandetexten och bilagor. |
| [ReplyAllAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/replyallallowed) { get; set; } | Anger om användaren kan svara alla mottagarna (1) av det ursprungliga e-postmeddelandet. Värdet är TRUE om användaren kan svara alla mottagarna av e-postmeddelandet; annars, FALSE. |
| [ReplyAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/replyallowed) { get; set; } | Anger om användaren får svara på e-postmeddelandet. Värdet är TRUE om användaren kan svara på e-postmeddelandet; annars, FALSE. |
| [TemplateDescription](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templatedescription) { get; set; } | Innehåller en beskrivning av rättighetspolicymallen som representeras av det överordnade RightsManagementLicense-elementet. Detta element används endast i informationssyfte. Maxlängden på TemplateDescription-elementet är 10240 tecken. |
| [TemplateID](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templateid) { get; set; } | Innehåller en sträng som identifierar rättighetspolicymallen som representeras av det överordnade RightsManagementLicense-elementet. |
| [TemplateName](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templatename) { get; set; } | Anger namnet på rättighetspolicymallen som representeras av det överordnade RightsManagementLicense-elementet. Detta element används endast i informationssyfte. Maxlängden på TemplateName-elementet är 256 tecken. |

### Se även

* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
