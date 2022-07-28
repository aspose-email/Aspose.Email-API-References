---
title: IAsyncEwsClient
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta linterfaccia asincrona per il client Exchange.
type: docs
weight: 3950
url: /it/net/aspose.email.clients.exchange.webservice/iasyncewsclient/
---
## IAsyncEwsClient interface

Rappresenta l'interfaccia asincrona per il client Exchange.

```csharp
public interface IAsyncEwsClient : IExchangeClientBase
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [MailboxInfo](../../aspose.email.clients.exchange.webservice/iasyncewsclient/mailboxinfo) { get; } | Ottiene le informazioni sulla casella di posta. |
| [UseSlashAsFolderSeparator](../../aspose.email.clients.exchange.webservice/iasyncewsclient/useslashasfolderseparator) { get; set; } | Ottiene o imposta un valore che determina se la barra '/' viene utilizzata come separatore di cartelle. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AppendMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/appendmessagesasync)(EwsAppendMessage) | Carica i messaggi di posta nella cartella specificata. |
| [ArchiveItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/archiveitemsasync)(EwsArchiveItems) | L'operazione ArchiveItem sposta un elemento nella cassetta postale di archivio dell'utente della cassetta postale. |
| [BackupAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/backupasync#backupasync)(ExchangeFolderInfoCollection, Stream, BackupOptions, CancellationToken) | Esegue il backup del contenuto delle cartelle specificate. |
| [BackupAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/backupasync#backupasync_1)(ExchangeFolderInfoCollection, string, BackupOptions, CancellationToken) | Esegue il backup del contenuto delle cartelle specificate. |
| [CancelAppointmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/cancelappointmentasync)(string, string, CancellationToken) | Annulla una riunione in uscita su un calendario organizzatore |
| [CopyConversationItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/copyconversationitemsasync)(string, string, string, CancellationToken) | Copia gli elementi della conversazione, che si trovano nella cartella specificata, nella cartella di destinazione specificata |
| [CopyItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/copyitemasync)(string, string, CancellationToken) | Copia l'elemento nella cartella specificata |
| [CreateAppointmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createappointmentasync)(Appointment, string, CancellationToken) | Crea appuntamento. |
| [CreateFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createfolderasync)(string, string, ExchangeFolderPermissionCollection, string, CancellationToken) | Crea la nuova cartella |
| [CreateItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createitemasync)(MapiMessageItemBase, string, CancellationToken) | Crea l'elemento specificato nella cartella specificata. |
| [CreateItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createitemsasync)(IEnumerable&lt;ExchangeStreamedItem&gt;, string, CancellationToken) | Crea gli elementi specificati nella cartella specificata |
| [CreatePublicFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createpublicfolderasync#createpublicfolderasync_1)(string, ExchangeFolderPermissionCollection, string, CancellationToken) | Crea la cartella pubblica specificata nella cartella pubblica radice |
| [CreatePublicFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createpublicfolderasync#createpublicfolderasync)(string, ExchangeFolderPermissionCollection, ExchangeFolderType, string, CancellationToken) | Crea la cartella pubblica specificata nella cartella pubblica radice |
| [CreateTaskAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createtaskasync)(ExchangeTask, string, CancellationToken) | Crea l'attività specificata nella cartella specificata. |
| [DeleteConversationItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deleteconversationitemsasync)(string, string, CancellationToken) | Elimina gli elementi della conversazione, che si trovano nella cartella specificata |
| [DeleteFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deletefolderasync)(string, bool, CancellationToken) | Elimina la cartella |
| [DeleteFoldersAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deletefoldersasync)(IEnumerable&lt;string&gt;, bool, CancellationToken) | Elimina le cartelle |
| [DeleteItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deleteitemasync)(string, DeletionOptions, CancellationToken) | Elimina l'elemento specificato |
| [DeleteItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deleteitemsasync)(IEnumerable&lt;string&gt;, DeletionOptions, CancellationToken) | Elimina gli elementi specificati |
| [EmptyFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/emptyfolderasync)(string, EmptyFolderOptions, CancellationToken) | Svuota la cartella specificata |
| [ExportItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/exportitemsasync)(IEnumerable&lt;string&gt;, CancellationToken) | Esporta gli elementi specificati dalla mailbox |
| [FetchAppointmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchappointmentasync)(string, string, CancellationToken) | Recupera l'appuntamento specificato dal server. |
| [FetchAttachmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchattachmentasync)(string, CancellationToken) | Recupera l'allegato |
| [FetchConversationMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchconversationmessagesasync)(string, CancellationToken) | Recupera i messaggi di conversazione specificati |
| [FetchItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchitemasync)(string, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Recupera l'elemento completo con allegati. |
| [FetchItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchitemsasync)(EwsFetchItems) | Recupera gli elementi specificati. |
| [FetchMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchmessagesasync)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Recupera i messaggi specificati. |
| [FetchTaskAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchtaskasync)(string, CancellationToken) | Recupera l'attività specificata. |
| [FindConversationsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/findconversationsasync)(string, CancellationToken) | Trova le conversazioni nella cartella specificata |
| [FindPeopleAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/findpeopleasync)(EwsFindPeople) | Trova contatti. |
| [FolderExistsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/folderexistsasync)(string, string, CancellationToken) | Verifica se la cartella specificata esiste. |
| [GetContactAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getcontactasync)(string, ExchangeListContactsOptions, CancellationToken) | Recupera le informazioni di contatto in base all'identificatore specificato. |
| [GetContactsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getcontactsasync)(string, ExchangeListContactsOptions, CancellationToken) | Elenca i contatti che si trovano nella cartella specificata sul server |
| [GetFolderInfoAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getfolderinfoasync)(string, CancellationToken) | Ottiene le informazioni sulla cartella |
| [GetFolderPermissionsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getfolderpermissionsasync)(string, CancellationToken) | Ottiene i permessi della cartella. |
| [GetMailboxesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getmailboxesasync)(CancellationToken) | Elenca le cassette postali con indirizzi SMTP. Nota: il numero massimo di contatti restituiti è 100. Questa è una restrizione dell'operazione EWS utilizzata. |
| [GetMailboxInfoAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getmailboxinfoasync)(string, CancellationToken) | Ottiene le informazioni sulla casella di posta |
| [GetServerTimeZoneIdsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getservertimezoneidsasync)(IEnumerable&lt;string&gt;, CancellationToken) | GetServerTimeZoneIds restituisce informazioni dall'ID fuso orario disponibili su un server Exchange. |
| [GetTimezoneIdAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/gettimezoneidasync)(CancellationToken) | Ottiene l'id del fuso orario. |
| [ListAppointmentsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listappointmentsasync)(string, MailQuery, bool, CancellationToken) | Recupera l'elenco degli appuntamenti per la cartella del calendario specificata |
| [ListAppointmentsByPageAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listappointmentsbypageasync)(string, MailQuery, int, int, CancellationToken) | Recupera la pagina con gli appuntamenti per la cartella del calendario specificata |
| [ListContactsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listcontactsasync)(string, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Elenca i contatti che si trovano nella cartella specificata sul server. |
| [ListItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listitemsasync)(string, string, MailQuery, bool, CancellationToken) | Recupera l'elenco degli URI degli elementi nella cartella specificata |
| [ListMailboxesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmailboxesasync)(string, CancellationToken) | Elenca le cassette postali con indirizzi SMTP. Nota: il numero massimo di contatti restituiti è 100. Questa è una restrizione dell'operazione EWS utilizzata. |
| [ListMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesasync#listmessagesasync)(IEnumerable&lt;string&gt;, CancellationToken) | Elenca i messaggi nella cartella specificata. |
| [ListMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesasync#listmessagesasync_1)(string, string, int, MailQuery, bool, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Elenca i messaggi nella cartella specificata. |
| [ListMessagesByPageAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesbypageasync#listmessagesbypageasync)(string, PageInfo, CancellationToken) | Elenca i messaggi nella cartella specificata. |
| [ListMessagesByPageAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesbypageasync#listmessagesbypageasync_1)(string, int, int, MailQuery, CancellationToken) | Elenca i messaggi nella cartella specificata. |
| [ListPublicFoldersAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listpublicfoldersasync)(CancellationToken) | Ottiene la raccolta di cartelle pubbliche dalla cartella pubblica principale |
| [ListSubFoldersAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listsubfoldersasync)(string, string, CancellationToken) | Ottiene la raccolta di cartelle figlie da genitore |
| [ListSubFoldersByPageAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listsubfoldersbypageasync)(string, PageInfo, CancellationToken) | Cerca la cartella specificata nella cartella principale specificata con il metodo paging supporta il paging. |
| [ListTasksAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listtasksasync)(string, int, MailQuery, bool, CancellationToken) | Recupera elenchi di attività di scambio. |
| [LoadContactPhotoAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/loadcontactphotoasync)(ContactPhoto, CancellationToken) | Carica i dati binari della foto dei contatti |
| [MailDisablePublicFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/maildisablepublicfolderasync)(string, CancellationToken) | Posta-disabilita una cartella pubblica |
| [MailEnablePublicFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/mailenablepublicfolderasync)(string, CancellationToken) | Abilitazione alla posta di una cartella pubblica |
| [MarkAllItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/markallitemsasync)(IEnumerable&lt;string&gt;, bool, bool, CancellationToken) | Contrassegna tutti gli elementi nelle cartelle specificate. |
| [MarkAsJunkAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/markasjunkasync)(IEnumerable&lt;string&gt;, bool, bool, CancellationToken) | Il metodo MarkAsJunk sposta i messaggi di posta nella cartella della posta indesiderata e blocca il mittente del messaggio. |
| [MoveConversationItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/moveconversationitemsasync)(string, string, string, CancellationToken) | Sposta gli elementi della conversazione, che si trovano nella cartella specificata, nella cartella di destinazione specificata |
| [MoveItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/moveitemasync)(string, string, CancellationToken) | Sposta l'elemento nella cartella specificata |
| [ResolveContactsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/resolvecontactsasync)(string, ExchangeListContactsOptions, CancellationToken) | Risolve indirizzi e-mail e nomi visualizzati ambigui Nota: il numero massimo di contatti restituiti è 100. Questa è una restrizione del funzionamento EWS utilizzato. |
| [ResolveMapiContactsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/resolvemapicontactsasync)(string, CancellationToken) | Risolve indirizzi e-mail e nomi visualizzati ambigui Nota: il numero massimo di contatti restituiti è 100. Questa è una restrizione del funzionamento EWS utilizzato. |
| [RestoreAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/restoreasync)(PersonalStorage, RestoreSettings, CancellationToken) | Ripristina le cartelle di scambio specificate dalla memoria personale specificata. |
| [SendAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/sendasync)(MailMessage, FollowUpOptions, CancellationToken) | Invia il messaggio. |
| [SetConversationReadStateAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/setconversationreadstateasync)(string, bool, string, CancellationToken) | Imposta lo stato di lettura degli elementi della conversazione, che si trovano nella cartella specificata, sul valore specificato |
| [SetReadFlagAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/setreadflagasync)(string, bool, CancellationToken) | Contrassegna il messaggio specificato come letto. |
| [SetTimezoneIdAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/settimezoneidasync)(string, CancellationToken) | Imposta l'id del fuso orario. |
| [SyncFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/syncfolderasync)(SyncState, CancellationToken) | Recupera le modifiche degli elementi in una cartella specificata. |
| [UpdateAppointmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updateappointmentasync)(Appointment, string, CancellationToken) | Aggiorna l'appuntamento. |
| [UpdateContactAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updatecontactasync)(Contact, CancellationToken) | Aggiorna un elemento di contatto nell'archivio di Exchange. |
| [UpdateItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updateitemasync)(EwsUpdateItem) | Aggiorna l'elemento. |
| [UpdateItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updateitemsasync)(IEnumerable&lt;ExchangeStreamedItem&gt;, CancellationToken) | Aggiorna gli elementi specificati in una casella di posta. |
| [UpdateTaskAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updatetaskasync)(ExchangeTask, CancellationToken) | Aggiorna l'attività specificata. |

### Guarda anche

* interface [IExchangeClientBase](../../aspose.email.clients.exchange/iexchangeclientbase)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
