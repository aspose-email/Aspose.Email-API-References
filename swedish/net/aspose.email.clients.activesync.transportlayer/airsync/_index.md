---
title: AirSync
second_title: Aspose.Email för .NET API-referens
description: AirSync-namnområdet för ActiveSync-protokollet
type: docs
weight: 960
url: /sv/net/aspose.email.clients.activesync.transportlayer/airsync/
---
## AirSync enumeration

AirSync-namnområdet för ActiveSync-protokollet

```csharp
public enum AirSync
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Sync | `5` | Sync-elementet är ett obligatoriskt element i Sync-kommandoförfrågningar och svar som identifierar kroppen av HTTP POST som innehållande ett Sync-kommando (avsnitt 2.2.2.19). Det är toppnivåelementet i XML-strömmen. |
| Responses | `6` | Innehåller svar på operationer som bearbetas av servern. |
| Add | `7` | Skapar ett nytt objekt i en samling på klienten eller på servern. |
| Change | `8` | Modifierar egenskaper för ett befintligt objekt på klientenheten eller servern. |
| Delete | `9` | Tar bort ett objekt på klientenheten eller servern. Objektet identifieras av dess ServerId-element. |
| Fetch | `10` | Används för att begära applikationsdata för ett objekt som trunkerades i ett synkroniseringssvar från servern. |
| SyncKey | `11` | Innehåller ett värde som används av servern för att markera synkroniseringstillståndet för en samling. |
| ClientId | `12` | Innehåller en unik identifierare (vanligtvis ett heltal) som genereras av klienten för att tillfälligt identifiera ett nytt objekt som skapas med hjälp av Add-elementet. |
| ServerId | `13` | Den representerar en unik identifierare som tilldelas av servern till varje objekt som kan synkroniseras. |
| Status | `14` | Indikerar orsaken till misslyckandet i en kommandobegäran. |
| Collection | `15` | Innehåller kommandon och alternativ som gäller en viss samling. |
| Class | `16` | Identifierar klassen för objektet som läggs till i samlingen. |
| CollectionId | `18` | Anger server-ID för mappen som ska synkroniseras. |
| GetChanges | `19` | Begär att servern i sitt svar inkluderar alla väntande ändringar av samlingen som specificeras av ServerId-elementet (avsnitt 2.2.3.151.6). |
| MoreAvailable | `20` | Indikerar att det finns fler ändringar än antalet som begärs i WindowSize-elementet (avsnitt 2.2.3.183). |
| WindowSize | `21` | Anger ett maximalt antal ändrade objekt i en samling eller en begäran som SKA ingå i synkroniseringssvaret. |
| Commands | `22` | Innehåller operationer som gäller en samling. |
| Options | `23` | Innehåller element som styr vissa aspekter av hur synkroniseringen utförs. |
| FilterType | `24` | Anger ett valfritt tidsfönster för objekten som skickas från servern till klienten. Det gäller e-post- och kalendersamlingar. |
| Conflict | `27` | Anger hur konflikten som uppstår när ett objekt har ändrats på både klienten och servern ska lösas. |
| Collections | `28` | Fungerar som en behållare för samlingselementet. |
| ApplicationData | `29` | Innehåller data för ett visst objekt, såsom en kontakt, e-postmeddelande, kalendermöte eller uppgiftsobjekt. Kan användas för att ändra objekt, lägga till objekt eller hämta objekt på klientenheten eller servern. |
| DeletesAsMoves | `30` | Indikerar att alla borttagna objekt SKA flyttas till mappen Deleted Items. |
| Supported | `32` | Anger vilka kontakt- och kalenderelement i en synkroniseringsbegäran som hanteras av klienten. |
| SoftDelete | `33` | Tar bort ett objekt från klienten när det faller utanför FilterType-resultaten (avsnitt 2.2.3.64.2) eller det inte längre ingår som en del av instruktionerna för SyncOptions (avsnitt 2.2.3.115.5). |
| MIMESupport | `34` | Aktiverar MIME-stöd för e-postobjekt som skickas från servern till klienten. |
| MIMETruncation | `35` | Anger om MIME-data för e-postobjektet SKA trunkeras när det skickas från servern till klienten. |
| Wait | `36` | Anger antalet minuter som servern SKA fördröja ett svar om inga nya objekt läggs till i de inkluderade mapparna, som specificerats i avsnitt 3.1.5.4. |
| Limit | `37` | Anger antingen det maximala antalet samlingar som kan synkroniseras eller det högsta/minsta värdet som är tillåtet för Vänteintervallet (avsnitt 2.2.3.182) eller HeartbeatInterval-intervallet (avsnitt 2.2.3.79.2). |
| Partial | `38` | Indikerar till servern att klienten skickade en ofullständig lista över samlingar, i vilket fall servern hämtar resten av samlingarna från sin cache. |
| ConversationMode | `39` | Anger om objekt som ingår i konversationsmodaliteten ska inkluderas i resultaten av synkroniseringssvaret. |
| MaxItems | `40` | Anger det maximala antalet mottagare (det vill säga de N mest använda mottagaren) som ska hållas synkroniserade inifrån mottagarinformationscachen. |
| HeartbeatInterval | `41` | Anger antalet sekunder som servern SKA fördröja ett svar om inga nya objekt läggs till i de inkluderade mapparna, som specificerats i avsnitt 3.1.5.4. |

### Se även

* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
