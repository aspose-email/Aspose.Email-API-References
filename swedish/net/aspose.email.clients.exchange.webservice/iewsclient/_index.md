---
title: IEWSClient
second_title: Aspose.Email för .NET API-referens
description: Representerar gränssnittet för Exchange-klienten.
type: docs
weight: 3960
url: /sv/net/aspose.email.clients.exchange.webservice/iewsclient/
---
## IEWSClient interface

Representerar gränssnittet för Exchange-klienten.

```csharp
public interface IEWSClient : IExchangeClientBase
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CalendarFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/calendarfoldereventfilter) { get; set; } | Anger händelsetyper för Calendar folder |
| [ContactsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/contactsfoldereventfilter) { get; set; } | Anger händelsetyper för Contacts folder |
| [CurrentCalendarFolderUri](../../aspose.email.clients.exchange.webservice/iewsclient/currentcalendarfolderuri) { get; set; } | Hämtar eller ställer in aktuell kalendermapp uri |
| [DeletedItemsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/deleteditemsfoldereventfilter) { get; set; } | Anger händelsetyper för DeletedItems folder |
| [DraftsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/draftsfoldereventfilter) { get; set; } | Anger händelsetyper för mappen Drafts |
| [EnableDecompression](../../aspose.email.clients.exchange.webservice/iewsclient/enabledecompression) { get; set; } | Hämtar eller ställer in ett värde som anger om dekompression är aktiverat |
| [Headers](../../aspose.email.clients.exchange.webservice/iewsclient/headers) { get; } | Hämtar array av namnvärdespar som läggs till i WebHeaderCollection i EWS-förfrågan. |
| [InboxFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/inboxfoldereventfilter) { get; set; } | Anger händelsetyper för Inbox folder |
| [JournalFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/journalfoldereventfilter) { get; set; } | Anger händelsetyper för Journal folder |
| [MailboxInfo](../../aspose.email.clients.exchange.webservice/iewsclient/mailboxinfo) { get; } | Hämtar brevlådeinformationen. |
| [NotesFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/notesfoldereventfilter) { get; set; } | Anger händelsetyper för Notes folder |
| [NotificationsCheckInterval](../../aspose.email.clients.exchange.webservice/iewsclient/notificationscheckinterval) { get; set; } | Definierar intervall för aviseringskontroll |
| [NotificationTimeout](../../aspose.email.clients.exchange.webservice/iewsclient/notificationtimeout) { get; set; } | Definierar timeout för serveraviseringar |
| [OutboxFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/outboxfoldereventfilter) { get; set; } | Anger händelsetyper för Outbox folder |
| [ReconnectCount](../../aspose.email.clients.exchange.webservice/iewsclient/reconnectcount) { get; set; } | Hämtar eller ställer in antalet återanslutningsförsök vid anslutningsavbrott. |
| [ReturnClientRequestId](../../aspose.email.clients.exchange.webservice/iewsclient/returnclientrequestid) { get; set; } | Hämtar eller sätter en flagga för att indikera om klienten kräver att serversidan returnerar begäran-id. |
| [RootFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/rootfoldereventfilter) { get; set; } | Anger händelsetyper för rotmappen |
| [SentItemsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/sentitemsfoldereventfilter) { get; set; } | Anger händelsetyper för SentItems folder |
| [ServerVersion](../../aspose.email.clients.exchange.webservice/iewsclient/serverversion) { get; } | Får information om den aktuella versionen av MS Exchange. |
| [TasksFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/tasksfoldereventfilter) { get; set; } | Anger händelsetyper för Tasks folder |
| [TimezoneId](../../aspose.email.clients.exchange.webservice/iewsclient/timezoneid) { get; set; } | Hämtar eller ställer in tidszon id |
| [UseSlashAsFolderSeparator](../../aspose.email.clients.exchange.webservice/iewsclient/useslashasfolderseparator) { get; set; } | Hämtar eller ställer in värde som avgör om snedstrecket '/' används som mappavgränsare. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddHeader](../../aspose.email.clients.exchange.webservice/iewsclient/addheader)(string, string) | Lägger till namn och värde till WebHeaderCollection i EWS-förfrågan. |
| [AddToDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/addtodistributionlist)(ExchangeDistributionList, MailAddressCollection) | Lägger till medlemmarna i distributionslistan. |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage)(MailMessage) | Laddar upp e-postmeddelandet till mappen Inkorg |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_1)(MapiMessage) | Laddar upp e-postmeddelandet till den angivna mappen |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_2)(MapiMessage, bool) | Laddar upp e-postmeddelandet till den angivna mappen |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_3)(string, MailMessage) | Laddar upp e-postmeddelandet till den angivna mappen |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_5)(string, MapiMessage, bool) | Laddar upp e-postmeddelandet till den angivna mappen |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_1)(IEnumerable&lt;MailMessage&gt;) | Laddar upp e-postmeddelandet till den angivna mappen |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages)(params MailMessage[]) | Laddar upp e-postmeddelandet till den angivna mappen |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_3)(string, IEnumerable&lt;MailMessage&gt;) | Laddar upp e-postmeddelandena till den angivna mappen |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_4)(string, IEnumerable&lt;MapiMessage&gt;) | Laddar upp mapi-meddelanden till den angivna mappen |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_2)(string, params MailMessage[]) | Laddar upp e-postmeddelandet till den angivna mappen |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem)(string, Appointment) | Operationen ArchiveItem flyttar ett objekt till brevlådeanvändarens arkivpostlåda. |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem_1)(string, ExchangeTask) | Operationen ArchiveItem flyttar ett objekt till brevlådeanvändarens arkivpostlåda. |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem_2)(string, MapiMessageItemBase) | Operationen ArchiveItem flyttar ett objekt till brevlådeanvändarens arkivpostlåda. |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem_3)(string, string) | Operationen ArchiveItem flyttar ett objekt till brevlådeanvändarens arkivpostlåda. |
| [Backup](../../aspose.email.clients.exchange.webservice/iewsclient/backup#backup)(ExchangeFolderInfoCollection, Stream, BackupOptions) | Säkerhetskopierar innehållet i de angivna mapparna |
| [Backup](../../aspose.email.clients.exchange.webservice/iewsclient/backup#backup_1)(ExchangeFolderInfoCollection, string, BackupOptions) | Säkerhetskopierar innehållet i de angivna mapparna |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment)(Appointment) | Avbryter ett möte. |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_2)(MapiCalendar) | Avbryter ett möte. |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_4)(string) | Avbryter ett spännande möte på en arrangörskalender |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_1)(Appointment, string) | Avbryter ett möte. |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_3)(MapiCalendar, string) | Avbryter ett möte. |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_5)(string, string) | Avbryter ett spännande möte på en arrangörskalender |
| [CheckUserAvailability](../../aspose.email.clients.exchange.webservice/iewsclient/checkuseravailability#checkuseravailability)(string, DateRange) | Kontrollerar användarens tillgänglighet inom det angivna tidsfönstret. |
| [CheckUserAvailability](../../aspose.email.clients.exchange.webservice/iewsclient/checkuseravailability#checkuseravailability_1)(StringCollection, DateRange) | Kontrollerar användarnas tillgänglighet inom det angivna tidsfönstret. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess_1)(ExchangeDelegateUser, string) | Stänger åtkomst till den angivna postlådan för den angivna användaren. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess_2)(ExchangeDelegateUserCollection, string) | Stänger åtkomst till den angivna postlådan för den angivna användaren. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess)(ExchangeFolderUserInfo, string) | Stänger åtkomst till den angivna postlådan för den angivna användaren. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess_3)(string, string) | Stänger åtkomst till den angivna postlådan för den angivna användaren. |
| [CopyConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/copyconversationitems#copyconversationitems)(string, string) | Kopierar konversationsobjekten till den angivna målmappen |
| [CopyConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/copyconversationitems#copyconversationitems_1)(string, string, string) | Kopierar konversationsobjekten, som finns i den angivna mappen, till den angivna målmappen |
| [CopyItem](../../aspose.email.clients.exchange.webservice/iewsclient/copyitem)(string, string) | Kopierar objektet till angiven folder |
| [CreateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/createappointment#createappointment)(Appointment) | Skapar möte. |
| [CreateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/createappointment#createappointment_1)(Appointment, string) | Skapar möte. |
| [CreateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/createappointment#createappointment_4)(MapiCalendar, string, bool) | Skapar möte. |
| [CreateCalendarSharingInvitationMessage](../../aspose.email.clients.exchange.webservice/iewsclient/createcalendarsharinginvitationmessage)(string) | Skapa inbjudan till kalenderdelning. |
| [CreateContact](../../aspose.email.clients.exchange.webservice/iewsclient/createcontact#createcontact_1)(Contact) | Skapar ett kontaktobjekt i Exchange-butiken. |
| [CreateContact](../../aspose.email.clients.exchange.webservice/iewsclient/createcontact#createcontact_3)(string, Contact) | Skapar ett kontaktobjekt i den angivna mappen. |
| [CreateDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/createdistributionlist)(ExchangeDistributionList, MailAddressCollection) | Skapar den privata distributionslistan. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder)(string) | Skapar ny mapp i rotmappen. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_1)(string, ExchangeFolderType) | Skapar ny mapp i rotmappen. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_2)(string, string) | Skapar den nya mappen med det angivna namnet i den angivna överordnade mappen. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_3)(string, string, ExchangeFolderPermissionCollection) | Skapar den nya mappen |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_5)(string, string, ExchangeFolderType) | Skapar den nya mappen |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_4)(string, string, ExchangeFolderPermissionCollection, string) | Skapar den nya mappen |
| [CreateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/createinboxrule#createinboxrule)(InboxRule) | Skapar den angivna inkorgsregeln |
| [CreateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/createinboxrule#createinboxrule_1)(InboxRule, string) | Skapar den angivna inkorgsregeln |
| [CreateItem](../../aspose.email.clients.exchange.webservice/iewsclient/createitem#createitem)(MapiMessageItemBase) | Skapar det givna objektet i standardobjektmappen. |
| [CreateItem](../../aspose.email.clients.exchange.webservice/iewsclient/createitem#createitem_1)(string, MapiMessageItemBase) | Skapar det givna objektet i den angivna mappen. |
| [CreateItems](../../aspose.email.clients.exchange.webservice/iewsclient/createitems)(ExchangeStreamedItem[], string) | Skapar de angivna objekten i den angivna mappen |
| [CreatePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createpublicfolder#createpublicfolder)(string, ExchangeFolderPermissionCollection) | Skapar den angivna offentliga mappen i den offentliga rotmappen |
| [CreatePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createpublicfolder#createpublicfolder_1)(string, ExchangeFolderPermissionCollection, ExchangeFolderType) | Skapar den angivna offentliga mappen i den offentliga rotmappen |
| [CreatePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createpublicfolder#createpublicfolder_2)(string, string, ExchangeFolderPermissionCollection) | Skapar den angivna offentliga mappen i den offentliga rotmappen |
| [CreateTask](../../aspose.email.clients.exchange.webservice/iewsclient/createtask#createtask)(ExchangeTask) | Skapar den givna uppgiften i standarduppgiftsmappen. |
| [CreateTask](../../aspose.email.clients.exchange.webservice/iewsclient/createtask#createtask_2)(string, ExchangeTask) | Skapar den givna uppgiften i den angivna mappen. |
| [CreateUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/createuserconfiguration)(UserConfiguration) | Skapar den angivna användarkonfigurationen |
| [DelegateAccess](../../aspose.email.clients.exchange.webservice/iewsclient/delegateaccess#delegateaccess)(ExchangeDelegateUser, string) | Delegerar åtkomst till den angivna postlådan till den angivna användaren. |
| [DelegateAccess](../../aspose.email.clients.exchange.webservice/iewsclient/delegateaccess#delegateaccess_1)(ExchangeDelegateUserCollection, string) | Delegerar åtkomst till brevlådan till de angivna användarna. |
| [DelegateAccess](../../aspose.email.clients.exchange.webservice/iewsclient/delegateaccess#delegateaccess_2)(string, ExchangeDelegateFolderPermissionLevel, string) | Delegerar åtkomst på huvudpostlådan till den angivna användaren. |
| [DeleteConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/deleteconversationitems#deleteconversationitems)(string) | Tar bort alla objekt i den angivna konversationen |
| [DeleteConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/deleteconversationitems#deleteconversationitems_1)(string, string) | Tar bort konversationsobjekten som finns i den angivna mappen |
| [DeleteDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/deletedistributionlist)(ExchangeDistributionList, bool) | Tar bort distributionslistan. |
| [DeleteFolder](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolder#deletefolder)(string) | Tar bort mappen |
| [DeleteFolder](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolder#deletefolder_1)(string, bool) | Tar bort mappen |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders)(ExchangeFolderInfoCollection) | Tar bort de angivna mapparna |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders_2)(StringCollection) | Tar bort de angivna mapparna |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders_1)(ExchangeFolderInfoCollection, bool) | Tar bort de angivna mapparna |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders_3)(StringCollection, bool) | Tar bort mappen |
| [DeleteFromDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/deletefromdistributionlist)(ExchangeDistributionList, MailAddressCollection) | Tar bort medlemmarna från distributionslistan. |
| [DeleteInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/deleteinboxrule#deleteinboxrule)(string) | Tar bort den angivna inkorgsregeln |
| [DeleteInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/deleteinboxrule#deleteinboxrule_1)(string, string) | Tar bort den angivna inkorgsregeln |
| [DeleteItem](../../aspose.email.clients.exchange.webservice/iewsclient/deleteitem)(string, DeletionOptions) | Tar bort specificerad item |
| [DeleteItems](../../aspose.email.clients.exchange.webservice/iewsclient/deleteitems)(IEnumerable&lt;string&gt;, DeletionOptions) | Tar bort specificerade objekt |
| [DeleteUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/deleteuserconfiguration)(UserConfigurationName) | Tar bort den angivna användarkonfigurationen |
| [DisconnectPhoneCall](../../aspose.email.clients.exchange.webservice/iewsclient/disconnectphonecall)(string) | Kopplar bort ett telefonsamtal specificerat av id. |
| [EmptyFolder](../../aspose.email.clients.exchange.webservice/iewsclient/emptyfolder#emptyfolder)(string) | Tömmer den angivna mappen. Undermappar kommer inte att raderas; borttagna objekt kommer att flyttas till DeletedItems folder |
| [EmptyFolder](../../aspose.email.clients.exchange.webservice/iewsclient/emptyfolder#emptyfolder_1)(string, EmptyFolderOptions) | Tömmer den angivna mappen |
| [ExpandDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/expanddistributionlist)(MailAddress) | Utökar de offentliga distributionslistans medlemmar. |
| [ExportItems](../../aspose.email.clients.exchange.webservice/iewsclient/exportitems)(params string[]) | Exporterar de angivna objekten från mailbox |
| [FetchAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/fetchappointment#fetchappointment)(string) | Hämta det angivna mötet från servern. |
| [FetchAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/fetchappointment#fetchappointment_1)(string, string) | Hämta det angivna mötet från servern. |
| [FetchAttachment](../../aspose.email.clients.exchange.webservice/iewsclient/fetchattachment)(string) | Hämtar bilagan |
| [FetchConversationMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchconversationmessages)(string) | Hämtar de angivna konversationsmeddelandena |
| [FetchDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/fetchdistributionlist)(ExchangeDistributionList) | Hämtar medlemmarna i den privata distributionslistan. |
| [FetchItem](../../aspose.email.clients.exchange.webservice/iewsclient/fetchitem#fetchitem)(string) | Hämtar objektet som[`MapiMessage`](../../aspose.email.mapi/mapimessage) . |
| [FetchItem](../../aspose.email.clients.exchange.webservice/iewsclient/fetchitem#fetchitem_1)(string, IEnumerable&lt;PropertyDescriptor&gt;) | Hämtar objektet som[`MapiMessage`](../../aspose.email.mapi/mapimessage) . |
| [FetchItems](../../aspose.email.clients.exchange.webservice/iewsclient/fetchitems)(EwsFetchItems) | Hämtar objekten. |
| [FetchMapiCalendar](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapicalendar#fetchmapicalendar)(IEnumerable&lt;string&gt;) | Hämta array av[`MapiCalendar`](../../aspose.email.mapi/mapicalendar) objekt. |
| [FetchMapiCalendar](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapicalendar#fetchmapicalendar_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Hämta array av[`MapiCalendar`](../../aspose.email.mapi/mapicalendar) objekt. |
| [FetchMapiMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapimessages#fetchmapimessages)(IEnumerable&lt;string&gt;) | Hämtar de angivna meddelandena |
| [FetchMapiMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapimessages#fetchmapimessages_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Hämtar de angivna meddelandena |
| [FetchMapiNotes](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapinotes#fetchmapinotes)(IEnumerable&lt;string&gt;) | Hämta array av[`MapiNote`](../../aspose.email.mapi/mapinote) objekt. |
| [FetchMapiNotes](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapinotes#fetchmapinotes_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Hämta array av[`MapiNote`](../../aspose.email.mapi/mapinote) objekt. |
| [FetchMapiTasks](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapitasks#fetchmapitasks)(IEnumerable&lt;string&gt;) | Hämta array av[`MapiTask`](../../aspose.email.mapi/mapitask) objekt. |
| [FetchMapiTasks](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapitasks#fetchmapitasks_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Hämta array av[`MapiTask`](../../aspose.email.mapi/mapitask) objekt. |
| [FetchMessage](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessage#fetchmessage)(string) | Hämtar meddelandet. |
| [FetchMessage](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessage#fetchmessage_1)(string, IEnumerable&lt;PropertyDescriptor&gt;) | Hämtar meddelandet från server |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages)(IEnumerable&lt;ExchangeMessageInfo&gt;) | Hämtar de angivna meddelandena |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages_1)(IEnumerable&lt;string&gt;) | Hämtar de angivna meddelandena |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages_3)(StringCollection) | Hämtar de angivna meddelandena |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages_2)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Hämtar de angivna meddelandena |
| [FetchTask](../../aspose.email.clients.exchange.webservice/iewsclient/fetchtask)(string) | Hämtar den angivna uppgiften. |
| [FindConversations](../../aspose.email.clients.exchange.webservice/iewsclient/findconversations)(string) | Hittar konversationer i den angivna mappen |
| [FindMessageTrackingReport](../../aspose.email.clients.exchange.webservice/iewsclient/findmessagetrackingreport)(FindMessageTrackingReportOptions) | Hittar meddelanden som uppfyller de angivna kriterierna. |
| [FindPeople](../../aspose.email.clients.exchange.webservice/iewsclient/findpeople#findpeople_1)(string, int) | Hitta kontakter som finns i den globala adresslistan (GAL) på servern. |
| [FindPeople](../../aspose.email.clients.exchange.webservice/iewsclient/findpeople#findpeople)(string, MailQuery, int) | Hitta kontakter som finns i den angivna användarens personliga brevlåda på servern. |
| [FolderExists](../../aspose.email.clients.exchange.webservice/iewsclient/folderexists#folderexists)(string, string) | Kontrollerar om den angivna mappen finns. |
| [FolderExists](../../aspose.email.clients.exchange.webservice/iewsclient/folderexists#folderexists_1)(string, string, out ExchangeFolderInfo) | Kontrollerar om den angivna mappen finns. |
| [Forward](../../aspose.email.clients.exchange.webservice/iewsclient/forward)(MailMessage, ExchangeMessageInfo) | Vidarebefordra ett meddelande. |
| [GetCallInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getcallinfo)(string) | Hämtar telefonsamtalsinformation genom samtal id |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact)(ObjectIdentifier) | Hämtar kontaktinformation enligt specificerad identifierare. |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact_2)(string) | Hämtar kontaktinformation enligt specificerad identifierare. |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact_1)(ObjectIdentifier, ExchangeListContactsOptions) | Hämtar kontaktinformation enligt specificerad identifierare. |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact_3)(string, ExchangeListContactsOptions) | Hämtar kontaktinformation enligt specificerad identifierare. |
| [GetContacts](../../aspose.email.clients.exchange.webservice/iewsclient/getcontacts#getcontacts)(string) | Listar kontakter som finns i den angivna mappen på server |
| [GetContacts](../../aspose.email.clients.exchange.webservice/iewsclient/getcontacts#getcontacts_1)(string, ExchangeListContactsOptions) | Listar kontakter som finns i den angivna mappen på server |
| [GetExchangeType](../../aspose.email.clients.exchange.webservice/iewsclient/getexchangetype)() | Får information om den aktuella versionen av MS Exchange. |
| [GetFolderInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getfolderinfo)(string) | Hämtar mappinformationen |
| [GetFolderPermissions](../../aspose.email.clients.exchange.webservice/iewsclient/getfolderpermissions)(string) | Får mappbehörigheterna. |
| [GetInboxRules](../../aspose.email.clients.exchange.webservice/iewsclient/getinboxrules#getinboxrules)() | Får inkorgsregler |
| [GetInboxRules](../../aspose.email.clients.exchange.webservice/iewsclient/getinboxrules#getinboxrules_1)(string) | Får inkorgsregler |
| [GetMailboxes](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxes)() | Listar postlådor med smtp-adresser. Obs: det maximala antalet returnerade kontakter är 100. Detta är en begränsning av använd EWS-drift. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxinfo#getmailboxinfo)() | Hämtar brevlådeinformationen. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxinfo#getmailboxinfo_1)(string) | Hämtar brevlådeinformationen |
| [GetMailboxSize](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxsize)() | Hämtar storleken på brevlådan. Observera att denna operation utförs rekursivt för alla undermappar och gör att det tar lite tid |
| [GetMailboxSizeEx](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxsizeex)(string) | Får storleken på brevlådan Observera att denna operation utförs rekursivt för alla undermappar och gör att det tar lite tid |
| [GetMailTips](../../aspose.email.clients.exchange.webservice/iewsclient/getmailtips)(GetMailTipsOptions) | Får mailtips |
| [GetMessageTrackingReport](../../aspose.email.clients.exchange.webservice/iewsclient/getmessagetrackingreport)(GetMessageTrackingReportOptions) | Får meddelandespårningsrapport |
| [GetServerTimeZoneIds](../../aspose.email.clients.exchange.webservice/iewsclient/getservertimezoneids#getservertimezoneids)() | GetServerTimeZoneIds returnerar information från tidszons-id som är tillgängligt på en Exchange-server. |
| [GetServerTimeZoneIds](../../aspose.email.clients.exchange.webservice/iewsclient/getservertimezoneids#getservertimezoneids_1)(IEnumerable&lt;string&gt;) | GetServerTimeZoneIds returnerar information från tidszons-id som är tillgängligt på en Exchange-server. |
| [GetServerTimeZoneIds](../../aspose.email.clients.exchange.webservice/iewsclient/getservertimezoneids#getservertimezoneids_2)(params string[]) | GetServerTimeZoneIds returnerar information från tidszons-id som är tillgängligt på en Exchange-server. |
| [GetUMConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/getumconfiguration)() | Hämtar enhetlig meddelandekonfiguration |
| [GetUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/getuserconfiguration)(UserConfigurationName) | Hämtar den angivna användarkonfigurationen |
| [GetVersionInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getversioninfo)() | Returnerar utbytesserverversion info |
| [ImpersonateUser](../../aspose.email.clients.exchange.webservice/iewsclient/impersonateuser)(ItemChoice, string) | Utger sig för att vara användaren. |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments)() | Hämtar lista över möten för standardkalendermappen |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_3)(bool) | Hämtar lista över möten för standardkalendermappen |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_1)(MailQuery) | Hämtar lista över möten för standardkalendermappen |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_4)(string) | Hämtar lista över möten för specificerad kalendermapp |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_2)(MailQuery, bool) | Hämtar lista över möten för standardkalendermappen |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_7)(string, bool) | Hämtar lista över möten för specificerad kalendermapp |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_5)(string, MailQuery) | Hämtar lista över möten för specificerad kalendermapp |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_6)(string, MailQuery, bool) | Hämtar lista över möten för specificerad kalendermapp |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_2)(int) | Hämtar sida med möten för kalendermappen |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_3)(int, int) | Hämtar sida med möten för kalendermappen |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage)(MailQuery, int) | Hämtar sida med möten för kalendermappen |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_6)(string, int) | Hämtar sida med möten för angiven kalendermapp |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_1)(MailQuery, int, int) | Hämtar sida med möten för kalendermappen |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_7)(string, int, int) | Hämtar sida med möten för angiven kalendermapp |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_4)(string, MailQuery, int) | Hämtar sida med möten för angiven kalendermapp |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_5)(string, MailQuery, int, int) | Hämtar sida med möten för angiven kalendermapp |
| [ListContacts](../../aspose.email.clients.exchange.webservice/iewsclient/listcontacts#listcontacts)(string) | Listar kontakter som finns i den angivna mappen på server |
| [ListContacts](../../aspose.email.clients.exchange.webservice/iewsclient/listcontacts#listcontacts_1)(string, IEnumerable&lt;PropertyDescriptor&gt;) | Listar kontakter som finns i den angivna mappen på server |
| [ListDelegates](../../aspose.email.clients.exchange.webservice/iewsclient/listdelegates)(string) | Listar de användare som beviljas åtkomst till den angivna postlådan. |
| [ListDistributionLists](../../aspose.email.clients.exchange.webservice/iewsclient/listdistributionlists)() | Lista de privata distributionslistorna. |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems)(string) | Hämta lista över objekt-urier i angiven folder |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_1)(string, MailQuery) | Hämta lista över objekt-urier i angiven folder |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_3)(string, string) | Hämta lista över objekt-urier i angiven folder |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_2)(string, MailQuery, bool) | Hämta lista över objekt-urier i angiven folder |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_4)(string, string, MailQuery) | Hämta lista över objekt-urier i angiven folder |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_5)(string, string, MailQuery, bool) | Hämta lista över objekt-urier i angiven folder |
| [ListMailboxes](../../aspose.email.clients.exchange.webservice/iewsclient/listmailboxes#listmailboxes)() | Listar postlådor. |
| [ListMailboxes](../../aspose.email.clients.exchange.webservice/iewsclient/listmailboxes#listmailboxes_1)(string) | Var uppmärksam, denna åsidosatta metod fungerar med Exchange Server 2013 och högre. Listar postlådor. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages)() | Lista meddelandena i inkorgen. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_1)(IEnumerable&lt;string&gt;) | Lista meddelandena i den angivna mappen. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_2)(string) | Listar meddelandena. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_7)(string, bool) | Lista meddelandena i den angivna mappen |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_3)(string, ExchangeListMessagesOptions) | Listar meddelandena. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_8)(string, int) | Listar meddelandena. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_5)(string, MailQuery) | Lista meddelandena i den angivna mappen. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_4)(string, ExchangeListMessagesOptions, IEnumerable&lt;PropertyDescriptor&gt;) | Lista meddelandena i den angivna mappen |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_9)(string, int, ExchangeListMessagesOptions) | Listar meddelandena. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_10)(string, int, MailQuery) | Lista meddelandena i den angivna mappen. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_6)(string, MailQuery, bool) | Lista meddelandena i den angivna mappen. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_13)(string, string, bool) | Lista meddelandena i den angivna mappen |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_12)(string, string, MailQuery) | Lista meddelandena i den angivna mappen. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_11)(string, int, MailQuery, bool) | Lista meddelandena i den angivna mappen. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_4)(string, int) | Lista meddelandena i den angivna mappen. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage)(string, PageInfo) | Lista meddelandena i den angivna mappen. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_5)(string, int, int) | Lista meddelandena i den angivna mappen. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_2)(string, MailQuery, int) | Lista meddelandena i den angivna mappen. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_1)(string, PageInfo, ExchangeListMessagesOptions) | Lista meddelandena i den angivna mappen. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_6)(string, int, int, ExchangeListMessagesOptions) | Lista meddelandena i den angivna mappen. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_3)(string, MailQuery, int, int) | Lista meddelandena i den angivna mappen. |
| [ListMessagesFromPublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesfrompublicfolder#listmessagesfrompublicfolder)(ExchangeFolderInfo) | Få samling av meddelanden från den offentliga mappen |
| [ListMessagesFromPublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesfrompublicfolder#listmessagesfrompublicfolder_1)(string) | Få samling av meddelanden från den offentliga mappen |
| [ListPublicFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listpublicfolders)() | Hämtar samling av offentliga mappar från den offentliga rotmappen |
| [ListSubFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfolders#listsubfolders)(ExchangeFolderInfo) | Hämtar samling av offentliga underordnade mappar från parent |
| [ListSubFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfolders#listsubfolders_1)(string) | Hämtar samling av underordnade mappar från parent |
| [ListSubFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfolders#listsubfolders_2)(string, string) | Hämtar samling av underordnade mappar från parent |
| [ListSubFoldersByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage#listsubfoldersbypage_1)(string, int) | Söker i den angivna mappen i den givna överordnade mappen med paging Metoden stöder personsökning. Anropar för första gången i personsökningscykeln. |
| [ListSubFoldersByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage#listsubfoldersbypage)(string, PageInfo) | Söker i den angivna mappen i den givna överordnade mappen med paging Metoden stöder personsökning. |
| [ListSubFoldersByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage#listsubfoldersbypage_2)(string, int, int) | Söker i den angivna mappen i den givna överordnade mappen med paging Metoden stöder personsökning. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks)() | Hämtar listor över utbytesuppgifter för standardmappen. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_1)(string) | Hämtar listor över utbytesuppgifter. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_3)(string, int) | Hämtar listor över utbytesuppgifter. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_2)(string, MailQuery) | Hämtar listor över utbytesuppgifter. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_4)(string, int, MailQuery) | Hämtar listor över utbytesuppgifter. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_5)(string, int, MailQuery, bool) | Hämtar listor över utbytesuppgifter. |
| [LoadContactPhoto](../../aspose.email.clients.exchange.webservice/iewsclient/loadcontactphoto)(ContactPhoto) | Laddar kontaktfoto binär data |
| [MailDisablePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/maildisablepublicfolder)(string) | Mail-inaktivera en offentlig mapp |
| [MailEnablePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/mailenablepublicfolder)(string) | Mail-aktivera en offentlig mapp |
| [MarkAllItems](../../aspose.email.clients.exchange.webservice/iewsclient/markallitems#markallitems_2)(bool, params string[]) | Markerar alla objekt i angivna mappar. |
| [MarkAllItems](../../aspose.email.clients.exchange.webservice/iewsclient/markallitems#markallitems)(bool, bool, IEnumerable&lt;string&gt;) | Markerar alla objekt i angivna mappar. |
| [MarkAllItems](../../aspose.email.clients.exchange.webservice/iewsclient/markallitems#markallitems_1)(bool, bool, params string[]) | Markerar alla objekt i angivna mappar. |
| [MarkAllItemsAsRead](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasread#markallitemsasread)() | Markerar alla objekt i inkorgen som lästa utan kvitton. |
| [MarkAllItemsAsRead](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasread#markallitemsasread_1)(IEnumerable&lt;string&gt;) | Markerar alla objekt i angivna mappar som lästa utan kvitton. |
| [MarkAllItemsAsRead](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasread#markallitemsasread_2)(params string[]) | Markerar alla objekt i angivna mappar som lästa utan kvitton. |
| [MarkAllItemsAsUnread](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasunread#markallitemsasunread)() | Markerar alla objekt i inkorgen som olästa. |
| [MarkAllItemsAsUnread](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasunread#markallitemsasunread_1)(IEnumerable&lt;string&gt;) | Markerar alla objekt i angivna mappar som olästa. |
| [MarkAllItemsAsUnread](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasunread#markallitemsasunread_2)(params string[]) | Markerar alla objekt i angivna mappar som olästa. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_2)(bool, IEnumerable&lt;string&gt;) | MarkAsJunk-metoden flyttar e-postmeddelanden till skräppostmappen och blockerar meddelandeavsändaren. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_3)(bool, params string[]) | MarkAsJunk-metoden flyttar e-postmeddelanden till skräppostmappen och blockerar meddelandeavsändaren. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk)(bool, bool, IEnumerable&lt;string&gt;) | MarkAsJunk-metoden flyttar e-postmeddelanden till skräppostmappen och blockerar meddelandeavsändaren. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_1)(bool, bool, params string[]) | MarkAsJunk-metoden flyttar e-postmeddelanden till skräppostmappen och blockerar meddelandeavsändaren. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_4)(bool, bool, IEnumerable&lt;string&gt;, out string[], out string[], out string[]) | MarkAsJunk-metoden flyttar e-postmeddelanden till skräppostmappen och blockerar meddelandeavsändaren. |
| [MoveConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/moveconversationitems#moveconversationitems)(string, string) | Flyttar konversationsobjekten till den angivna målmappen |
| [MoveConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/moveconversationitems#moveconversationitems_1)(string, string, string) | Flyttar konversationsobjekten, som finns i den angivna mappen, till den angivna målmappen |
| [MoveItem](../../aspose.email.clients.exchange.webservice/iewsclient/moveitem)(string, string) | Flyttar objektet till angiven folder |
| [PlayOnPhone](../../aspose.email.clients.exchange.webservice/iewsclient/playonphone)(string, string) | PlayOnPhone-operationen initierar ett utgående samtal och spelar upp ett meddelande över telefonen. |
| [RemoveHeader](../../aspose.email.clients.exchange.webservice/iewsclient/removeheader)(string) | Ta bort WebHeader från WebHeaderCollection i EWS-begäran. |
| [Reply](../../aspose.email.clients.exchange.webservice/iewsclient/reply)(MailMessage, ExchangeMessageInfo) | Svara på avsändarens meddelande. |
| [ReplyAll](../../aspose.email.clients.exchange.webservice/iewsclient/replyall)(MailMessage, ExchangeMessageInfo) | Svara avsändaren och alla mottagare av ett meddelande. |
| [ResetImpersonation](../../aspose.email.clients.exchange.webservice/iewsclient/resetimpersonation)() | Återställer identiteten. |
| [ResetSubscription](../../aspose.email.clients.exchange.webservice/iewsclient/resetsubscription)() | Återställ alla prenumerationer |
| [ResolveContact](../../aspose.email.clients.exchange.webservice/iewsclient/resolvecontact)(string) | Löser tvetydiga postlådenamn. |
| [ResolveContacts](../../aspose.email.clients.exchange.webservice/iewsclient/resolvecontacts#resolvecontacts)(string) | Löser tvetydiga postlådevisningsnamn. Obs: det maximala antalet returnerade kontakter är 100. Detta är en begränsning av använda utbyteskommando. |
| [ResolveContacts](../../aspose.email.clients.exchange.webservice/iewsclient/resolvecontacts#resolvecontacts_1)(string, ExchangeListContactsOptions) | Löser tvetydiga e-postadresser och visningsnamn Obs: det maximala antalet returnerade kontakter är 100. Detta är en begränsning av använd EWS-drift. |
| [Restore](../../aspose.email.clients.exchange.webservice/iewsclient/restore)(PersonalStorage, RestoreSettings) | Återställer de angivna utbytesmapparna från den givna personliga lagringen. |
| [SaveMessage](../../aspose.email.clients.exchange.webservice/iewsclient/savemessage#savemessage)(string, Stream) | Sparar meddelandet. |
| [SaveMessage](../../aspose.email.clients.exchange.webservice/iewsclient/savemessage#savemessage_1)(string, string) | Sparar meddelandet. |
| [Send](../../aspose.email.clients.exchange.webservice/iewsclient/send#send)(MailMessage) | Skickar det angivna meddelandet. |
| [Send](../../aspose.email.clients.exchange.webservice/iewsclient/send#send_1)(MailMessage, FollowUpOptions) | Skickar meddelandet. |
| [Send](../../aspose.email.clients.exchange.webservice/iewsclient/send#send_2)(string, string, string, string) | Skickar det angivna meddelandet |
| [SetConversationReadState](../../aspose.email.clients.exchange.webservice/iewsclient/setconversationreadstate#setconversationreadstate)(string, bool) | Ställ in lässtatus för konversationsobjekten till det angivna värdet |
| [SetConversationReadState](../../aspose.email.clients.exchange.webservice/iewsclient/setconversationreadstate#setconversationreadstate_1)(string, string, bool) | Ställ in lässtatus för konversationsobjekten, som finns i den angivna mappen, till det angivna värdet |
| [SetReadFlag](../../aspose.email.clients.exchange.webservice/iewsclient/setreadflag#setreadflag)(string) | Ställer in läsflaggan. |
| [SetReadFlag](../../aspose.email.clients.exchange.webservice/iewsclient/setreadflag#setreadflag_1)(string, bool) | Markerar det angivna meddelandet som läst. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_1)(string) | Hämtar ändringar av objekt och undermappar i en angiven mapp. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder)(SyncState) | Hämtar ändringar av objekten i en angiven mapp. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_3)(string, string) | Hämtar ändringar av objekten i en angiven mapp. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_2)(string, SyncFolderType) | Hämtar ändringar av objekt och undermappar i en angiven mapp. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_4)(string, string, IEnumerable&lt;string&gt;) | Hämtar ändringar av objekten i en angiven mapp. |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment)(Appointment) | Uppdaterar möte. |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment_2)(MapiCalendar) | Uppdaterar möte. |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment_1)(Appointment, string) | Uppdaterar möte. |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment_3)(MapiCalendar, string) | Uppdaterar möte. |
| [UpdateContact](../../aspose.email.clients.exchange.webservice/iewsclient/updatecontact#updatecontact_1)(Contact) | Uppdaterar ett kontaktobjekt i Exchange-butiken. |
| [UpdateContact](../../aspose.email.clients.exchange.webservice/iewsclient/updatecontact#updatecontact)(MapiContact) | Uppdaterar ett kontaktobjekt i Exchange-butiken. |
| [UpdateDelegate](../../aspose.email.clients.exchange.webservice/iewsclient/updatedelegate)(ExchangeDelegateUser, string) | Uppdaterar inställningarna för delegatanvändare som beviljas åtkomst till den angivna postlådan. |
| [UpdateDelegates](../../aspose.email.clients.exchange.webservice/iewsclient/updatedelegates)(ExchangeDelegateUserCollection, string) | Uppdaterar inställningarna för delegatanvändare som beviljas åtkomst till den angivna postlådan. |
| [UpdateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/updateinboxrule#updateinboxrule)(InboxRule) | Uppdaterar den angivna inkorgsregeln |
| [UpdateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/updateinboxrule#updateinboxrule_1)(InboxRule, string) | Uppdaterar den angivna inkorgsregeln |
| [UpdateItems](../../aspose.email.clients.exchange.webservice/iewsclient/updateitems)(ExchangeStreamedItem[], string) | Uppdaterar de angivna objekten i en brevlåda |
| [UpdateNote](../../aspose.email.clients.exchange.webservice/iewsclient/updatenote#updatenote)(MapiNote) | Uppdaterar den angivna anteckningen. |
| [UpdateNote](../../aspose.email.clients.exchange.webservice/iewsclient/updatenote#updatenote_1)(string, MapiNote) | Uppdaterar den angivna anteckningen. |
| [UpdateNote](../../aspose.email.clients.exchange.webservice/iewsclient/updatenote#updatenote_2)(string, MapiNote, IEnumerable&lt;PropertyDescriptor&gt;) | Uppdaterar den angivna anteckningen. |
| [UpdateSubscription](../../aspose.email.clients.exchange.webservice/iewsclient/updatesubscription)() | Uppdateringar prenumerationer |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_3)(ExchangeTask) | Uppdaterar den angivna uppgiften. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask)(MapiTask) | Uppdaterar den angivna uppgiften. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_4)(ExchangeTask, UpdateTaskOptions) | Uppdaterar den angivna uppgiften. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_1)(string, MapiTask) | Uppdaterar den angivna uppgiften. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_2)(string, MapiTask, IEnumerable&lt;PropertyDescriptor&gt;) | Uppdaterar den angivna uppgiften. |
| [UpdateUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/updateuserconfiguration)(UserConfiguration) | Uppdaterar den angivna användarkonfigurationen |

### Se även

* interface [IExchangeClientBase](../../aspose.email.clients.exchange/iexchangeclientbase)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
