---
title: IEWSClient
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta linterfaccia per il client Exchange.
type: docs
weight: 3960
url: /it/net/aspose.email.clients.exchange.webservice/iewsclient/
---
## IEWSClient interface

Rappresenta l'interfaccia per il client Exchange.

```csharp
public interface IEWSClient : IExchangeClientBase
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CalendarFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/calendarfoldereventfilter) { get; set; } | Specifica i tipi di eventi per la cartella Calendario |
| [ContactsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/contactsfoldereventfilter) { get; set; } | Specifica i tipi di eventi per la cartella Contatti |
| [CurrentCalendarFolderUri](../../aspose.email.clients.exchange.webservice/iewsclient/currentcalendarfolderuri) { get; set; } | Ottiene o imposta la cartella del calendario corrente uri |
| [DeletedItemsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/deleteditemsfoldereventfilter) { get; set; } | Specifica i tipi di evento per la cartella DeletedItems |
| [DraftsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/draftsfoldereventfilter) { get; set; } | Specifica i tipi di eventi per la cartella Bozze |
| [EnableDecompression](../../aspose.email.clients.exchange.webservice/iewsclient/enabledecompression) { get; set; } | Ottiene o imposta un valore che indica se la decompressione è abilitata |
| [Headers](../../aspose.email.clients.exchange.webservice/iewsclient/headers) { get; } | Ottiene l'array di coppie nome valore che vengono aggiunte a WebHeaderCollection nella richiesta EWS. |
| [InboxFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/inboxfoldereventfilter) { get; set; } | Specifica i tipi di eventi per la cartella Posta in arrivo |
| [JournalFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/journalfoldereventfilter) { get; set; } | Specifica i tipi di eventi per la cartella Journal |
| [MailboxInfo](../../aspose.email.clients.exchange.webservice/iewsclient/mailboxinfo) { get; } | Ottiene le informazioni sulla casella di posta. |
| [NotesFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/notesfoldereventfilter) { get; set; } | Specifica i tipi di eventi per la cartella Notes |
| [NotificationsCheckInterval](../../aspose.email.clients.exchange.webservice/iewsclient/notificationscheckinterval) { get; set; } | Definisce l'intervallo per il controllo delle notifiche |
| [NotificationTimeout](../../aspose.email.clients.exchange.webservice/iewsclient/notificationtimeout) { get; set; } | Definisce il timeout per le notifiche del server |
| [OutboxFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/outboxfoldereventfilter) { get; set; } | Specifica i tipi di evento per la cartella Posta in uscita |
| [ReconnectCount](../../aspose.email.clients.exchange.webservice/iewsclient/reconnectcount) { get; set; } | Ottiene o imposta il numero di tentativi di riconnessione alle interruzioni di connessione. |
| [ReturnClientRequestId](../../aspose.email.clients.exchange.webservice/iewsclient/returnclientrequestid) { get; set; } | Ottiene o imposta un flag per indicare se il client richiede che il lato server restituisca l'id della richiesta. |
| [RootFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/rootfoldereventfilter) { get; set; } | Specifica i tipi di evento per la cartella principale |
| [SentItemsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/sentitemsfoldereventfilter) { get; set; } | Specifica i tipi di eventi per la cartella SentItems |
| [ServerVersion](../../aspose.email.clients.exchange.webservice/iewsclient/serverversion) { get; } | Ottiene le informazioni sulla versione corrente di MS Exchange. |
| [TasksFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/tasksfoldereventfilter) { get; set; } | Specifica i tipi di eventi per la cartella Attività |
| [TimezoneId](../../aspose.email.clients.exchange.webservice/iewsclient/timezoneid) { get; set; } | Ottiene o imposta l'id del fuso orario |
| [UseSlashAsFolderSeparator](../../aspose.email.clients.exchange.webservice/iewsclient/useslashasfolderseparator) { get; set; } | Ottiene o imposta un valore che determina se la barra '/' viene utilizzata come separatore di cartelle. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddHeader](../../aspose.email.clients.exchange.webservice/iewsclient/addheader)(string, string) | Aggiunge nome e valore a WebHeaderCollection nella richiesta EWS. |
| [AddToDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/addtodistributionlist)(ExchangeDistributionList, MailAddressCollection) | Aggiunge i membri alla lista di distribuzione. |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage)(MailMessage) | Carica il messaggio di posta nella cartella Posta in arrivo |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_1)(MapiMessage) | Carica il messaggio di posta nella cartella specificata |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_2)(MapiMessage, bool) | Carica il messaggio di posta nella cartella specificata |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_3)(string, MailMessage) | Carica il messaggio di posta nella cartella specificata |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_5)(string, MapiMessage, bool) | Carica il messaggio di posta nella cartella specificata |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_1)(IEnumerable&lt;MailMessage&gt;) | Carica il messaggio di posta nella cartella specificata |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages)(params MailMessage[]) | Carica il messaggio di posta nella cartella specificata |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_3)(string, IEnumerable&lt;MailMessage&gt;) | Carica i messaggi di posta nella cartella specificata |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_4)(string, IEnumerable&lt;MapiMessage&gt;) | Carica i messaggi mapi nella cartella specificata |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_2)(string, params MailMessage[]) | Carica il messaggio di posta nella cartella specificata |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem)(string, Appointment) | L'operazione ArchiveItem sposta un elemento nella cassetta postale di archivio dell'utente della cassetta postale. |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem_1)(string, ExchangeTask) | L'operazione ArchiveItem sposta un elemento nella cassetta postale di archivio dell'utente della cassetta postale. |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem_2)(string, MapiMessageItemBase) | L'operazione ArchiveItem sposta un elemento nella cassetta postale di archivio dell'utente della cassetta postale. |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem_3)(string, string) | L'operazione ArchiveItem sposta un elemento nella cassetta postale di archivio dell'utente della cassetta postale. |
| [Backup](../../aspose.email.clients.exchange.webservice/iewsclient/backup#backup)(ExchangeFolderInfoCollection, Stream, BackupOptions) | Esegue il backup del contenuto delle cartelle specificate |
| [Backup](../../aspose.email.clients.exchange.webservice/iewsclient/backup#backup_1)(ExchangeFolderInfoCollection, string, BackupOptions) | Esegue il backup del contenuto delle cartelle specificate |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment)(Appointment) | Annulla l'appuntamento. |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_2)(MapiCalendar) | Annulla l'appuntamento. |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_4)(string) | Annulla una riunione in uscita su un calendario organizzatore |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_1)(Appointment, string) | Annulla l'appuntamento. |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_3)(MapiCalendar, string) | Annulla l'appuntamento. |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_5)(string, string) | Annulla una riunione in uscita su un calendario organizzatore |
| [CheckUserAvailability](../../aspose.email.clients.exchange.webservice/iewsclient/checkuseravailability#checkuseravailability)(string, DateRange) | Verifica la disponibilità dell'utente entro la finestra temporale specificata. |
| [CheckUserAvailability](../../aspose.email.clients.exchange.webservice/iewsclient/checkuseravailability#checkuseravailability_1)(StringCollection, DateRange) | Verifica la disponibilità degli utenti entro la finestra temporale specificata. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess_1)(ExchangeDelegateUser, string) | Chiude l'accesso alla casella di posta specificata per l'utente specificato. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess_2)(ExchangeDelegateUserCollection, string) | Chiude l'accesso alla casella di posta specificata per l'utente specificato. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess)(ExchangeFolderUserInfo, string) | Chiude l'accesso alla casella di posta specificata per l'utente specificato. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess_3)(string, string) | Chiude l'accesso alla casella di posta specificata per l'utente specificato. |
| [CopyConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/copyconversationitems#copyconversationitems)(string, string) | Copia gli elementi della conversazione nella cartella di destinazione specificata |
| [CopyConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/copyconversationitems#copyconversationitems_1)(string, string, string) | Copia gli elementi della conversazione, che si trovano nella cartella specificata, nella cartella di destinazione specificata |
| [CopyItem](../../aspose.email.clients.exchange.webservice/iewsclient/copyitem)(string, string) | Copia l'elemento nella cartella specificata |
| [CreateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/createappointment#createappointment)(Appointment) | Crea appuntamento. |
| [CreateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/createappointment#createappointment_1)(Appointment, string) | Crea appuntamento. |
| [CreateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/createappointment#createappointment_4)(MapiCalendar, string, bool) | Crea appuntamento. |
| [CreateCalendarSharingInvitationMessage](../../aspose.email.clients.exchange.webservice/iewsclient/createcalendarsharinginvitationmessage)(string) | Crea messaggio di invito alla condivisione del calendario. |
| [CreateContact](../../aspose.email.clients.exchange.webservice/iewsclient/createcontact#createcontact_1)(Contact) | Crea un elemento di contatto nell'archivio di Exchange. |
| [CreateContact](../../aspose.email.clients.exchange.webservice/iewsclient/createcontact#createcontact_3)(string, Contact) | Crea un elemento di contatto nella cartella specificata. |
| [CreateDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/createdistributionlist)(ExchangeDistributionList, MailAddressCollection) | Crea la lista di distribuzione privata. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder)(string) | Crea una nuova cartella nella cartella principale. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_1)(string, ExchangeFolderType) | Crea una nuova cartella nella cartella principale. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_2)(string, string) | Crea la nuova cartella con il nome specificato nella cartella principale specificata. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_3)(string, string, ExchangeFolderPermissionCollection) | Crea la nuova cartella |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_5)(string, string, ExchangeFolderType) | Crea la nuova cartella |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_4)(string, string, ExchangeFolderPermissionCollection, string) | Crea la nuova cartella |
| [CreateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/createinboxrule#createinboxrule)(InboxRule) | Crea la regola della posta in arrivo specificata |
| [CreateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/createinboxrule#createinboxrule_1)(InboxRule, string) | Crea la regola della posta in arrivo specificata |
| [CreateItem](../../aspose.email.clients.exchange.webservice/iewsclient/createitem#createitem)(MapiMessageItemBase) | Crea l'elemento specificato nella cartella dell'elemento predefinita. |
| [CreateItem](../../aspose.email.clients.exchange.webservice/iewsclient/createitem#createitem_1)(string, MapiMessageItemBase) | Crea l'elemento specificato nella cartella specificata. |
| [CreateItems](../../aspose.email.clients.exchange.webservice/iewsclient/createitems)(ExchangeStreamedItem[], string) | Crea gli elementi specificati nella cartella specificata |
| [CreatePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createpublicfolder#createpublicfolder)(string, ExchangeFolderPermissionCollection) | Crea la cartella pubblica specificata nella cartella pubblica radice |
| [CreatePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createpublicfolder#createpublicfolder_1)(string, ExchangeFolderPermissionCollection, ExchangeFolderType) | Crea la cartella pubblica specificata nella cartella pubblica radice |
| [CreatePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createpublicfolder#createpublicfolder_2)(string, string, ExchangeFolderPermissionCollection) | Crea la cartella pubblica specificata nella cartella pubblica radice |
| [CreateTask](../../aspose.email.clients.exchange.webservice/iewsclient/createtask#createtask)(ExchangeTask) | Crea l'attività specificata nella cartella delle attività predefinita. |
| [CreateTask](../../aspose.email.clients.exchange.webservice/iewsclient/createtask#createtask_2)(string, ExchangeTask) | Crea l'attività specificata nella cartella specificata. |
| [CreateUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/createuserconfiguration)(UserConfiguration) | Crea la configurazione utente specificata |
| [DelegateAccess](../../aspose.email.clients.exchange.webservice/iewsclient/delegateaccess#delegateaccess)(ExchangeDelegateUser, string) | Delega l'accesso alla cassetta postale specificata all'utente specificato. |
| [DelegateAccess](../../aspose.email.clients.exchange.webservice/iewsclient/delegateaccess#delegateaccess_1)(ExchangeDelegateUserCollection, string) | Delega l'accesso alla casella di posta agli utenti specificati. |
| [DelegateAccess](../../aspose.email.clients.exchange.webservice/iewsclient/delegateaccess#delegateaccess_2)(string, ExchangeDelegateFolderPermissionLevel, string) | Delega l'accesso alla cassetta postale principale all'utente specificato. |
| [DeleteConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/deleteconversationitems#deleteconversationitems)(string) | Elimina tutti gli elementi della conversazione specificata |
| [DeleteConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/deleteconversationitems#deleteconversationitems_1)(string, string) | Elimina gli elementi della conversazione, che si trovano nella cartella specificata |
| [DeleteDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/deletedistributionlist)(ExchangeDistributionList, bool) | Elimina la lista di distribuzione. |
| [DeleteFolder](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolder#deletefolder)(string) | Elimina la cartella |
| [DeleteFolder](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolder#deletefolder_1)(string, bool) | Elimina la cartella |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders)(ExchangeFolderInfoCollection) | Elimina le cartelle specificate |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders_2)(StringCollection) | Elimina le cartelle specificate |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders_1)(ExchangeFolderInfoCollection, bool) | Elimina le cartelle specificate |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders_3)(StringCollection, bool) | Elimina la cartella |
| [DeleteFromDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/deletefromdistributionlist)(ExchangeDistributionList, MailAddressCollection) | Elimina i membri dalla lista di distribuzione. |
| [DeleteInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/deleteinboxrule#deleteinboxrule)(string) | Elimina la regola posta in arrivo specificata |
| [DeleteInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/deleteinboxrule#deleteinboxrule_1)(string, string) | Elimina la regola posta in arrivo specificata |
| [DeleteItem](../../aspose.email.clients.exchange.webservice/iewsclient/deleteitem)(string, DeletionOptions) | Elimina l'elemento specificato |
| [DeleteItems](../../aspose.email.clients.exchange.webservice/iewsclient/deleteitems)(IEnumerable&lt;string&gt;, DeletionOptions) | Elimina gli elementi specificati |
| [DeleteUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/deleteuserconfiguration)(UserConfigurationName) | Elimina la configurazione utente specificata |
| [DisconnectPhoneCall](../../aspose.email.clients.exchange.webservice/iewsclient/disconnectphonecall)(string) | Disconnette una telefonata specificata da id. |
| [EmptyFolder](../../aspose.email.clients.exchange.webservice/iewsclient/emptyfolder#emptyfolder)(string) | Svuota la cartella specificata. Le sottocartelle non verranno eliminate; gli elementi eliminati verranno spostati nella cartella DeletedItems |
| [EmptyFolder](../../aspose.email.clients.exchange.webservice/iewsclient/emptyfolder#emptyfolder_1)(string, EmptyFolderOptions) | Svuota la cartella specificata |
| [ExpandDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/expanddistributionlist)(MailAddress) | Espande i membri della lista di distribuzione pubblica. |
| [ExportItems](../../aspose.email.clients.exchange.webservice/iewsclient/exportitems)(params string[]) | Esporta gli elementi specificati dalla mailbox |
| [FetchAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/fetchappointment#fetchappointment)(string) | Recupera l'appuntamento specificato dal server. |
| [FetchAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/fetchappointment#fetchappointment_1)(string, string) | Recupera l'appuntamento specificato dal server. |
| [FetchAttachment](../../aspose.email.clients.exchange.webservice/iewsclient/fetchattachment)(string) | Recupera l'allegato |
| [FetchConversationMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchconversationmessages)(string) | Recupera i messaggi di conversazione specificati |
| [FetchDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/fetchdistributionlist)(ExchangeDistributionList) | Recupera i membri privati della lista di distribuzione. |
| [FetchItem](../../aspose.email.clients.exchange.webservice/iewsclient/fetchitem#fetchitem)(string) | Recupera l'elemento come[`MapiMessage`](../../aspose.email.mapi/mapimessage) . |
| [FetchItem](../../aspose.email.clients.exchange.webservice/iewsclient/fetchitem#fetchitem_1)(string, IEnumerable&lt;PropertyDescriptor&gt;) | Recupera l'elemento come[`MapiMessage`](../../aspose.email.mapi/mapimessage) . |
| [FetchItems](../../aspose.email.clients.exchange.webservice/iewsclient/fetchitems)(EwsFetchItems) | Recupera gli elementi. |
| [FetchMapiCalendar](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapicalendar#fetchmapicalendar)(IEnumerable&lt;string&gt;) | Recupera matrice di[`MapiCalendar`](../../aspose.email.mapi/mapicalendar) oggetti. |
| [FetchMapiCalendar](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapicalendar#fetchmapicalendar_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Recupera matrice di[`MapiCalendar`](../../aspose.email.mapi/mapicalendar) oggetti. |
| [FetchMapiMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapimessages#fetchmapimessages)(IEnumerable&lt;string&gt;) | Recupera i messaggi specificati |
| [FetchMapiMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapimessages#fetchmapimessages_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Recupera i messaggi specificati |
| [FetchMapiNotes](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapinotes#fetchmapinotes)(IEnumerable&lt;string&gt;) | Recupera matrice di[`MapiNote`](../../aspose.email.mapi/mapinote) oggetti. |
| [FetchMapiNotes](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapinotes#fetchmapinotes_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Recupera matrice di[`MapiNote`](../../aspose.email.mapi/mapinote) oggetti. |
| [FetchMapiTasks](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapitasks#fetchmapitasks)(IEnumerable&lt;string&gt;) | Recupera matrice di[`MapiTask`](../../aspose.email.mapi/mapitask) oggetti. |
| [FetchMapiTasks](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapitasks#fetchmapitasks_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Recupera matrice di[`MapiTask`](../../aspose.email.mapi/mapitask) oggetti. |
| [FetchMessage](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessage#fetchmessage)(string) | Recupera il messaggio. |
| [FetchMessage](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessage#fetchmessage_1)(string, IEnumerable&lt;PropertyDescriptor&gt;) | Recupera il messaggio dal server |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages)(IEnumerable&lt;ExchangeMessageInfo&gt;) | Recupera i messaggi specificati |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages_1)(IEnumerable&lt;string&gt;) | Recupera i messaggi specificati |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages_3)(StringCollection) | Recupera i messaggi specificati |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages_2)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Recupera i messaggi specificati |
| [FetchTask](../../aspose.email.clients.exchange.webservice/iewsclient/fetchtask)(string) | Recupera l'attività specificata. |
| [FindConversations](../../aspose.email.clients.exchange.webservice/iewsclient/findconversations)(string) | Trova le conversazioni nella cartella specificata |
| [FindMessageTrackingReport](../../aspose.email.clients.exchange.webservice/iewsclient/findmessagetrackingreport)(FindMessageTrackingReportOptions) | Trova i messaggi che soddisfano i criteri specificati. |
| [FindPeople](../../aspose.email.clients.exchange.webservice/iewsclient/findpeople#findpeople_1)(string, int) | Trova i contatti che si trovano nell'elenco indirizzi globale (GAL) sul server. |
| [FindPeople](../../aspose.email.clients.exchange.webservice/iewsclient/findpeople#findpeople)(string, MailQuery, int) | Trova i contatti che si trovano nella casella di posta personale dell'utente specificato sul server. |
| [FolderExists](../../aspose.email.clients.exchange.webservice/iewsclient/folderexists#folderexists)(string, string) | Verifica se la cartella specificata esiste. |
| [FolderExists](../../aspose.email.clients.exchange.webservice/iewsclient/folderexists#folderexists_1)(string, string, out ExchangeFolderInfo) | Verifica se la cartella specificata esiste. |
| [Forward](../../aspose.email.clients.exchange.webservice/iewsclient/forward)(MailMessage, ExchangeMessageInfo) | Inoltra un messaggio. |
| [GetCallInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getcallinfo)(string) | Recupera le informazioni sulla telefonata in base all'ID chiamata |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact)(ObjectIdentifier) | Recupera le informazioni di contatto in base all'identificatore specificato. |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact_2)(string) | Recupera le informazioni di contatto in base all'identificatore specificato. |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact_1)(ObjectIdentifier, ExchangeListContactsOptions) | Recupera le informazioni di contatto in base all'identificatore specificato. |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact_3)(string, ExchangeListContactsOptions) | Recupera le informazioni di contatto in base all'identificatore specificato. |
| [GetContacts](../../aspose.email.clients.exchange.webservice/iewsclient/getcontacts#getcontacts)(string) | Elenca i contatti che si trovano nella cartella specificata sul server |
| [GetContacts](../../aspose.email.clients.exchange.webservice/iewsclient/getcontacts#getcontacts_1)(string, ExchangeListContactsOptions) | Elenca i contatti che si trovano nella cartella specificata sul server |
| [GetExchangeType](../../aspose.email.clients.exchange.webservice/iewsclient/getexchangetype)() | Ottiene le informazioni sulla versione corrente di MS Exchange. |
| [GetFolderInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getfolderinfo)(string) | Ottiene le informazioni sulla cartella |
| [GetFolderPermissions](../../aspose.email.clients.exchange.webservice/iewsclient/getfolderpermissions)(string) | Ottiene i permessi della cartella. |
| [GetInboxRules](../../aspose.email.clients.exchange.webservice/iewsclient/getinboxrules#getinboxrules)() | Ottiene le regole della posta in arrivo |
| [GetInboxRules](../../aspose.email.clients.exchange.webservice/iewsclient/getinboxrules#getinboxrules_1)(string) | Ottiene le regole della posta in arrivo |
| [GetMailboxes](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxes)() | Elenca le cassette postali con indirizzi SMTP. Nota: il numero massimo di contatti restituiti è 100. Questa è una restrizione dell'operazione EWS utilizzata. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxinfo#getmailboxinfo)() | Ottiene le informazioni sulla casella di posta. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxinfo#getmailboxinfo_1)(string) | Ottiene le informazioni sulla casella di posta |
| [GetMailboxSize](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxsize)() | Ottiene la dimensione della casella di posta. Si noti che questa operazione viene eseguita in modo ricorsivo per tutte le sottocartelle e richiede un po' di tempo |
| [GetMailboxSizeEx](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxsizeex)(string) | Ottiene la dimensione della casella di posta Si noti che questa operazione viene eseguita in modo ricorsivo per tutte le sottocartelle e richiede un po' di tempo |
| [GetMailTips](../../aspose.email.clients.exchange.webservice/iewsclient/getmailtips)(GetMailTipsOptions) | Ottiene suggerimenti per la posta |
| [GetMessageTrackingReport](../../aspose.email.clients.exchange.webservice/iewsclient/getmessagetrackingreport)(GetMessageTrackingReportOptions) | Ottiene il rapporto di verifica dei messaggi |
| [GetServerTimeZoneIds](../../aspose.email.clients.exchange.webservice/iewsclient/getservertimezoneids#getservertimezoneids)() | GetServerTimeZoneIds restituisce informazioni dall'ID fuso orario disponibili su un server Exchange. |
| [GetServerTimeZoneIds](../../aspose.email.clients.exchange.webservice/iewsclient/getservertimezoneids#getservertimezoneids_1)(IEnumerable&lt;string&gt;) | GetServerTimeZoneIds restituisce informazioni dall'ID fuso orario disponibili su un server Exchange. |
| [GetServerTimeZoneIds](../../aspose.email.clients.exchange.webservice/iewsclient/getservertimezoneids#getservertimezoneids_2)(params string[]) | GetServerTimeZoneIds restituisce informazioni dall'ID fuso orario disponibili su un server Exchange. |
| [GetUMConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/getumconfiguration)() | Recupera la configurazione della messaggistica unificata |
| [GetUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/getuserconfiguration)(UserConfigurationName) | Ottiene la configurazione utente specificata |
| [GetVersionInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getversioninfo)() | Restituisce la versione del server di scambio info |
| [ImpersonateUser](../../aspose.email.clients.exchange.webservice/iewsclient/impersonateuser)(ItemChoice, string) | Rappresenta l'utente. |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments)() | Recupera l'elenco degli appuntamenti per la cartella del calendario predefinita |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_3)(bool) | Recupera l'elenco degli appuntamenti per la cartella del calendario predefinita |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_1)(MailQuery) | Recupera l'elenco degli appuntamenti per la cartella del calendario predefinita |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_4)(string) | Recupera l'elenco degli appuntamenti per la cartella del calendario specificata |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_2)(MailQuery, bool) | Recupera l'elenco degli appuntamenti per la cartella del calendario predefinita |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_7)(string, bool) | Recupera l'elenco degli appuntamenti per la cartella del calendario specificata |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_5)(string, MailQuery) | Recupera l'elenco degli appuntamenti per la cartella del calendario specificata |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_6)(string, MailQuery, bool) | Recupera l'elenco degli appuntamenti per la cartella del calendario specificata |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_2)(int) | Recupera la pagina con gli appuntamenti per la cartella del calendario |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_3)(int, int) | Recupera la pagina con gli appuntamenti per la cartella del calendario |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage)(MailQuery, int) | Recupera la pagina con gli appuntamenti per la cartella del calendario |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_6)(string, int) | Recupera la pagina con gli appuntamenti per la cartella del calendario specificata |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_1)(MailQuery, int, int) | Recupera la pagina con gli appuntamenti per la cartella del calendario |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_7)(string, int, int) | Recupera la pagina con gli appuntamenti per la cartella del calendario specificata |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_4)(string, MailQuery, int) | Recupera la pagina con gli appuntamenti per la cartella del calendario specificata |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_5)(string, MailQuery, int, int) | Recupera la pagina con gli appuntamenti per la cartella del calendario specificata |
| [ListContacts](../../aspose.email.clients.exchange.webservice/iewsclient/listcontacts#listcontacts)(string) | Elenca i contatti che si trovano nella cartella specificata sul server |
| [ListContacts](../../aspose.email.clients.exchange.webservice/iewsclient/listcontacts#listcontacts_1)(string, IEnumerable&lt;PropertyDescriptor&gt;) | Elenca i contatti che si trovano nella cartella specificata sul server |
| [ListDelegates](../../aspose.email.clients.exchange.webservice/iewsclient/listdelegates)(string) | Elenca gli utenti a cui è concesso l'accesso alla cassetta postale specificata. |
| [ListDistributionLists](../../aspose.email.clients.exchange.webservice/iewsclient/listdistributionlists)() | Elenca le liste di distribuzione private. |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems)(string) | Recupera l'elenco degli elementi uri nella cartella specificata |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_1)(string, MailQuery) | Recupera l'elenco degli elementi uri nella cartella specificata |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_3)(string, string) | Recupera l'elenco degli elementi uri nella cartella specificata |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_2)(string, MailQuery, bool) | Recupera l'elenco degli elementi uri nella cartella specificata |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_4)(string, string, MailQuery) | Recupera l'elenco degli elementi uri nella cartella specificata |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_5)(string, string, MailQuery, bool) | Recupera l'elenco degli elementi uri nella cartella specificata |
| [ListMailboxes](../../aspose.email.clients.exchange.webservice/iewsclient/listmailboxes#listmailboxes)() | Elenca le cassette postali. |
| [ListMailboxes](../../aspose.email.clients.exchange.webservice/iewsclient/listmailboxes#listmailboxes_1)(string) | Prestare attenzione, questo metodo sovrascritto funziona con Exchange Server 2013 e versioni successive. Elenca le cassette postali. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages)() | Elenca i messaggi nella cartella della posta in arrivo. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_1)(IEnumerable&lt;string&gt;) | Elenca i messaggi nella cartella specificata. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_2)(string) | Elenca i messaggi. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_7)(string, bool) | Elenca i messaggi nella cartella specificata |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_3)(string, ExchangeListMessagesOptions) | Elenca i messaggi. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_8)(string, int) | Elenca i messaggi. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_5)(string, MailQuery) | Elenca i messaggi nella cartella specificata. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_4)(string, ExchangeListMessagesOptions, IEnumerable&lt;PropertyDescriptor&gt;) | Elenca i messaggi nella cartella specificata |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_9)(string, int, ExchangeListMessagesOptions) | Elenca i messaggi. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_10)(string, int, MailQuery) | Elenca i messaggi nella cartella specificata. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_6)(string, MailQuery, bool) | Elenca i messaggi nella cartella specificata. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_13)(string, string, bool) | Elenca i messaggi nella cartella specificata |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_12)(string, string, MailQuery) | Elenca i messaggi nella cartella specificata. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_11)(string, int, MailQuery, bool) | Elenca i messaggi nella cartella specificata. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_4)(string, int) | Elenca i messaggi nella cartella specificata. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage)(string, PageInfo) | Elenca i messaggi nella cartella specificata. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_5)(string, int, int) | Elenca i messaggi nella cartella specificata. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_2)(string, MailQuery, int) | Elenca i messaggi nella cartella specificata. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_1)(string, PageInfo, ExchangeListMessagesOptions) | Elenca i messaggi nella cartella specificata. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_6)(string, int, int, ExchangeListMessagesOptions) | Elenca i messaggi nella cartella specificata. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_3)(string, MailQuery, int, int) | Elenca i messaggi nella cartella specificata. |
| [ListMessagesFromPublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesfrompublicfolder#listmessagesfrompublicfolder)(ExchangeFolderInfo) | Ottieni raccolta di messaggi dalla cartella pubblica |
| [ListMessagesFromPublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesfrompublicfolder#listmessagesfrompublicfolder_1)(string) | Ottieni raccolta di messaggi dalla cartella pubblica |
| [ListPublicFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listpublicfolders)() | Ottiene la raccolta di cartelle pubbliche dalla cartella pubblica principale |
| [ListSubFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfolders#listsubfolders)(ExchangeFolderInfo) | Ottiene la raccolta di cartelle pubbliche figlie da genitore |
| [ListSubFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfolders#listsubfolders_1)(string) | Ottiene la raccolta di cartelle figlie da genitore |
| [ListSubFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfolders#listsubfolders_2)(string, string) | Ottiene la raccolta di cartelle figlie da genitore |
| [ListSubFoldersByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage#listsubfoldersbypage_1)(string, int) | Cerca nella cartella specificata nella cartella principale specificata con il metodo paging supporta il paging. Richiama per la prima volta nel ciclo di paging. |
| [ListSubFoldersByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage#listsubfoldersbypage)(string, PageInfo) | Cerca la cartella specificata nella cartella principale specificata con il metodo paging supporta il paging. |
| [ListSubFoldersByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage#listsubfoldersbypage_2)(string, int, int) | Cerca la cartella specificata nella cartella principale specificata con il metodo paging supporta il paging. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks)() | Recupera elenchi di attività di scambio per la cartella predefinita. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_1)(string) | Recupera elenchi di attività di scambio. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_3)(string, int) | Recupera elenchi di attività di scambio. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_2)(string, MailQuery) | Recupera elenchi di attività di scambio. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_4)(string, int, MailQuery) | Recupera elenchi di attività di scambio. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_5)(string, int, MailQuery, bool) | Recupera elenchi di attività di scambio. |
| [LoadContactPhoto](../../aspose.email.clients.exchange.webservice/iewsclient/loadcontactphoto)(ContactPhoto) | Carica i dati binari della foto dei contatti |
| [MailDisablePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/maildisablepublicfolder)(string) | Posta-disabilita una cartella pubblica |
| [MailEnablePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/mailenablepublicfolder)(string) | Abilitazione alla posta di una cartella pubblica |
| [MarkAllItems](../../aspose.email.clients.exchange.webservice/iewsclient/markallitems#markallitems_2)(bool, params string[]) | Contrassegna tutti gli elementi nelle cartelle specificate. |
| [MarkAllItems](../../aspose.email.clients.exchange.webservice/iewsclient/markallitems#markallitems)(bool, bool, IEnumerable&lt;string&gt;) | Contrassegna tutti gli elementi nelle cartelle specificate. |
| [MarkAllItems](../../aspose.email.clients.exchange.webservice/iewsclient/markallitems#markallitems_1)(bool, bool, params string[]) | Contrassegna tutti gli elementi nelle cartelle specificate. |
| [MarkAllItemsAsRead](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasread#markallitemsasread)() | Contrassegna tutti gli elementi nella cartella Posta in arrivo come letti senza ricevute. |
| [MarkAllItemsAsRead](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasread#markallitemsasread_1)(IEnumerable&lt;string&gt;) | Contrassegna tutti gli elementi nelle cartelle specificate come letti senza ricevute. |
| [MarkAllItemsAsRead](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasread#markallitemsasread_2)(params string[]) | Contrassegna tutti gli elementi nelle cartelle specificate come letti senza ricevute. |
| [MarkAllItemsAsUnread](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasunread#markallitemsasunread)() | Contrassegna tutti gli elementi nella cartella Posta in arrivo come non letti. |
| [MarkAllItemsAsUnread](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasunread#markallitemsasunread_1)(IEnumerable&lt;string&gt;) | Contrassegna tutti gli elementi nelle cartelle specificate come non letti. |
| [MarkAllItemsAsUnread](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasunread#markallitemsasunread_2)(params string[]) | Contrassegna tutti gli elementi nelle cartelle specificate come non letti. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_2)(bool, IEnumerable&lt;string&gt;) | Il metodo MarkAsJunk sposta i messaggi di posta nella cartella della posta indesiderata e blocca il mittente del messaggio. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_3)(bool, params string[]) | Il metodo MarkAsJunk sposta i messaggi di posta nella cartella della posta indesiderata e blocca il mittente del messaggio. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk)(bool, bool, IEnumerable&lt;string&gt;) | Il metodo MarkAsJunk sposta i messaggi di posta nella cartella della posta indesiderata e blocca il mittente del messaggio. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_1)(bool, bool, params string[]) | Il metodo MarkAsJunk sposta i messaggi di posta nella cartella della posta indesiderata e blocca il mittente del messaggio. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_4)(bool, bool, IEnumerable&lt;string&gt;, out string[], out string[], out string[]) | Il metodo MarkAsJunk sposta i messaggi di posta nella cartella della posta indesiderata e blocca il mittente del messaggio. |
| [MoveConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/moveconversationitems#moveconversationitems)(string, string) | Sposta gli elementi della conversazione nella cartella di destinazione specificata |
| [MoveConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/moveconversationitems#moveconversationitems_1)(string, string, string) | Sposta gli elementi della conversazione, che si trovano nella cartella specificata, nella cartella di destinazione specificata |
| [MoveItem](../../aspose.email.clients.exchange.webservice/iewsclient/moveitem)(string, string) | Sposta l'elemento nella cartella specificata |
| [PlayOnPhone](../../aspose.email.clients.exchange.webservice/iewsclient/playonphone)(string, string) | L'operazione PlayOnPhone avvia una chiamata in uscita e riproduce un messaggio al telefono. |
| [RemoveHeader](../../aspose.email.clients.exchange.webservice/iewsclient/removeheader)(string) | Rimuovi WebHeader da WebHeaderCollection nella richiesta EWS. |
| [Reply](../../aspose.email.clients.exchange.webservice/iewsclient/reply)(MailMessage, ExchangeMessageInfo) | Rispondi al messaggio del mittente. |
| [ReplyAll](../../aspose.email.clients.exchange.webservice/iewsclient/replyall)(MailMessage, ExchangeMessageInfo) | Rispondi al mittente e a tutti i destinatari di un messaggio. |
| [ResetImpersonation](../../aspose.email.clients.exchange.webservice/iewsclient/resetimpersonation)() | Reimposta la rappresentazione. |
| [ResetSubscription](../../aspose.email.clients.exchange.webservice/iewsclient/resetsubscription)() | Ripristina tutti gli abbonamenti |
| [ResolveContact](../../aspose.email.clients.exchange.webservice/iewsclient/resolvecontact)(string) | Risolve nomi di cassette postali ambigui. |
| [ResolveContacts](../../aspose.email.clients.exchange.webservice/iewsclient/resolvecontacts#resolvecontacts)(string) | Risolve i nomi visualizzati delle cassette postali ambigui. Nota: il numero massimo di contatti restituiti è 100. Questa è una restrizione del comando di scambio utilizzato. |
| [ResolveContacts](../../aspose.email.clients.exchange.webservice/iewsclient/resolvecontacts#resolvecontacts_1)(string, ExchangeListContactsOptions) | Risolve indirizzi e-mail e nomi visualizzati ambigui Nota: il numero massimo di contatti restituiti è 100. Questa è una restrizione del funzionamento EWS utilizzato. |
| [Restore](../../aspose.email.clients.exchange.webservice/iewsclient/restore)(PersonalStorage, RestoreSettings) | Ripristina le cartelle di scambio specificate dalla memoria personale specificata. |
| [SaveMessage](../../aspose.email.clients.exchange.webservice/iewsclient/savemessage#savemessage)(string, Stream) | Salva il messaggio. |
| [SaveMessage](../../aspose.email.clients.exchange.webservice/iewsclient/savemessage#savemessage_1)(string, string) | Salva il messaggio. |
| [Send](../../aspose.email.clients.exchange.webservice/iewsclient/send#send)(MailMessage) | Invia il messaggio specificato. |
| [Send](../../aspose.email.clients.exchange.webservice/iewsclient/send#send_1)(MailMessage, FollowUpOptions) | Invia il messaggio. |
| [Send](../../aspose.email.clients.exchange.webservice/iewsclient/send#send_2)(string, string, string, string) | Invia il messaggio specificato |
| [SetConversationReadState](../../aspose.email.clients.exchange.webservice/iewsclient/setconversationreadstate#setconversationreadstate)(string, bool) | Imposta lo stato di lettura degli elementi della conversazione sul valore specificato |
| [SetConversationReadState](../../aspose.email.clients.exchange.webservice/iewsclient/setconversationreadstate#setconversationreadstate_1)(string, string, bool) | Imposta lo stato di lettura degli elementi della conversazione, che si trovano nella cartella specificata, sul valore specificato |
| [SetReadFlag](../../aspose.email.clients.exchange.webservice/iewsclient/setreadflag#setreadflag)(string) | Imposta il flag di lettura. |
| [SetReadFlag](../../aspose.email.clients.exchange.webservice/iewsclient/setreadflag#setreadflag_1)(string, bool) | Contrassegna il messaggio specifico come letto. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_1)(string) | Recupera le modifiche degli elementi e delle sottocartelle in una cartella specificata. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder)(SyncState) | Recupera le modifiche degli elementi in una cartella specificata. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_3)(string, string) | Recupera le modifiche degli elementi in una cartella specificata. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_2)(string, SyncFolderType) | Recupera le modifiche degli elementi e delle sottocartelle in una cartella specificata. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_4)(string, string, IEnumerable&lt;string&gt;) | Recupera le modifiche degli elementi in una cartella specificata. |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment)(Appointment) | Aggiorna l'appuntamento. |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment_2)(MapiCalendar) | Aggiorna l'appuntamento. |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment_1)(Appointment, string) | Aggiorna l'appuntamento. |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment_3)(MapiCalendar, string) | Aggiorna l'appuntamento. |
| [UpdateContact](../../aspose.email.clients.exchange.webservice/iewsclient/updatecontact#updatecontact_1)(Contact) | Aggiorna un elemento di contatto nell'archivio di Exchange. |
| [UpdateContact](../../aspose.email.clients.exchange.webservice/iewsclient/updatecontact#updatecontact)(MapiContact) | Aggiorna un elemento di contatto nell'archivio di Exchange. |
| [UpdateDelegate](../../aspose.email.clients.exchange.webservice/iewsclient/updatedelegate)(ExchangeDelegateUser, string) | Aggiorna le impostazioni dell'utente delegato a cui è concesso l'accesso alla cassetta postale specificata. |
| [UpdateDelegates](../../aspose.email.clients.exchange.webservice/iewsclient/updatedelegates)(ExchangeDelegateUserCollection, string) | Aggiorna le impostazioni degli utenti delegati a cui è concesso l'accesso alla cassetta postale specificata. |
| [UpdateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/updateinboxrule#updateinboxrule)(InboxRule) | Aggiorna la regola della posta in arrivo specificata |
| [UpdateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/updateinboxrule#updateinboxrule_1)(InboxRule, string) | Aggiorna la regola della posta in arrivo specificata |
| [UpdateItems](../../aspose.email.clients.exchange.webservice/iewsclient/updateitems)(ExchangeStreamedItem[], string) | Aggiorna gli elementi specificati in una casella di posta |
| [UpdateNote](../../aspose.email.clients.exchange.webservice/iewsclient/updatenote#updatenote)(MapiNote) | Aggiorna la nota specificata. |
| [UpdateNote](../../aspose.email.clients.exchange.webservice/iewsclient/updatenote#updatenote_1)(string, MapiNote) | Aggiorna la nota specificata. |
| [UpdateNote](../../aspose.email.clients.exchange.webservice/iewsclient/updatenote#updatenote_2)(string, MapiNote, IEnumerable&lt;PropertyDescriptor&gt;) | Aggiorna la nota specificata. |
| [UpdateSubscription](../../aspose.email.clients.exchange.webservice/iewsclient/updatesubscription)() | Aggiorna gli abbonamenti |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_3)(ExchangeTask) | Aggiorna l'attività specificata. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask)(MapiTask) | Aggiorna l'attività specificata. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_4)(ExchangeTask, UpdateTaskOptions) | Aggiorna l'attività specificata. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_1)(string, MapiTask) | Aggiorna l'attività specificata. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_2)(string, MapiTask, IEnumerable&lt;PropertyDescriptor&gt;) | Aggiorna l'attività specificata. |
| [UpdateUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/updateuserconfiguration)(UserConfiguration) | Aggiorna la configurazione utente specificata |

### Guarda anche

* interface [IExchangeClientBase](../../aspose.email.clients.exchange/iexchangeclientbase)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
