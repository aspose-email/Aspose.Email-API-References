---
title: IAsyncImapClient
second_title: Aspose.Email för .NET API-referens
description: Tillåter program att komma åt och manipulera meddelanden genom att använda Internet Message Access Protocol IMAP.
type: docs
weight: 16240
url: /sv/net/aspose.email.clients.imap/iasyncimapclient/
---
## IAsyncImapClient interface

Tillåter program att komma åt och manipulera meddelanden genom att använda Internet Message Access Protocol (IMAP).

```csharp
public interface IAsyncImapClient
```

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/addmessageflagsasync)(ImapChangeMessageFlags) | Lägger till flaggorna i meddelandet |
| [AppendMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/appendmessageasync)(MailMessage, string, IConnection, CancellationToken) | Laddar upp e-postmeddelandet till den angivna mappen |
| [AppendMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/appendmessagesasync)(IEnumerable&lt;MailMessage&gt;, string, IConnection, CancellationToken) | Laddar upp e-postmeddelanden till den aktuella mappen |
| [BackupAsync](../../aspose.email.clients.imap/iasyncimapclient/backupasync#backupasync)(ImapFolderInfoCollection, Stream, BackupSettings, IConnection, CancellationToken) | Säkerhetskopierar innehållet i de angivna mapparna |
| [BackupAsync](../../aspose.email.clients.imap/iasyncimapclient/backupasync#backupasync_1)(ImapFolderInfoCollection, string, BackupSettings, IConnection, CancellationToken) | Säkerhetskopierar innehållet i de angivna mapparna |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/changemessageflagsasync)(ImapChangeMessageFlags) | Ändrar flaggorna för meddelandet |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/iasyncimapclient/clientcapabilitiesasync)(IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Meddelar servern vilka tillägg som stöds av klienten. Observera att denna operation endast fungerar om servern stöder RFC5161 Se mer https://tools.ietf.org/html/rfc5161 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/iasyncimapclient/commitdeletesasync)(ImapUniqueIdParameterSet) | Begå raderingarna |
| [CopyMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessageasync#copymessageasync)(int, string, IConnection, CancellationToken) | Kopierar meddelandet |
| [CopyMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessageasync#copymessageasync_1)(string, string, IConnection, CancellationToken) | Kopierar meddelandet. |
| [CopyMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessagesasync)(ImapCopyMessages) | Kopiera meddelandena. |
| [CreateFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/createfolderasync)(string, IConnection, CancellationToken) | Skapar en mapp med det angivna namnet. |
| [DeleteFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/deletefolderasync)(string, IConnection, CancellationToken) | Tar bort en angiven mapp. Denna metod representerar kommandot IMAP DELETE. |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/deletemessagesasync)(ImapDeleteMessages) | Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315 |
| [ExistFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/existfolderasync)(string, IConnection, CancellationToken) | Kontrollera om den här mappen existerar |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/iasyncimapclient/fetchattachmentasync)(int, string, IConnection, CancellationToken) | Hämtar den angivna bilagan. |
| [FetchMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/fetchmessagesasync)(ImapFetchMessages) | Hämtar meddelandena asynkront |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/iasyncimapclient/getfolderinfoasync)(string, IConnection, CancellationToken) | Returnerar information om den angivna mappen utan att välja it |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/iasyncimapclient/getmessagethreadsasync)(BaseSearchConditions, IConnection, CancellationToken) | Få meddelandetrådar. |
| [GetNamespacesAsync](../../aspose.email.clients.imap/iasyncimapclient/getnamespacesasync)(IConnection, CancellationToken) | Får namnutrymmen som är tillgängliga på en server. |
| [GetQuotaAsync](../../aspose.email.clients.imap/iasyncimapclient/getquotaasync)(string, IConnection, CancellationToken) | Får kvotinformation |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/iasyncimapclient/getquotarootasync)(string, IConnection, CancellationToken) | Hämtar kvotrotinformation för mailbox |
| [IntroduceClientAsync](../../aspose.email.clients.imap/iasyncimapclient/introduceclientasync)(ImapIdentificationInfo, IConnection, CancellationToken) | Introducerar klientinformation till en server. |
| [ListFoldersAsync](../../aspose.email.clients.imap/iasyncimapclient/listfoldersasync)(string, bool, ListFoldersOptions, ListFoldersReturnOptions, IConnection, CancellationToken) | Hämtar listan över undermappar i den angivna mappen |
| [ListMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessageasync#listmessageasync)(int, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Får information om ett meddelande. |
| [ListMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessageasync#listmessageasync_1)(string, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Får information om ett meddelande. |
| [ListMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesasync#listmessagesasync)(MailQuery, string, int, IConnection, CancellationToken) | Hämtar listan över meddelanden i den aktuella mappen. |
| [ListMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesasync#listmessagesasync_1)(string, long, bool, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Hämtar listan över meddelanden i den angivna mappen |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesbypageasync#listmessagesbypageasync_1)(int, int, PageSettings, CancellationToken) | Hämtar listan med meddelanden |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesbypageasync#listmessagesbypageasync)(MailQuery, PageInfo, PageSettings, CancellationToken) | Hämtar listan med meddelanden |
| [MoveFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/movefolderasync)(string, string, IConnection, CancellationToken) | Flyttar angiven mapp och dess undermappar till en ny plats. |
| [MoveMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/movemessagesasync)(ImapMoveMessages) | Flyttar meddelandena. |
| [NoopAsync](../../aspose.email.clients.imap/iasyncimapclient/noopasync)(IConnection, CancellationToken) | 'Ingen operation' kommando |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/removemessageflagsasync)(ImapChangeMessageFlags) | Tar bort flaggorna för meddelandet |
| [RenameFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/renamefolderasync)(string, string, IConnection, CancellationToken) | Byter namn på en angiven mapp till ett nytt namn |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/iasyncimapclient/requestcheckpointasync)(IConnection, CancellationToken) | Begär en kontrollpunkt för den för närvarande valda postlådan. |
| [RestoreAsync](../../aspose.email.clients.imap/iasyncimapclient/restoreasync)(PersonalStorage, RestoreSettings, CancellationToken) | Börjar återställa imap-mappar från den givna personliga lagringen. |
| [ResumeMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/resumemonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, IImapMonitoringState, CancellationToken) | Återupptar övervakning av meddelandeändringar för angiven mapp. Till skillnad från StartMonitoring-metoden kommer den att hitta alla saknade brevlådeändringar och ringa återuppringningen för dem. |
| [SelectFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/selectfolderasync)(string, bool?, IConnection, CancellationToken) | Väljer den angivna mappen |
| [SetQuotaAsync](../../aspose.email.clients.imap/iasyncimapclient/setquotaasync)(string, string, int, IConnection, CancellationToken) | Anger kvotinformation |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/iasyncimapclient/sortmessagethreadsasync)(SortConditions, IConnection, CancellationToken) | Sortera meddelandetrådar. |
| [StartMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/startmonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, string) | Startar övervakning av meddelandeändringar för angiven mapp. |
| [StopMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/stopmonitoringasync)(string, CancellationToken) | Stoppar övervakning av meddelandeändringar för angiven mapp. Stoppar övervakning av alla mappar om folderName är null. |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/subscribefolderasync)(string, IConnection, CancellationToken) | Skickade kommandot SUBSCRIBE som lägger till det angivna brevlådenamnet till serverns uppsättning "aktiva" brevlådor. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/undeletemessageasync#undeletemessageasync)(int, long, IConnection, CancellationToken) | Markerar ett meddelande med det angivna sekvensnumret som inte raderat |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/undeletemessageasync#undeletemessageasync_1)(string, long, IConnection, CancellationToken) | Markerar ett meddelande med det angivna sekvensnumret som inte raderat. |
| [UnselectFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/unselectfolderasync)(bool, IConnection, CancellationToken) | Avmarkerar mappar som för närvarande är valda. om doNotExpunge-egenskapen är true, alla meddelanden är markerade som borttagna tas bort, annars avbryts raderingen. Observera att den här operationen endast fungerar om servern stöder RFC3691 Se mer https://tools. ietf.org/html/rfc3691 |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/unsubscribefolderasync)(string, IConnection, CancellationToken) | Skickade kommandot UNSUBSCRIBE som tar bort det angivna brevlådenamnet från serverns uppsättning "aktiva" brevlådor |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/iasyncimapclient/validatecredentialsasync)(IConnection, CancellationToken) | Utför behörighetsvalidering |

### Se även

* namnutrymme [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
