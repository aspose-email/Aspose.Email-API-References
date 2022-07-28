---
title: Aspose.Email.Clients.Imap
second_title: Aspose.Email för .NET API-referens
description: Den Aspose.Email.Clients.Imap namnområdet tillhandahåller klasser för åtkomst till och manipulera meddelanden med hjälp av IMAP Internet Message Access Protocol.
type: docs
weight: 220
url: /sv/net/aspose.email.clients.imap/
---
Den **Aspose.Email.Clients.Imap** namnområdet tillhandahåller klasser för åtkomst till och manipulera meddelanden med hjälp av IMAP (Internet Message Access Protocol).

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [AppendMessagesResult](./appendmessagesresult) | Innehåller operationsresultat med meddelanden |
| [BackupSettings](./backupsettings) | Klassen innehåller alternativ för säkerhetskopiering |
| [BaseSearchConditions](./basesearchconditions) | Tillhandahåller basklass för sökvillkoren. |
| [ESearchOptions](./esearchoptions) | Resultatalternativ för ESEARCH Den här metoden fungerar endast om servern stöder tillägget ESEARCH. Snälla, läs mer https://tools.ietf.org/html/rfc4315 |
| [FetchTimeoutException](./fetchtimeoutexception) | Representerar undantaget som skapas när ett meddelande inte kan läsas inom den angivna tiden. |
| [ImapAttachmentInfo](./imapattachmentinfo) | Representerar en bilaga information. |
| [ImapAttachmentInfoCollection](./imapattachmentinfocollection) | Representerar samlingen av[`ImapAttachmentInfo`](../aspose.email.clients.imap/imapattachmentinfo) |
| [ImapClient](./imapclient) | Tillåter applikationer att komma åt och manipulera meddelanden genom att använda Internet Message Access Protocol (IMAP). |
| [ImapFolderInfo](./imapfolderinfo) | Representerar en IMAP-mapp. |
| [ImapFolderInfoCollection](./imapfolderinfocollection) | Tillhandahåller en behållare för en samling ImapFolderInfo-objekt. |
| [ImapIdentificationInfo](./imapidentificationinfo) | Representerar klassbehållare med identifieringsinformation för utbyte mellan e-postklient och server. Läs mer rfc2971 https://tools.ietf.org/html/rfc2971 |
| [ImapMailboxInfo](./imapmailboxinfo) | Innehåller en uppsättning brevlådor för specialanvändning |
| [ImapMessageFlags](./imapmessageflags) | Representerar flaggorna som är kopplade till meddelandet. |
| [ImapMessageInfo](./imapmessageinfo) | Representerar ett Imap-meddelandeobjekt. |
| [ImapMessageInfoCollection](./imapmessageinfocollection) | Tillhandahåller en behållare för en samling av[`ImapMessageInfo`](../aspose.email.clients.imap/imapmessageinfo) objekt |
| [ImapMonitoringErrorEventArgs](./imapmonitoringerroreventargs) | Klassen innehåller övervakningsfelhändelsedata. |
| [ImapMonitoringErrorEventHandler](./imapmonitoringerroreventhandler) | Representerar metoden som kommer att hantera ett imap-övervakningsfel event |
| [ImapMonitoringEventArgs](./imapmonitoringeventargs) | Klassen innehåller övervakningshändelsedata. |
| [ImapMonitoringEventHandler](./imapmonitoringeventhandler) | Representerar metoden som kommer att hantera en imap-övervakningshändelse |
| [ImapNamespace](./imapnamespace) | Representerar IMAP-namnutrymme Mer information: https://tools.ietf.org/html/rfc2342 |
| [ImapPageInfo](./imappageinfo) | Innehåller information om hämtad sida när personsökningsmetoder används. |
| [ImapQueryBuilder](./imapquerybuilder) | Representerar byggaren av sökuttryck som används av IMAP-protokollet. |
| [ImapQuota](./imapquota) | Innehåller information om kvot för postlåderesurs. |
| [ImapQuotaRoot](./imapquotaroot) | Innehåller information om kvotrot för postlåderesurs. |
| [MessageThreadResult](./messagethreadresult) | Innehåller resultat för SORT ot THREAD methods Se mer: https://tools.ietf.org/html/rfc5256 |
| [ModificationSequenceField](./modificationsequencefield) | Definierar uppsättning värden för det valda fältet att söka på. |
| [PageSettings](./pagesettings) | Inställningarna för metoden ImapClient.ListMessagesByPage |
| [PageSettingsAsync](./pagesettingsasync) | Inställningarna för asynkroniseringsmetoden ImapClient.BeginListMessagesByPage. |
| [RangeSeqSet](./rangeseqset) | Behållare med värdeintervall att söka. |
| [ReadLinesTimeoutException](./readlinestimeoutexception) | Representerar undantaget som skapas när ett svar från servern inte kan läsas inom den angivna tiden. |
| [RestoreSettings](./restoresettings) | Inställningarna för ImapClient.Restore method |
| [RestoreSettingsAsync](./restoresettingsasync) | Inställningarna för ImapClient.Restore async-metoden. |
| [SequenceSetBaseValue](./sequencesetbasevalue) | Basklass för olika behållare för värden att söka. |
| [SequenceSetField](./sequencesetfield) | Definierar uppsättning värden för det valda fältet att söka på. |
| [SimpleSeqSet](./simpleseqset) | Enkel behållare för värde att söka. |
| [SortConditions](./sortconditions) | Tillhandahåller sökvillkoren för SORT-tillägget. Kompatibel med SORT IMAP-tillägget som beskrivs på https://tools.ietf.org/html/rfc5256 |
| [ThreadSearchConditions](./threadsearchconditions) | Ger sökvillkoren för att hämta e-posttråd. Kompatibel med THREAD IMAP-tillägg som beskrivs på https://tools.ietf.org/html/rfc5256 |
| [XGMThreadSearchConditions](./xgmthreadsearchconditions) | Tillhandahåller sökvillkoren för att hämta e-posttråd. Kompatibel med X-GM-EXT-1 IMAP-tillägg som beskrivs på https://developers.google.com/gmail/imap/imap-extensions#checking_for_the_presence_of_x0000d. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IAsyncImapClient](./iasyncimapclient) | Tillåter program att komma åt och manipulera meddelanden genom att använda Internet Message Access Protocol (IMAP). |
| [IImapMonitoringState](./iimapmonitoringstate) | Håller mappövervakningstillstånd. Detta kan användas för att återuppta mappövervakning från place där det stoppades när ett fel uppstod. Använda sig av[`ResumeMonitoring`](../aspose.email.clients.imap/imapclient/resumemonitoring) metod. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [ImapCommandResult](./imapcommandresult) | Räknar upp resultaten av imap-kommandot. |
| [ImapKnownAuthenticationType](./imapknownauthenticationtype) |  |
| [ImapListFields](./imaplistfields) | Fält som kan hämtas från servern |
| [ImapNamespaceType](./imapnamespacetype) | Representerar IMAP-namnområde type Mer information: https://tools.ietf.org/html/rfc2342 |
| [ImapSpecialFolderTypes](./imapspecialfoldertypes) | Representerar en uppräkning av postlådor för specialanvändning Mer information finns i RFC6154 http://tools.ietf.org/html/rfc6154 |
| [ImapStatusCode](./imapstatuscode) | Representerar statussvaren. |
| [ListFoldersOptions](./listfoldersoptions) | Valmöjligheterna för mapplistan Observera att dessa alternativ stöds om servern stöder RFC 5258 "IMAP LIST Command Extensions" Se mer information i https://tools.ietf.org/html/rfc5258 |
| [ListFoldersReturnOptions](./listfoldersreturnoptions) | Returalternativ för ListFolders operation Observera att detta alternativ stöds om servern stöder RFC 5258 "IMAP LIST Command Extensions" Se mer information i https://tools.ietf.org/html/rfc5258 |
| [SortingKey](./sortingkey) | Sorteringskriterier för kommandot "SORT" Se mer: https://tools.ietf.org/html/rfc5256 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
