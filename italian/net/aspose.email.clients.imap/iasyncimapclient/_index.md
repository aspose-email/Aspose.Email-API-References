---
title: IAsyncImapClient
second_title: Aspose.Email per riferimento all'API .NET
description: Consente alle applicazioni di accedere e manipolare messaggi utilizzando lInternet Message Access Protocol IMAP.
type: docs
weight: 16240
url: /it/net/aspose.email.clients.imap/iasyncimapclient/
---
## IAsyncImapClient interface

Consente alle applicazioni di accedere e manipolare messaggi utilizzando l'Internet Message Access Protocol (IMAP).

```csharp
public interface IAsyncImapClient
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/addmessageflagsasync)(ImapChangeMessageFlags) | Aggiunge i flag al messaggio |
| [AppendMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/appendmessageasync)(MailMessage, string, IConnection, CancellationToken) | Carica il messaggio di posta nella cartella specificata |
| [AppendMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/appendmessagesasync)(IEnumerable&lt;MailMessage&gt;, string, IConnection, CancellationToken) | Carica i messaggi di posta nella cartella corrente |
| [BackupAsync](../../aspose.email.clients.imap/iasyncimapclient/backupasync#backupasync)(ImapFolderInfoCollection, Stream, BackupSettings, IConnection, CancellationToken) | Esegue il backup del contenuto delle cartelle specificate |
| [BackupAsync](../../aspose.email.clients.imap/iasyncimapclient/backupasync#backupasync_1)(ImapFolderInfoCollection, string, BackupSettings, IConnection, CancellationToken) | Esegue il backup del contenuto delle cartelle specificate |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/changemessageflagsasync)(ImapChangeMessageFlags) | Modifica i flag del messaggio |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/iasyncimapclient/clientcapabilitiesasync)(IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Notifica al server quali estensioni sono supportate dal client. Nota, questa operazione funziona solo nel caso in cui il server supporti RFC5161 Vedi di più https://tools.ietf.org/html/rfc5161 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/iasyncimapclient/commitdeletesasync)(ImapUniqueIdParameterSet) | Conferma le eliminazioni |
| [CopyMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessageasync#copymessageasync)(int, string, IConnection, CancellationToken) | Copia il messaggio |
| [CopyMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessageasync#copymessageasync_1)(string, string, IConnection, CancellationToken) | Copia il messaggio. |
| [CopyMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessagesasync)(ImapCopyMessages) | Copia i messaggi. |
| [CreateFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/createfolderasync)(string, IConnection, CancellationToken) | Crea una cartella con il nome specificato. |
| [DeleteFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/deletefolderasync)(string, IConnection, CancellationToken) | Elimina una cartella specificata. Questo metodo rappresenta il comando IMAP DELETE. |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/deletemessagesasync)(ImapDeleteMessages) | Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |
| [ExistFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/existfolderasync)(string, IConnection, CancellationToken) | Verifica se questa cartella esiste |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/iasyncimapclient/fetchattachmentasync)(int, string, IConnection, CancellationToken) | Recupera l'allegato specificato. |
| [FetchMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/fetchmessagesasync)(ImapFetchMessages) | Recupera i messaggi in modo asincrono |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/iasyncimapclient/getfolderinfoasync)(string, IConnection, CancellationToken) | Restituisce informazioni sulla cartella specificata senza selezionarla |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/iasyncimapclient/getmessagethreadsasync)(BaseSearchConditions, IConnection, CancellationToken) | Ottieni thread di messaggi. |
| [GetNamespacesAsync](../../aspose.email.clients.imap/iasyncimapclient/getnamespacesasync)(IConnection, CancellationToken) | Ottiene gli spazi dei nomi disponibili su un server. |
| [GetQuotaAsync](../../aspose.email.clients.imap/iasyncimapclient/getquotaasync)(string, IConnection, CancellationToken) | Ottiene informazioni sulla quota |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/iasyncimapclient/getquotarootasync)(string, IConnection, CancellationToken) | Ottiene le informazioni sulla radice della quota per la casella di posta |
| [IntroduceClientAsync](../../aspose.email.clients.imap/iasyncimapclient/introduceclientasync)(ImapIdentificationInfo, IConnection, CancellationToken) | Introduce le informazioni sul client a un server. |
| [ListFoldersAsync](../../aspose.email.clients.imap/iasyncimapclient/listfoldersasync)(string, bool, ListFoldersOptions, ListFoldersReturnOptions, IConnection, CancellationToken) | Ottiene l'elenco delle sottocartelle nella cartella specificata |
| [ListMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessageasync#listmessageasync)(int, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Ottiene informazioni su un messaggio. |
| [ListMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessageasync#listmessageasync_1)(string, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Ottiene informazioni su un messaggio. |
| [ListMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesasync#listmessagesasync)(MailQuery, string, int, IConnection, CancellationToken) | Ottiene l'elenco dei messaggi nella cartella corrente. |
| [ListMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesasync#listmessagesasync_1)(string, long, bool, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Ottiene l'elenco dei messaggi nella cartella specificata |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesbypageasync#listmessagesbypageasync_1)(int, int, PageSettings, CancellationToken) | Ottiene l'elenco dei messaggi |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesbypageasync#listmessagesbypageasync)(MailQuery, PageInfo, PageSettings, CancellationToken) | Ottiene l'elenco dei messaggi |
| [MoveFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/movefolderasync)(string, string, IConnection, CancellationToken) | Sposta la cartella specificata e le relative sottocartelle nella nuova posizione. |
| [MoveMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/movemessagesasync)(ImapMoveMessages) | Sposta i messaggi. |
| [NoopAsync](../../aspose.email.clients.imap/iasyncimapclient/noopasync)(IConnection, CancellationToken) | Comando 'Nessuna operazione' |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/removemessageflagsasync)(ImapChangeMessageFlags) | Rimuove i flag del messaggio |
| [RenameFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/renamefolderasync)(string, string, IConnection, CancellationToken) | Rinomina una cartella specificata con un nuovo nome |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/iasyncimapclient/requestcheckpointasync)(IConnection, CancellationToken) | Richiede un checkpoint della casella di posta attualmente selezionata. |
| [RestoreAsync](../../aspose.email.clients.imap/iasyncimapclient/restoreasync)(PersonalStorage, RestoreSettings, CancellationToken) | Inizia a ripristinare le cartelle imap dalla memoria personale specificata. |
| [ResumeMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/resumemonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, IImapMonitoringState, CancellationToken) | Riprende il monitoraggio delle modifiche ai messaggi per la cartella specificata. A differenza del metodo StartMonitoring, troverà tutte le modifiche alla casella di posta mancanti e chiamerà la richiamata per esse. |
| [SelectFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/selectfolderasync)(string, bool?, IConnection, CancellationToken) | Seleziona la cartella specificata |
| [SetQuotaAsync](../../aspose.email.clients.imap/iasyncimapclient/setquotaasync)(string, string, int, IConnection, CancellationToken) | Imposta le informazioni sulla quota |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/iasyncimapclient/sortmessagethreadsasync)(SortConditions, IConnection, CancellationToken) | Ordina i thread dei messaggi. |
| [StartMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/startmonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, string) | Avvia il monitoraggio delle modifiche ai messaggi per la cartella specificata. |
| [StopMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/stopmonitoringasync)(string, CancellationToken) | Arresta il monitoraggio delle modifiche ai messaggi per la cartella specificata. Interrompe il monitoraggio di tutte le cartelle se folderName è null. |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/subscribefolderasync)(string, IConnection, CancellationToken) | Inviato il comando SUBSCRIBE che aggiunge il nome della casella di posta specificato al set di caselle di posta "attive" del server. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/undeletemessageasync#undeletemessageasync)(int, long, IConnection, CancellationToken) | Contrassegna un messaggio con il numero di sequenza specificato come non eliminato |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/undeletemessageasync#undeletemessageasync_1)(string, long, IConnection, CancellationToken) | Contrassegna un messaggio con il numero di sequenza specificato come non eliminato. |
| [UnselectFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/unselectfolderasync)(bool, IConnection, CancellationToken) | Deseleziona la cartella attualmente selezionata. se la proprietà doNotExpunge è vera, tutti i messaggi sono contrassegnati come eliminati vengono rimossi, altrimenti l'eliminazione viene annullata. Nota, questa operazione funziona solo nel caso in cui il server supporti RFC3691 Vedi altro https://tools. ietf.org/html/rfc3691 |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/unsubscribefolderasync)(string, IConnection, CancellationToken) | Inviato il comando UNSUBSCRIBE che rimuove il nome della cassetta postale specificato dal set di cassette postali "attive" del server |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/iasyncimapclient/validatecredentialsasync)(IConnection, CancellationToken) | Esegue la convalida delle credenziali |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
