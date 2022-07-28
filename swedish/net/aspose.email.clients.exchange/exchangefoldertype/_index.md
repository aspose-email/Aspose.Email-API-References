---
title: ExchangeFolderType
second_title: Aspose.Email för .NET API-referens
description: Räknar upp de olika mapptyperna. Dessa värden finns också i egenskapen PidTagContainerClass.
type: docs
weight: 3340
url: /sv/net/aspose.email.clients.exchange/exchangefoldertype/
---
## ExchangeFolderType enumeration

Räknar upp de olika mapptyperna. Dessa värden finns också i egenskapen PidTagContainerClass.

```csharp
public enum ExchangeFolderType
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Undefined | `0` | Mapptyp är inte inställd. Värdet används med följande välkända mappar: Root - Message Store hierarkins översta mapp, som innehåller alla andra mappobjekt i det meddelandelagret. Finder - Innehåller standardsökmappar. FreeBusy-data - Innehåller ledig/upptagen-data för brevlådans ägare. Överst i personliga mappar - Den översta mappen i den mellanpersonliga meddelandehierarkin, som innehåller användardatamappar, inklusive de flesta specialmappar som inkorgen. Vanliga vyer - Innehåller data för standardvyer som är standard för meddelandelagret och som kan användas av alla användare av en klient som kommer åt meddelandelagret. Personliga vyer - Innehåller data för vyer definierade av en viss användare. Uppskjuten åtgärd - Innehåller eventuella uppskjutna vyer Action Message (DAM) eller Deferred Error Message (DEM) som är resultatet av exekvering av regler på klientsidan. |
| Note | `1` | Detta värde representerar e-postmeddelandemapptypen ("IPF.Note"). Värdet används med följande välkända mappar: Borttagna objekt - Standardplatsen för objekt som har tagits bort. Utkorg - Utgående e-post Meddelandeobjekt placeras i den här mappen när meddelandeobjektet skickas. Skickade objekt - Standardplatsen där kopior av e-postmeddelandeobjekt placeras efter att de har skickats (skickats). Inkorg - Standardplatsen för inkommande ( mottagna) e-post Meddelandeobjekt. Utkast - Standardplatsen för sammansatt e-post Meddelandeobjekt som har sparats men inte skickats. Skräppost - Standardplats för e-post Meddelandeobjekt som fastställts vara skräppost av en skräppostregel. Synkroniseringsproblem - Innehåller mappar som innehåller meddelanden som indikerar särskilda problem som uppstår under synkronisering mellan klient och server. Detta är den överordnade mappen för mapparna Konflikter, Lokala fel och Serverfel. Konflikter - Innehåller meddelandeobjekt som indikerar synkroniseringskonflikter mellan klient och server. Lokala fel - Innehåller meddelanden som indikerar synkroniseringsfel på klientsidan_x00 på klientsidan. - Innehåller meddelanden som indikerar synkroniseringsfel på serversidan. Tracked Mail Processing - Sökmapp som innehåller flaggade objekt. Spooler Queue - Innehåller e-postobjekt som har skickats eller tagits emot. |
| RSSFeeds | `2` | Detta värde representerar mapptypen RSS-meddelande ("IPF.Note.OutlookHomepage"). Värdet används med följande välkända mappar: RSS-flöden - Innehåller RSS-flödesmeddelanden (Really Simple Syndication). |
| Appointment | `3` | Det här värdet representerar mapptypen "bokning" ("IPF.Appointment"). Värdet används med följande välkända mappar: Kalender - Innehåller kalenderobjekt, såsom möten. |
| Contact | `4` | Detta värde representerar mapptypen "kontakter" ("IPF.Contact"). Värdet används med följande välkända mappar: Kontakter - Innehåller kontaktobjekt. Föreslagna kontakter - Innehåller kontaktobjekt som skapas när en mottagare inte är det i en adressbok. Kontaktsökning - Sökmapp som visar en lista över kontakter som uppfyller sökkriterierna. |
| QuickContacts | `5` | Detta värde representerar mapptypen för favoritkontakter ("IPF.Contact.MOC.QuickContacts"). Värdet används med följande välkända mappar: Snabbkontakter - Innehåller kontaktobjekt för användarens favoritkontakter och snabbmeddelandekontakter. |
| ImContactsList | `6` | Det här värdet representerar mapptypen för snabbmeddelandekontakter ("IPF.Contact.MOC.ImContactList"). Värde används med följande välkända mappar: IM Contacts List - Innehåller personlig distributionslista-objekt för favoritkontakter och snabbmeddelandekontakter . |
| DocumentLibraries | `7` | Detta värde representerar mapptypen 'dokument' ("IPF.ShortcutFolder"). Värdet används med följande välkända mappar: Dokumentbibliotek - Innehåller dokument som ska laddas upp till en delad plats. |
| Journal | `8` | Detta värde representerar mapptypen 'Journal' ("IPF.Journal"). Värdet används med följande välkända mappar: Journal - Innehåller journalobjekt. |
| StickyNote | `9` | Detta värde representerar mapptypen 'notes' ("IPF.StickyNote"). Värdet används med följande välkända mappar: Notes - Innehåller Note-objekt. |
| Task | `10` | Det här värdet representerar mapptypen "Task" ("IPF.Task"). Värdet används med följande välkända mappar: Att göra - Sökmapp som används för att spåra aktivitetsobjekt. Uppgifter - Innehåller uppgiftsobjekt. |
| Imap | `11` | Det här värdet representerar mapptypen 'imap' ("IPF.IMAP"). Används för att migrera från IMAP-profilen till Exchange. |
| Unknown | `12` | Mapptypen är okänd. |

### Se även

* namnutrymme [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
