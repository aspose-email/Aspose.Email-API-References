---
title: SearchOptions
second_title: Aspose.Email för .NET API-referens
description: Innehåller sökalternativen. Användarnamnet och lösenordet kan endast skickas i begäran efter att ha mottagit ett statusvärde på 14. Servern kräver dessa uppgifter för att komma åt de begärda resurserna. Klienten MÅSTE bara skicka dessa över en säker eller pålitlig anslutning och endast som svar på ett statusvärde på 14. De alternativ som stöds varierar beroende på butiken som söks. Följande tabell listar de giltiga alternativen för varje butik. GAL Range UserName Password Picture Mailbox Range DeepTraversal RebuildResults BodyPreference BodyPartPreference RightsManagementSupport Endast användarnamn 0 DocumentLibrary BodyPreference är giltigt i _0 kommandobegäranden som inkluderar ett ConversationId.
type: docs
weight: 1950
url: /sv/net/aspose.email.clients.activesync.transportlayer/searchoptions/
---
## SearchOptions class

Innehåller sökalternativen. Användarnamnet och lösenordet kan endast skickas i begäran efter att ha mottagit ett statusvärde på 14. Servern kräver dessa uppgifter för att komma åt de begärda resurserna. Klienten MÅSTE bara skicka dessa över en säker eller pålitlig anslutning, och endast som svar på ett statusvärde på 14. De alternativ som stöds varierar beroende på butiken som söks. Följande tabell listar de giltiga alternativen för varje butik. GAL: Range, UserName, Password, Picture Mailbox: Range, DeepTraversal, RebuildResults, BodyPreference, BodyPartPreference, RightsManagementSupport Endast användarnamn 0, DocumentLibrary: BodyPreference är giltigt i _0 kommandobegäranden som inkluderar ett ConversationId.

