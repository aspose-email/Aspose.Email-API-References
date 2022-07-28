---
title: IAsyncEwsClient
second_title: Aspose.Email för .NET API-referens
description: Representerar det asynkroniserade gränssnittet för Exchange-klienten.
type: docs
weight: 3950
url: /sv/net/aspose.email.clients.exchange.webservice/iasyncewsclient/
---
## IAsyncEwsClient interface

Representerar det asynkroniserade gränssnittet för Exchange-klienten.

```csharp
public interface IAsyncEwsClient : IExchangeClientBase
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [MailboxInfo](../../aspose.email.clients.exchange.webservice/iasyncewsclient/mailboxinfo) { get; } | Hämtar brevlådeinformationen. |
| [UseSlashAsFolderSeparator](../../aspose.email.clients.exchange.webservice/iasyncewsclient/useslashasfolderseparator) { get; set; } | Hämtar eller ställer in värde som avgör om snedstrecket '/' används som mappavgränsare. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AppendMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/appendmessagesasync)(EwsAppendMessage) | Laddar upp e-postmeddelanden till den angivna mappen. |
| [ArchiveItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/archiveitemsasync)(EwsArchiveItems) | Operationen ArchiveItem flyttar ett objekt till brevlådeanvändarens arkivpostlåda. |
| [BackupAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/backupasync#backupasync)(ExchangeFolderInfoCollection, Stream, BackupOptions, CancellationToken) | Säkerhetskopierar innehållet i de angivna mapparna. |
| [BackupAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/backupasync#backupasync_1)(ExchangeFolderInfoCollection, string, BackupOptions, CancellationToken) | Säkerhetskopierar innehållet i de angivna mapparna. |
| [CancelAppointmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/cancelappointmentasync)(string, string, CancellationToken) | Avbryter ett spännande möte på en arrangörskalender |
| [CopyConversationItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/copyconversationitemsasync)(string, string, string, CancellationToken) | Kopierar konversationsobjekten, som finns i den angivna mappen, till den angivna målmappen |
| [CopyItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/copyitemasync)(string, string, CancellationToken) | Kopierar objektet till angiven folder |
| [CreateAppointmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createappointmentasync)(Appointment, string, CancellationToken) | Skapar möte. |
| [CreateFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createfolderasync)(string, string, ExchangeFolderPermissionCollection, string, CancellationToken) | Skapar den nya mappen |
| [CreateItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createitemasync)(MapiMessageItemBase, string, CancellationToken) | Skapar det givna objektet i den angivna mappen. |
| [CreateItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createitemsasync)(IEnumerable&lt;ExchangeStreamedItem&gt;, string, CancellationToken) | Skapar de angivna objekten i den angivna mappen |
| [CreatePublicFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createpublicfolderasync#createpublicfolderasync_1)(string, ExchangeFolderPermissionCollection, string, CancellationToken) | Skapar den angivna offentliga mappen i den offentliga rotmappen |
| [CreatePublicFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createpublicfolderasync#createpublicfolderasync)(string, ExchangeFolderPermissionCollection, ExchangeFolderType, string, CancellationToken) | Skapar den angivna offentliga mappen i den offentliga rotmappen |
| [CreateTaskAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createtaskasync)(ExchangeTask, string, CancellationToken) | Skapar den givna uppgiften i den angivna mappen. |
| [DeleteConversationItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deleteconversationitemsasync)(string, string, CancellationToken) | Tar bort konversationsobjekten som finns i den angivna mappen |
| [DeleteFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deletefolderasync)(string, bool, CancellationToken) | Tar bort mappen |
| [DeleteFoldersAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deletefoldersasync)(IEnumerable&lt;string&gt;, bool, CancellationToken) | Tar bort mapparna |
| [DeleteItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deleteitemasync)(string, DeletionOptions, CancellationToken) | Tar bort specificerad item |
| [DeleteItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deleteitemsasync)(IEnumerable&lt;string&gt;, DeletionOptions, CancellationToken) | Tar bort specificerade objekt |
| [EmptyFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/emptyfolderasync)(string, EmptyFolderOptions, CancellationToken) | Tömmer den angivna mappen |
| [ExportItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/exportitemsasync)(IEnumerable&lt;string&gt;, CancellationToken) | Exporterar de angivna objekten från mailbox |
| [FetchAppointmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchappointmentasync)(string, string, CancellationToken) | Hämta det angivna mötet från servern. |
| [FetchAttachmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchattachmentasync)(string, CancellationToken) | Hämtar bilagan |
| [FetchConversationMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchconversationmessagesasync)(string, CancellationToken) | Hämtar de angivna konversationsmeddelandena |
| [FetchItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchitemasync)(string, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Hämtar hela objektet med bilagor. |
| [FetchItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchitemsasync)(EwsFetchItems) | Hämtar de angivna objekten. |
| [FetchMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchmessagesasync)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Hämtar de angivna meddelandena. |
| [FetchTaskAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchtaskasync)(string, CancellationToken) | Hämtar den angivna uppgiften. |
| [FindConversationsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/findconversationsasync)(string, CancellationToken) | Hittar konversationer i den angivna mappen |
| [FindPeopleAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/findpeopleasync)(EwsFindPeople) | Hitta kontakter. |
| [FolderExistsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/folderexistsasync)(string, string, CancellationToken) | Kontrollerar om den angivna mappen finns. |
| [GetContactAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getcontactasync)(string, ExchangeListContactsOptions, CancellationToken) | Hämtar kontaktinformation enligt specificerad identifierare. |
| [GetContactsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getcontactsasync)(string, ExchangeListContactsOptions, CancellationToken) | Listar kontakter som finns i den angivna mappen på server |
| [GetFolderInfoAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getfolderinfoasync)(string, CancellationToken) | Hämtar mappinformationen |
| [GetFolderPermissionsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getfolderpermissionsasync)(string, CancellationToken) | Får mappbehörigheterna. |
| [GetMailboxesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getmailboxesasync)(CancellationToken) | Listar postlådor med smtp-adresser. Obs: det maximala antalet returnerade kontakter är 100. Detta är en begränsning av använd EWS-drift. |
| [GetMailboxInfoAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getmailboxinfoasync)(string, CancellationToken) | Hämtar brevlådeinformationen |
| [GetServerTimeZoneIdsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getservertimezoneidsasync)(IEnumerable&lt;string&gt;, CancellationToken) | GetServerTimeZoneIds returnerar information från tidszons-id som är tillgängligt på en Exchange-server. |
| [GetTimezoneIdAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/gettimezoneidasync)(CancellationToken) | Får tidszon-id. |
| [ListAppointmentsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listappointmentsasync)(string, MailQuery, bool, CancellationToken) | Hämtar lista över möten för specificerad kalendermapp |
| [ListAppointmentsByPageAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listappointmentsbypageasync)(string, MailQuery, int, int, CancellationToken) | Hämtar sida med möten för angiven kalendermapp |
| [ListContactsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listcontactsasync)(string, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Listar kontakter som finns i den angivna mappen på servern. |
| [ListItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listitemsasync)(string, string, MailQuery, bool, CancellationToken) | Hämta lista över objekt-URIer i angiven folder |
| [ListMailboxesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmailboxesasync)(string, CancellationToken) | Listar postlådor med smtp-adresser. Obs: det maximala antalet returnerade kontakter är 100. Detta är en begränsning av använd EWS-drift. |
| [ListMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesasync#listmessagesasync)(IEnumerable&lt;string&gt;, CancellationToken) | Lista meddelandena i den angivna mappen. |
| [ListMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesasync#listmessagesasync_1)(string, string, int, MailQuery, bool, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Lista meddelandena i den angivna mappen. |
| [ListMessagesByPageAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesbypageasync#listmessagesbypageasync)(string, PageInfo, CancellationToken) | Lista meddelandena i den angivna mappen. |
| [ListMessagesByPageAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesbypageasync#listmessagesbypageasync_1)(string, int, int, MailQuery, CancellationToken) | Lista meddelandena i den angivna mappen. |
| [ListPublicFoldersAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listpublicfoldersasync)(CancellationToken) | Hämtar samling av offentliga mappar från den offentliga rotmappen |
| [ListSubFoldersAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listsubfoldersasync)(string, string, CancellationToken) | Hämtar samling av underordnade mappar från parent |
| [ListSubFoldersByPageAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listsubfoldersbypageasync)(string, PageInfo, CancellationToken) | Söker i den angivna mappen i den givna överordnade mappen med paging Metoden stöder personsökning. |
| [ListTasksAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listtasksasync)(string, int, MailQuery, bool, CancellationToken) | Hämtar listor över utbytesuppgifter. |
| [LoadContactPhotoAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/loadcontactphotoasync)(ContactPhoto, CancellationToken) | Laddar kontaktfoto binär data |
| [MailDisablePublicFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/maildisablepublicfolderasync)(string, CancellationToken) | Mail-inaktivera en offentlig mapp |
| [MailEnablePublicFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/mailenablepublicfolderasync)(string, CancellationToken) | Mail-aktivera en offentlig mapp |
| [MarkAllItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/markallitemsasync)(IEnumerable&lt;string&gt;, bool, bool, CancellationToken) | Markerar alla objekt i angivna mappar. |
| [MarkAsJunkAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/markasjunkasync)(IEnumerable&lt;string&gt;, bool, bool, CancellationToken) | MarkAsJunk-metoden flyttar e-postmeddelanden till skräppostmappen och blockerar meddelandeavsändaren. |
| [MoveConversationItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/moveconversationitemsasync)(string, string, string, CancellationToken) | Flyttar konversationsobjekten, som finns i den angivna mappen, till den angivna målmappen |
| [MoveItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/moveitemasync)(string, string, CancellationToken) | Flyttar objektet till angiven folder |
| [ResolveContactsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/resolvecontactsasync)(string, ExchangeListContactsOptions, CancellationToken) | Löser tvetydiga e-postadresser och visningsnamn Obs: det maximala antalet returnerade kontakter är 100. Detta är en begränsning av använd EWS-drift. |
| [ResolveMapiContactsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/resolvemapicontactsasync)(string, CancellationToken) | Löser tvetydiga e-postadresser och visningsnamn Obs: det maximala antalet returnerade kontakter är 100. Detta är en begränsning av använd EWS-drift. |
| [RestoreAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/restoreasync)(PersonalStorage, RestoreSettings, CancellationToken) | Återställer de angivna utbytesmapparna från den givna personliga lagringen. |
| [SendAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/sendasync)(MailMessage, FollowUpOptions, CancellationToken) | Skickar meddelandet. |
| [SetConversationReadStateAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/setconversationreadstateasync)(string, bool, string, CancellationToken) | Ställ in lässtatus för konversationsobjekten, som finns i den angivna mappen, till det angivna värdet |
| [SetReadFlagAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/setreadflagasync)(string, bool, CancellationToken) | Markerar det angivna meddelandet som läst. |
| [SetTimezoneIdAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/settimezoneidasync)(string, CancellationToken) | Ställer in tidszon-id. |
| [SyncFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/syncfolderasync)(SyncState, CancellationToken) | Hämtar ändringar av objekten i en angiven mapp. |
| [UpdateAppointmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updateappointmentasync)(Appointment, string, CancellationToken) | Uppdaterar möte. |
| [UpdateContactAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updatecontactasync)(Contact, CancellationToken) | Uppdaterar ett kontaktobjekt i Exchange-butiken. |
| [UpdateItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updateitemasync)(EwsUpdateItem) | Uppdaterar objektet. |
| [UpdateItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updateitemsasync)(IEnumerable&lt;ExchangeStreamedItem&gt;, CancellationToken) | Uppdaterar de angivna objekten i en postlåda. |
| [UpdateTaskAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updatetaskasync)(ExchangeTask, CancellationToken) | Uppdaterar den angivna uppgiften. |

### Se även

* interface [IExchangeClientBase](../../aspose.email.clients.exchange/iexchangeclientbase)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
