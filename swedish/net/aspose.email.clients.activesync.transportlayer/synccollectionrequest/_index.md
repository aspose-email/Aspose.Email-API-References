---
title: SyncCollectionRequest
second_title: Aspose.Email för .NET API-referens
description: Klass innehåller kommandon och alternativ som gäller en viss samling.
type: docs
weight: 2190
url: /sv/net/aspose.email.clients.activesync.transportlayer/synccollectionrequest/
---
## SyncCollectionRequest class

Klass innehåller kommandon och alternativ som gäller en viss samling.

```csharp
public class SyncCollectionRequest
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [SyncCollectionRequest](synccollectionrequest)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/collectionid) { get; set; } | Anger server-ID för mappen som ska synkroniseras. |
| [Commands](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/commands) { get; set; } | Innehåller operationer som gäller en samling. Tillgängliga operationer är Lägg till, Ta bort, Ändra, Hämta och SoftDelete. |
| [ConversationMode](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/conversationmode) { get; set; } | Anger om objekt som ingår i konversationsmodaliteten ska inkluderas i resultaten av synkroniseringssvaret. Att ställa in ConversationMode-elementvärdet till TRUE resulterar i att alla e-postmeddelanden som matchar de mottagna konversationerna inom det angivna datumfiltret hämtas. Men även om brödtexten i e-postmeddelanden utanför det tidsbaserade filtret inte kommer att hämtas, kommer textförhandsgranskningarna att hämtas om förhandsgranskningarna begärdes. Att ställa in ConversationMode-elementvärdet till FALSE i en synkroniseringsbegäran resulterar i synkronisering av objekt som uppfyller kriterierna för FilterType-elementets värde (avsnitt 2.2.3.64). Om du ställer in ConversationMode-elementvärdet till TRUE utökas resultatuppsättningen till att även inkludera alla objekt med identiska email2:ConversationId ([MS-ASEMAIL] avsnitt 2.2.2.14)-värden som de i FilterType-resultatuppsättningen. ConversationMode-elementvärdet har ingen inverkan på objekt utanför samlingen som specificeras av CollectionId-elementet (avsnitt 2.2.3.30.5); resultatuppsättningen är alltid begränsad till objekt i den angivna samlingen. ConversationMode-elementvärdet begränsar eller utökar endast resultaten som bestäms av FilterType-elementvärdet. |
| [DeletesAsMoves](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/deletesasmoves) { get; set; } | Förfrågningar som indikerar att alla borttagna objekt SKA flyttas till mappen Deleted Items. Om DeletesAsMoves-elementet är inställt på false är borttagningen permanent. Om klienten vill ta bort objekt permanent, MÅSTE begäran innehålla elementet DeletesAsMoves med värdet FALSE. Ett värde på TRUE, som är standard, indikerar att alla borttagna objekt flyttas till mappen Deleted Items. |
| [GetChanges](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/getchanges) { get; set; } | Begär att servern i sitt svar inkluderar alla väntande ändringar av samlingen som specificeras av ServerId-elementet (avsnitt 2.2.3.151.6). Om det har skett ändringar sedan den senaste synkroniseringen, inkluderar serversvaret ett kommandoelement (avsnitt 2.2.3.32) som innehåller tillägg, raderingar och ändringar. Om klienten inte vill att serverändringarna ska returneras, MÅSTE begäran innehålla GetChanges-elementet med värdet FALSE. Ett värde på TRUE indikerar att klienten vill att serverändringarna ska returneras. Värdet TRUE antas när GetChanges-elementet är tomt. När GetChanges-elementet inte finns i begäran, beror beteendet på värdet på SyncKey-elementet, som specificerats i avsnitt 2.2.3.166.4. Om SyncKey-elementet har ett värde på 0, hanteras begäran som om GetChanges-elementet var satt till FALSE. Om SyncKey-elementet har ett värde som inte är noll, hanteras begäran som om GetChanges-elementet var satt till SANT. |
| [Options](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/options) { get; } | Anger alternativ som styr vissa aspekter av hur synkroniseringen utförs. Antal tillåtet 0...2. Synkroniseringsalternativ gör att klienten kan ange trunkerings- och innehållsinställningar. Dessa inställningar är inkapslade i ett airsyncbase:BodyPreference underordnat element, som specificerats i [MS-ASAIRS] avsnitt 2.2.2.7. Eftersom synkroniseringsalternativ är specificerade på en samling, kan klienten ange ett unikt airsyncbase:BodyPreference-elementvärde för varje samling som den synkroniseras. För mer information om airsyncbase:BodyPreference-elementet, se [MS-ASAIRS] avsnitt 2.2. 2.7. Servern bevarar Options-blocket över förfrågningar, med hjälp av ett koncept som kallas "sticky options". Om Options-blocket inte ingår i en begäran, används det föregående Options-blocket. Närhelst klienten anger nya alternativ genom att inkludera ett Options-block i begäran, MÅSTE servern ersätta det ursprungliga Options-blocket med det nya Options-blocket. Om två Options-element ingår i en enda Sync-kommandobegäran, MÅSTE ett av Options-elementen ange synkroniseringsalternativen för SMS-klassen, medan det andra Options-elementet anger alternativen för standardklassen för den givna mappen. |
| [Supported](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/supported) { get; } | Element i klassen Contact och Calendar som inte är spökbildade kan inkluderas som underordnade element till elementet som stöds. För detaljer om användningen av spökegenskaper, se avsnitt 2.2.3.154. |
| [SyncKey](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/synckey) { get; set; } | SyncKey-värdet används av servern för att markera synkroniseringstillståndet för en samling. En synkroniseringsnyckel med värdet 0 (noll) initierar synkroniseringstillståndet på servern och orsakar en fullständig synkronisering av samlingen. |
| [WindowSize](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/windowsize) { get; set; } | Anger ett maximalt antal ändrade objekt i en samling eller en begäran som SKA inkluderas i synkroniseringssvaret. Om WindowSize inte är definierad, beter sig servern som om ett WindowSize-element med värdet 100 skickades. Servern tolkar värdet 0 (noll) och värden över 512 som 512. |

### Se även

* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