```csharp
public class SearchOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [SearchOptions](searchoptions)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BodyPartPreference](../../aspose.email.clients.activesync.transportlayer/searchoptions/bodypartpreference) { get; } | Innehåller preferensinformation relaterad till typen och storleken på information som returneras från sökning, synkronisering eller hämtning av en meddelandedel. |
| [BodyPreference](../../aspose.email.clients.activesync.transportlayer/searchoptions/bodypreference) { get; } | Innehåller preferensinformation relaterad till typen och storleken på information som returneras från sökning, synkronisering eller hämtning. |
| [DeepTraversal](../../aspose.email.clients.activesync.transportlayer/searchoptions/deeptraversal) { get; set; } | Indikerar att klienten vill att servern ska söka i alla undermappar efter de mappar som anges i frågan. |
| [MIMESupport](../../aspose.email.clients.activesync.transportlayer/searchoptions/mimesupport) { get; set; } | Aktiverar MIME-stöd för e-postobjekt som skickas från servern till klienten. Om elementet airsync:MIMESupport är inställt på 'SendForSecureMIMEonly' (1) eller 'SendForAll' (2) i sökförfrågan: - egenskapen för airsyncbase:BodyPreference, typen, SKA inkluderas i sökförfrågan, som innehåller värdet 'MIME' (4) för att informera servern om att enheten kan läsa MIME BLOB. - Svaret från servern MÅSTE inkludera airsyncbase:Body, som är ett underordnat av egenskaperna. Airsyncbase:Body MÅSTE innehålla följande egenskaper i ett S/MIME-söksvar: - Airsyncbase:Type med värdet 'MIME' (4) för att informera enheten om att data är en MIME BLOB. - Airsyncbase :EstimatedDataSize för att ange den grova totala storleken på data. - Airsyncbase:Truncated för att indikera om MIME BLOB är trunkerad. - Airsyncbase:Data som innehåller hela MIME BLOB. |
| [Password](../../aspose.email.clients.activesync.transportlayer/searchoptions/password) { get; set; } | Anger lösenordet för det angivna användarnamnet. Värdet på lösenordet har en maximal längd på 100 tecken. |
| [Picture](../../aspose.email.clients.activesync.transportlayer/searchoptions/picture) { get; set; } | Innehåller data relaterade till fotobegäran. Bilden stöds inte när protokollversionen är 12.1 eller 14.0. |
| [Range](../../aspose.email.clients.activesync.transportlayer/searchoptions/range) { get; set; } | Anger det maximala antalet matchande poster som ska returneras. Formatet för Range-elementvärdet är i form av en nollbaserad indexspecifikator, bildad med en nolla, ett bindestreck och ett annat numeriskt värde: "mn." M anger det lägsta indexet för en nollbaserad array som skulle innehålla objekten. n anger det högsta indexet för en nollbaserad array som skulle innehålla objekten. Till exempel anger ett områdeselementvärde på 0–9 10 objekt och 0–10 anger 11 objekt. Ett områdeselementvärde på 0–0 indikerar 1 objekt. Om Range är null används standardvärdet för Range för varje Store-typ. Följande tabell identifierar standardintervallsvärdena och maximala resultat som returneras för varje butikstyp: Mailbox - Standardintervallsvärde: 0-99 - Maximalt returnerat resultat: 100 Default ranged : 1000 GAL - Standardintervallvärde: 0-99 - Maximalt returnerade resultat: 100 Om intervallvärdet som angetts i begäran överskrider standardintervallvärdet, indikerar ett statusavkastningsvärde på . I sökkommandosvaret anger egenskapen Total en uppskattning av det totala antalet poster som matchade frågevärdet. Sökresultat lagras i en sökmapp på servern. På detta sätt, när en klient kommer tillbaka med samma fråga men ett nytt radintervall, dras rader från resultatuppsättningen som för närvarande är lagrad i sökmappen. Hela resultatuppsättningen behöver inte byggas om. |
| [RebuildResults](../../aspose.email.clients.activesync.transportlayer/searchoptions/rebuildresults) { get; set; } | Tvingar servern att bygga om sökmappen (2) som motsvarar en given fråga. Sökresultaten (det vill säga resultatuppsättningen) lagras i en sökmapp på servern. På detta sätt, när en klient kommer tillbaka med samma fråga men ett nytt radintervall, dras rader från resultatuppsättningen som för närvarande är lagrad i sökmappen. Hela resultatuppsättningen behöver inte byggas om. Sökmappen förblir oförändrad tills klienten gör något av följande för att uppdatera resultatuppsättningen: - Skickar en sökförfrågan, anger en ny fråga. I det här fallet byggs sökmappen automatiskt om. RebuildResults-noden behöver inte inkluderas. - Skickar en sökförfrågan som inkluderar RebuildResults-noden. I det här fallet tvingas servern bygga om sökmappen. Om ett nytt objekt läggs till visas inte objektet i resultatuppsättningen förrän resultatuppsättningen uppdateras. Om ett objekt tas bort kommer servern att filtrera bort det borttagna objektet från resultatuppsättningen. Klienten SKA skicka en ny sökförfrågan med den givna frågan och inkludera alternativet RebuildResults med några dagars mellanrum för att säkerställa korrekta resultat för den frågan. |
| [RightsManagementSupport](../../aspose.email.clients.activesync.transportlayer/searchoptions/rightsmanagementsupport) { get; set; } | Anger hur servern returnerar rättighetshanterade e-postmeddelanden till klienten. Om värdet är TRUE kommer servern att dekomprimera och dekryptera rättighetshanterade e-postmeddelanden innan de skickas till klienten. Om värdet är FALSE kommer servern inte att dekomprimera eller dekryptera rättighetshanterade e-postmeddelanden innan de skickas till klienten. Om RightsManagementSupport-elementet inte ingår i ett begärandemeddelande, antas standardvärdet FALSE. |
| [UserName](../../aspose.email.clients.activesync.transportlayer/searchoptions/username) { get; set; } | Anger användarkontot som används för att söka i dokumentet från dokumentbiblioteket. Användarnamnsvärdet kan vara upp till 100 tecken långt. |

### Se även

* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
