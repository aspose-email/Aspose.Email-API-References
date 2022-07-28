---
title: IEWSClient
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente linterface pour le client Exchange.
type: docs
weight: 3960
url: /fr/net/aspose.email.clients.exchange.webservice/iewsclient/
---
## IEWSClient interface

Représente l'interface pour le client Exchange.

```csharp
public interface IEWSClient : IExchangeClientBase
```

## Propriétés

| Nom | La description |
| --- | --- |
| [CalendarFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/calendarfoldereventfilter) { get; set; } | Spécifie les types d'événements pour le dossier Calendrier |
| [ContactsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/contactsfoldereventfilter) { get; set; } | Spécifie les types d'événements pour le dossier Contacts |
| [CurrentCalendarFolderUri](../../aspose.email.clients.exchange.webservice/iewsclient/currentcalendarfolderuri) { get; set; } | Obtient ou définit le dossier de calendrier actuel uri |
| [DeletedItemsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/deleteditemsfoldereventfilter) { get; set; } | Spécifie les types d'événements pour le dossier DeletedItems |
| [DraftsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/draftsfoldereventfilter) { get; set; } | Spécifie les types d'événements pour le dossier Brouillons |
| [EnableDecompression](../../aspose.email.clients.exchange.webservice/iewsclient/enabledecompression) { get; set; } | Obtient ou définit une valeur qui indique si la décompression est activée |
| [Headers](../../aspose.email.clients.exchange.webservice/iewsclient/headers) { get; } | Obtient un tableau de paires nom-valeur qui sont ajoutées à WebHeaderCollection dans la requête EWS. |
| [InboxFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/inboxfoldereventfilter) { get; set; } | Spécifie les types d'événements pour le dossier Boîte de réception |
| [JournalFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/journalfoldereventfilter) { get; set; } | Spécifie les types d'événements pour le dossier Journal |
| [MailboxInfo](../../aspose.email.clients.exchange.webservice/iewsclient/mailboxinfo) { get; } | Obtient les informations de la boîte aux lettres. |
| [NotesFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/notesfoldereventfilter) { get; set; } | Spécifie les types d'événements pour le dossier Notes |
| [NotificationsCheckInterval](../../aspose.email.clients.exchange.webservice/iewsclient/notificationscheckinterval) { get; set; } | Définit l'intervalle de vérification des notifications |
| [NotificationTimeout](../../aspose.email.clients.exchange.webservice/iewsclient/notificationtimeout) { get; set; } | Définit le délai d'attente pour les notifications du serveur |
| [OutboxFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/outboxfoldereventfilter) { get; set; } | Spécifie les types d'événements pour le dossier Boîte d'envoi |
| [ReconnectCount](../../aspose.email.clients.exchange.webservice/iewsclient/reconnectcount) { get; set; } | Obtient ou définit le nombre de tentatives de reconnexion lors d'interruptions de connexion. |
| [ReturnClientRequestId](../../aspose.email.clients.exchange.webservice/iewsclient/returnclientrequestid) { get; set; } | Obtient ou définit un indicateur pour indiquer si le client exige que le côté serveur renvoie l'ID de la demande. |
| [RootFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/rootfoldereventfilter) { get; set; } | Spécifie les types d'événements pour le dossier racine |
| [SentItemsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/sentitemsfoldereventfilter) { get; set; } | Spécifie les types d'événements pour le dossier SentItems |
| [ServerVersion](../../aspose.email.clients.exchange.webservice/iewsclient/serverversion) { get; } | Obtient les informations sur la version actuelle de MS Exchange. |
| [TasksFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/tasksfoldereventfilter) { get; set; } | Spécifie les types d'événements pour le dossier Tâches |
| [TimezoneId](../../aspose.email.clients.exchange.webservice/iewsclient/timezoneid) { get; set; } | Obtient ou définit l'identifiant de fuseau horaire |
| [UseSlashAsFolderSeparator](../../aspose.email.clients.exchange.webservice/iewsclient/useslashasfolderseparator) { get; set; } | Obtient ou définit la valeur qui détermine si la barre oblique '/' est utilisée comme séparateur de dossier. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddHeader](../../aspose.email.clients.exchange.webservice/iewsclient/addheader)(string, string) | Ajoute le nom et la valeur à WebHeaderCollection dans la requête EWS. |
| [AddToDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/addtodistributionlist)(ExchangeDistributionList, MailAddressCollection) | Ajoute les membres à la liste de distribution. |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage)(MailMessage) | Télécharge le message électronique dans le dossier Boîte de réception |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_1)(MapiMessage) | télécharge le message électronique dans le dossier spécifié |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_2)(MapiMessage, bool) | télécharge le message électronique dans le dossier spécifié |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_3)(string, MailMessage) | télécharge le message électronique dans le dossier spécifié |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_5)(string, MapiMessage, bool) | télécharge le message électronique dans le dossier spécifié |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_1)(IEnumerable&lt;MailMessage&gt;) | télécharge le message électronique dans le dossier spécifié |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages)(params MailMessage[]) | télécharge le message électronique dans le dossier spécifié |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_3)(string, IEnumerable&lt;MailMessage&gt;) | télécharge les messages électroniques dans le dossier spécifié |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_4)(string, IEnumerable&lt;MapiMessage&gt;) | télécharge les messages mapi dans le dossier spécifié |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_2)(string, params MailMessage[]) | télécharge le message électronique dans le dossier spécifié |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem)(string, Appointment) | L'opération ArchiveItem déplace un élément dans la boîte aux lettres d'archivage de l'utilisateur de la boîte aux lettres. |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem_1)(string, ExchangeTask) | L'opération ArchiveItem déplace un élément dans la boîte aux lettres d'archivage de l'utilisateur de la boîte aux lettres. |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem_2)(string, MapiMessageItemBase) | L'opération ArchiveItem déplace un élément dans la boîte aux lettres d'archivage de l'utilisateur de la boîte aux lettres. |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem_3)(string, string) | L'opération ArchiveItem déplace un élément dans la boîte aux lettres d'archivage de l'utilisateur de la boîte aux lettres. |
| [Backup](../../aspose.email.clients.exchange.webservice/iewsclient/backup#backup)(ExchangeFolderInfoCollection, Stream, BackupOptions) | Sauvegarde le contenu des dossiers spécifiés |
| [Backup](../../aspose.email.clients.exchange.webservice/iewsclient/backup#backup_1)(ExchangeFolderInfoCollection, string, BackupOptions) | Sauvegarde le contenu des dossiers spécifiés |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment)(Appointment) | Annule le rendez-vous. |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_2)(MapiCalendar) | Annule le rendez-vous. |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_4)(string) | Annule une réunion sortante sur le calendrier d'un organisateur |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_1)(Appointment, string) | Annule le rendez-vous. |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_3)(MapiCalendar, string) | Annule le rendez-vous. |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_5)(string, string) | Annule une réunion sortante sur le calendrier d'un organisateur |
| [CheckUserAvailability](../../aspose.email.clients.exchange.webservice/iewsclient/checkuseravailability#checkuseravailability)(string, DateRange) | Vérifie la disponibilité de l'utilisateur dans la fenêtre de temps spécifiée. |
| [CheckUserAvailability](../../aspose.email.clients.exchange.webservice/iewsclient/checkuseravailability#checkuseravailability_1)(StringCollection, DateRange) | Vérifie la disponibilité des utilisateurs dans la fenêtre de temps spécifiée. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess_1)(ExchangeDelegateUser, string) | Ferme l'accès à la boîte aux lettres spécifiée pour l'utilisateur spécifié. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess_2)(ExchangeDelegateUserCollection, string) | Ferme l'accès à la boîte aux lettres spécifiée pour l'utilisateur spécifié. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess)(ExchangeFolderUserInfo, string) | Ferme l'accès à la boîte aux lettres spécifiée pour l'utilisateur spécifié. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess_3)(string, string) | Ferme l'accès à la boîte aux lettres spécifiée pour l'utilisateur spécifié. |
| [CopyConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/copyconversationitems#copyconversationitems)(string, string) | Copie les éléments de conversation dans le dossier cible spécifié |
| [CopyConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/copyconversationitems#copyconversationitems_1)(string, string, string) | Copie les éléments de conversation, qui se trouvent dans le dossier spécifié, dans le dossier cible spécifié |
| [CopyItem](../../aspose.email.clients.exchange.webservice/iewsclient/copyitem)(string, string) | Copie l'élément dans le dossier spécifié |
| [CreateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/createappointment#createappointment)(Appointment) | Crée un rendez-vous. |
| [CreateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/createappointment#createappointment_1)(Appointment, string) | Crée un rendez-vous. |
| [CreateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/createappointment#createappointment_4)(MapiCalendar, string, bool) | Crée un rendez-vous. |
| [CreateCalendarSharingInvitationMessage](../../aspose.email.clients.exchange.webservice/iewsclient/createcalendarsharinginvitationmessage)(string) | Créer un message d'invitation au partage d'agenda. |
| [CreateContact](../../aspose.email.clients.exchange.webservice/iewsclient/createcontact#createcontact_1)(Contact) | Crée un élément de contact dans la boutique Exchange. |
| [CreateContact](../../aspose.email.clients.exchange.webservice/iewsclient/createcontact#createcontact_3)(string, Contact) | Crée un élément de contact dans le dossier spécifié. |
| [CreateDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/createdistributionlist)(ExchangeDistributionList, MailAddressCollection) | Crée la liste de distribution privée. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder)(string) | Crée un nouveau dossier dans le dossier racine. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_1)(string, ExchangeFolderType) | Crée un nouveau dossier dans le dossier racine. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_2)(string, string) | Crée le nouveau dossier avec le nom spécifié dans le dossier parent spécifié. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_3)(string, string, ExchangeFolderPermissionCollection) | Crée le nouveau dossier |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_5)(string, string, ExchangeFolderType) | Crée le nouveau dossier |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_4)(string, string, ExchangeFolderPermissionCollection, string) | Crée le nouveau dossier |
| [CreateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/createinboxrule#createinboxrule)(InboxRule) | Crée la règle de boîte de réception spécifiée |
| [CreateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/createinboxrule#createinboxrule_1)(InboxRule, string) | Crée la règle de boîte de réception spécifiée |
| [CreateItem](../../aspose.email.clients.exchange.webservice/iewsclient/createitem#createitem)(MapiMessageItemBase) | Crée l'élément donné dans le dossier d'éléments par défaut. |
| [CreateItem](../../aspose.email.clients.exchange.webservice/iewsclient/createitem#createitem_1)(string, MapiMessageItemBase) | Crée l'élément donné dans le dossier spécifié. |
| [CreateItems](../../aspose.email.clients.exchange.webservice/iewsclient/createitems)(ExchangeStreamedItem[], string) | Crée les éléments spécifiés dans le dossier spécifié |
| [CreatePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createpublicfolder#createpublicfolder)(string, ExchangeFolderPermissionCollection) | Crée le dossier public spécifié dans le dossier public racine |
| [CreatePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createpublicfolder#createpublicfolder_1)(string, ExchangeFolderPermissionCollection, ExchangeFolderType) | Crée le dossier public spécifié dans le dossier public racine |
| [CreatePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createpublicfolder#createpublicfolder_2)(string, string, ExchangeFolderPermissionCollection) | Crée le dossier public spécifié dans le dossier public racine |
| [CreateTask](../../aspose.email.clients.exchange.webservice/iewsclient/createtask#createtask)(ExchangeTask) | Crée la tâche donnée dans le dossier de tâches par défaut. |
| [CreateTask](../../aspose.email.clients.exchange.webservice/iewsclient/createtask#createtask_2)(string, ExchangeTask) | Crée la tâche donnée dans le dossier spécifié. |
| [CreateUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/createuserconfiguration)(UserConfiguration) | Crée la configuration utilisateur spécifiée |
| [DelegateAccess](../../aspose.email.clients.exchange.webservice/iewsclient/delegateaccess#delegateaccess)(ExchangeDelegateUser, string) | Délègue l'accès à la boîte aux lettres spécifiée à l'utilisateur spécifié. |
| [DelegateAccess](../../aspose.email.clients.exchange.webservice/iewsclient/delegateaccess#delegateaccess_1)(ExchangeDelegateUserCollection, string) | Délègue l'accès à la boîte aux lettres aux utilisateurs spécifiés. |
| [DelegateAccess](../../aspose.email.clients.exchange.webservice/iewsclient/delegateaccess#delegateaccess_2)(string, ExchangeDelegateFolderPermissionLevel, string) | Délègue l'accès à la boîte aux lettres principale à l'utilisateur spécifié. |
| [DeleteConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/deleteconversationitems#deleteconversationitems)(string) | Supprime tous les éléments de la conversation spécifiée |
| [DeleteConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/deleteconversationitems#deleteconversationitems_1)(string, string) | Supprime les éléments de conversation, qui se trouvent dans le dossier spécifié |
| [DeleteDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/deletedistributionlist)(ExchangeDistributionList, bool) | Supprime la liste de distribution. |
| [DeleteFolder](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolder#deletefolder)(string) | Supprime le dossier |
| [DeleteFolder](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolder#deletefolder_1)(string, bool) | Supprime le dossier |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders)(ExchangeFolderInfoCollection) | Supprime les dossiers spécifiés |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders_2)(StringCollection) | Supprime les dossiers spécifiés |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders_1)(ExchangeFolderInfoCollection, bool) | Supprime les dossiers spécifiés |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders_3)(StringCollection, bool) | Supprime le dossier |
| [DeleteFromDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/deletefromdistributionlist)(ExchangeDistributionList, MailAddressCollection) | Supprime les membres de la liste de distribution. |
| [DeleteInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/deleteinboxrule#deleteinboxrule)(string) | Supprime la règle de boîte de réception spécifiée |
| [DeleteInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/deleteinboxrule#deleteinboxrule_1)(string, string) | Supprime la règle de boîte de réception spécifiée |
| [DeleteItem](../../aspose.email.clients.exchange.webservice/iewsclient/deleteitem)(string, DeletionOptions) | Supprime l'élément spécifié |
| [DeleteItems](../../aspose.email.clients.exchange.webservice/iewsclient/deleteitems)(IEnumerable&lt;string&gt;, DeletionOptions) | Supprime les éléments spécifiés |
| [DeleteUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/deleteuserconfiguration)(UserConfigurationName) | Supprime la configuration utilisateur spécifiée |
| [DisconnectPhoneCall](../../aspose.email.clients.exchange.webservice/iewsclient/disconnectphonecall)(string) | Déconnecte un appel téléphonique spécifié par id. |
| [EmptyFolder](../../aspose.email.clients.exchange.webservice/iewsclient/emptyfolder#emptyfolder)(string) | Vide le dossier spécifié. Les sous-dossiers ne seront pas supprimés ; les éléments supprimés seront déplacés dans le dossier DeletedItems |
| [EmptyFolder](../../aspose.email.clients.exchange.webservice/iewsclient/emptyfolder#emptyfolder_1)(string, EmptyFolderOptions) | Vide le dossier spécifié |
| [ExpandDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/expanddistributionlist)(MailAddress) | Développe les membres de la liste de distribution publique. |
| [ExportItems](../../aspose.email.clients.exchange.webservice/iewsclient/exportitems)(params string[]) | Exporte les éléments spécifiés de la boîte aux lettres |
| [FetchAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/fetchappointment#fetchappointment)(string) | Récupérer le rendez-vous spécifié à partir du serveur. |
| [FetchAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/fetchappointment#fetchappointment_1)(string, string) | Récupérer le rendez-vous spécifié à partir du serveur. |
| [FetchAttachment](../../aspose.email.clients.exchange.webservice/iewsclient/fetchattachment)(string) | Récupère la pièce jointe |
| [FetchConversationMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchconversationmessages)(string) | Récupère les messages de conversation spécifiés |
| [FetchDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/fetchdistributionlist)(ExchangeDistributionList) | Récupère les membres de la liste de distribution privée. |
| [FetchItem](../../aspose.email.clients.exchange.webservice/iewsclient/fetchitem#fetchitem)(string) | Récupère l'élément sous[`MapiMessage`](../../aspose.email.mapi/mapimessage) . |
| [FetchItem](../../aspose.email.clients.exchange.webservice/iewsclient/fetchitem#fetchitem_1)(string, IEnumerable&lt;PropertyDescriptor&gt;) | Récupère l'élément sous[`MapiMessage`](../../aspose.email.mapi/mapimessage) . |
| [FetchItems](../../aspose.email.clients.exchange.webservice/iewsclient/fetchitems)(EwsFetchItems) | Récupère les éléments. |
| [FetchMapiCalendar](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapicalendar#fetchmapicalendar)(IEnumerable&lt;string&gt;) | Récupère le tableau de[`MapiCalendar`](../../aspose.email.mapi/mapicalendar) objets. |
| [FetchMapiCalendar](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapicalendar#fetchmapicalendar_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Récupère le tableau de[`MapiCalendar`](../../aspose.email.mapi/mapicalendar) objets. |
| [FetchMapiMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapimessages#fetchmapimessages)(IEnumerable&lt;string&gt;) | Récupère les messages spécifiés |
| [FetchMapiMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapimessages#fetchmapimessages_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Récupère les messages spécifiés |
| [FetchMapiNotes](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapinotes#fetchmapinotes)(IEnumerable&lt;string&gt;) | Récupère le tableau de[`MapiNote`](../../aspose.email.mapi/mapinote) objets. |
| [FetchMapiNotes](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapinotes#fetchmapinotes_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Récupère le tableau de[`MapiNote`](../../aspose.email.mapi/mapinote) objets. |
| [FetchMapiTasks](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapitasks#fetchmapitasks)(IEnumerable&lt;string&gt;) | Récupère le tableau de[`MapiTask`](../../aspose.email.mapi/mapitask) objets. |
| [FetchMapiTasks](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapitasks#fetchmapitasks_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Récupère le tableau de[`MapiTask`](../../aspose.email.mapi/mapitask) objets. |
| [FetchMessage](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessage#fetchmessage)(string) | Récupère le message. |
| [FetchMessage](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessage#fetchmessage_1)(string, IEnumerable&lt;PropertyDescriptor&gt;) | Récupère le message du serveur |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages)(IEnumerable&lt;ExchangeMessageInfo&gt;) | Récupère les messages spécifiés |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages_1)(IEnumerable&lt;string&gt;) | Récupère les messages spécifiés |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages_3)(StringCollection) | Récupère les messages spécifiés |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages_2)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Récupère les messages spécifiés |
| [FetchTask](../../aspose.email.clients.exchange.webservice/iewsclient/fetchtask)(string) | Récupère la tâche spécifiée. |
| [FindConversations](../../aspose.email.clients.exchange.webservice/iewsclient/findconversations)(string) | Trouve les conversations dans le dossier spécifié |
| [FindMessageTrackingReport](../../aspose.email.clients.exchange.webservice/iewsclient/findmessagetrackingreport)(FindMessageTrackingReportOptions) | Recherche les messages qui répondent aux critères spécifiés. |
| [FindPeople](../../aspose.email.clients.exchange.webservice/iewsclient/findpeople#findpeople_1)(string, int) | Rechercher des contacts situés dans la liste d'adresses globale (GAL) sur le serveur. |
| [FindPeople](../../aspose.email.clients.exchange.webservice/iewsclient/findpeople#findpeople)(string, MailQuery, int) | Rechercher les contacts situés dans la boîte aux lettres personnelle de l'utilisateur spécifié sur le serveur. |
| [FolderExists](../../aspose.email.clients.exchange.webservice/iewsclient/folderexists#folderexists)(string, string) | Vérifie si le dossier spécifié existe. |
| [FolderExists](../../aspose.email.clients.exchange.webservice/iewsclient/folderexists#folderexists_1)(string, string, out ExchangeFolderInfo) | Vérifie si le dossier spécifié existe. |
| [Forward](../../aspose.email.clients.exchange.webservice/iewsclient/forward)(MailMessage, ExchangeMessageInfo) | Transférer un message. |
| [GetCallInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getcallinfo)(string) | Récupère les informations d'appel téléphonique par appel id |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact)(ObjectIdentifier) | Récupère les informations de contact selon l'identifiant spécifié. |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact_2)(string) | Récupère les informations de contact selon l'identifiant spécifié. |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact_1)(ObjectIdentifier, ExchangeListContactsOptions) | Récupère les informations de contact selon l'identifiant spécifié. |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact_3)(string, ExchangeListContactsOptions) | Récupère les informations de contact selon l'identifiant spécifié. |
| [GetContacts](../../aspose.email.clients.exchange.webservice/iewsclient/getcontacts#getcontacts)(string) | Répertorie les contacts situés dans le dossier spécifié sur le serveur |
| [GetContacts](../../aspose.email.clients.exchange.webservice/iewsclient/getcontacts#getcontacts_1)(string, ExchangeListContactsOptions) | Répertorie les contacts situés dans le dossier spécifié sur le serveur |
| [GetExchangeType](../../aspose.email.clients.exchange.webservice/iewsclient/getexchangetype)() | Obtient les informations sur la version actuelle de MS Exchange. |
| [GetFolderInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getfolderinfo)(string) | Obtient les informations du dossier |
| [GetFolderPermissions](../../aspose.email.clients.exchange.webservice/iewsclient/getfolderpermissions)(string) | Obtient les autorisations du dossier. |
| [GetInboxRules](../../aspose.email.clients.exchange.webservice/iewsclient/getinboxrules#getinboxrules)() | Obtient les règles de la boîte de réception |
| [GetInboxRules](../../aspose.email.clients.exchange.webservice/iewsclient/getinboxrules#getinboxrules_1)(string) | Obtient les règles de la boîte de réception |
| [GetMailboxes](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxes)() | Répertorie les boîtes aux lettres ayant des adresses smtp. Remarque : le nombre maximum de contacts renvoyés est de 100. Il s'agit d'une restriction de l'opération EWS utilisée. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxinfo#getmailboxinfo)() | Obtient les informations de la boîte aux lettres. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxinfo#getmailboxinfo_1)(string) | Obtient les informations de la boîte aux lettres |
| [GetMailboxSize](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxsize)() | Obtient la taille de la boîte aux lettres. Veuillez noter que cette opération est effectuée de manière récursive pour tous les sous-dossiers et prend du temps |
| [GetMailboxSizeEx](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxsizeex)(string) | Obtient la taille de la boîte aux lettres Veuillez noter que cette opération est effectuée de manière récursive pour tous les sous-dossiers et prend un certain temps |
| [GetMailTips](../../aspose.email.clients.exchange.webservice/iewsclient/getmailtips)(GetMailTipsOptions) | Obtient des conseils de messagerie |
| [GetMessageTrackingReport](../../aspose.email.clients.exchange.webservice/iewsclient/getmessagetrackingreport)(GetMessageTrackingReportOptions) | Obtient le rapport de suivi des messages |
| [GetServerTimeZoneIds](../../aspose.email.clients.exchange.webservice/iewsclient/getservertimezoneids#getservertimezoneids)() | Le GetServerTimeZoneIds renvoie des informations à partir de l'ID de fuseau horaire qui sont disponibles sur un serveur Exchange. |
| [GetServerTimeZoneIds](../../aspose.email.clients.exchange.webservice/iewsclient/getservertimezoneids#getservertimezoneids_1)(IEnumerable&lt;string&gt;) | Le GetServerTimeZoneIds renvoie des informations à partir de l'ID de fuseau horaire qui sont disponibles sur un serveur Exchange. |
| [GetServerTimeZoneIds](../../aspose.email.clients.exchange.webservice/iewsclient/getservertimezoneids#getservertimezoneids_2)(params string[]) | Le GetServerTimeZoneIds renvoie des informations à partir de l'ID de fuseau horaire qui sont disponibles sur un serveur Exchange. |
| [GetUMConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/getumconfiguration)() | Récupère la configuration de messagerie unifiée |
| [GetUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/getuserconfiguration)(UserConfigurationName) | Obtient la configuration utilisateur spécifiée |
| [GetVersionInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getversioninfo)() | Renvoie la version du serveur Exchange info |
| [ImpersonateUser](../../aspose.email.clients.exchange.webservice/iewsclient/impersonateuser)(ItemChoice, string) | Emprunte l'identité de l'utilisateur. |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments)() | Récupère la liste des rendez-vous pour le dossier de calendrier par défaut |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_3)(bool) | Récupère la liste des rendez-vous pour le dossier de calendrier par défaut |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_1)(MailQuery) | Récupère la liste des rendez-vous pour le dossier de calendrier par défaut |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_4)(string) | Récupère la liste des rendez-vous pour le dossier de calendrier spécifié |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_2)(MailQuery, bool) | Récupère la liste des rendez-vous pour le dossier de calendrier par défaut |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_7)(string, bool) | Récupère la liste des rendez-vous pour le dossier de calendrier spécifié |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_5)(string, MailQuery) | Récupère la liste des rendez-vous pour le dossier de calendrier spécifié |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_6)(string, MailQuery, bool) | Récupère la liste des rendez-vous pour le dossier de calendrier spécifié |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_2)(int) | Récupère la page avec les rendez-vous pour le dossier de calendrier |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_3)(int, int) | Récupère la page avec les rendez-vous pour le dossier de calendrier |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage)(MailQuery, int) | Récupère la page avec les rendez-vous pour le dossier de calendrier |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_6)(string, int) | Récupère la page avec les rendez-vous pour le dossier de calendrier spécifié |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_1)(MailQuery, int, int) | Récupère la page avec les rendez-vous pour le dossier de calendrier |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_7)(string, int, int) | Récupère la page avec les rendez-vous pour le dossier de calendrier spécifié |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_4)(string, MailQuery, int) | Récupère la page avec les rendez-vous pour le dossier de calendrier spécifié |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_5)(string, MailQuery, int, int) | Récupère la page avec les rendez-vous pour le dossier de calendrier spécifié |
| [ListContacts](../../aspose.email.clients.exchange.webservice/iewsclient/listcontacts#listcontacts)(string) | Répertorie les contacts situés dans le dossier spécifié sur le serveur |
| [ListContacts](../../aspose.email.clients.exchange.webservice/iewsclient/listcontacts#listcontacts_1)(string, IEnumerable&lt;PropertyDescriptor&gt;) | Répertorie les contacts situés dans le dossier spécifié sur le serveur |
| [ListDelegates](../../aspose.email.clients.exchange.webservice/iewsclient/listdelegates)(string) | Répertorie les utilisateurs autorisés à accéder à la boîte aux lettres spécifiée. |
| [ListDistributionLists](../../aspose.email.clients.exchange.webservice/iewsclient/listdistributionlists)() | Lister les listes de distribution privées. |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems)(string) | Récupérer la liste des uries d'éléments dans le dossier spécifié |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_1)(string, MailQuery) | Récupérer la liste des uries d'éléments dans le dossier spécifié |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_3)(string, string) | Récupérer la liste des uries d'éléments dans le dossier spécifié |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_2)(string, MailQuery, bool) | Récupérer la liste des uries d'éléments dans le dossier spécifié |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_4)(string, string, MailQuery) | Récupérer la liste des uries d'éléments dans le dossier spécifié |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_5)(string, string, MailQuery, bool) | Récupérer la liste des uries d'éléments dans le dossier spécifié |
| [ListMailboxes](../../aspose.email.clients.exchange.webservice/iewsclient/listmailboxes#listmailboxes)() | Répertorie les boîtes aux lettres. |
| [ListMailboxes](../../aspose.email.clients.exchange.webservice/iewsclient/listmailboxes#listmailboxes_1)(string) | Veuillez prêter votre attention, cette méthode remplacée fonctionne avec Exchange Server 2013 et supérieur. Répertorie les boîtes aux lettres. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages)() | Répertorier les messages dans le dossier de la boîte de réception. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_1)(IEnumerable&lt;string&gt;) | Liste les messages dans le dossier spécifié. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_2)(string) | Liste les messages. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_7)(string, bool) | Lister les messages dans le dossier spécifié |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_3)(string, ExchangeListMessagesOptions) | Liste les messages. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_8)(string, int) | Liste les messages. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_5)(string, MailQuery) | Liste les messages dans le dossier spécifié. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_4)(string, ExchangeListMessagesOptions, IEnumerable&lt;PropertyDescriptor&gt;) | Lister les messages dans le dossier spécifié |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_9)(string, int, ExchangeListMessagesOptions) | Liste les messages. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_10)(string, int, MailQuery) | Liste les messages dans le dossier spécifié. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_6)(string, MailQuery, bool) | Liste les messages dans le dossier spécifié. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_13)(string, string, bool) | Lister les messages dans le dossier spécifié |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_12)(string, string, MailQuery) | Liste les messages dans le dossier spécifié. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_11)(string, int, MailQuery, bool) | Liste les messages dans le dossier spécifié. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_4)(string, int) | Liste les messages dans le dossier spécifié. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage)(string, PageInfo) | Liste les messages dans le dossier spécifié. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_5)(string, int, int) | Liste les messages dans le dossier spécifié. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_2)(string, MailQuery, int) | Liste les messages dans le dossier spécifié. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_1)(string, PageInfo, ExchangeListMessagesOptions) | Liste les messages dans le dossier spécifié. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_6)(string, int, int, ExchangeListMessagesOptions) | Liste les messages dans le dossier spécifié. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_3)(string, MailQuery, int, int) | Liste les messages dans le dossier spécifié. |
| [ListMessagesFromPublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesfrompublicfolder#listmessagesfrompublicfolder)(ExchangeFolderInfo) | Obtenir la collection de messages du dossier public |
| [ListMessagesFromPublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesfrompublicfolder#listmessagesfrompublicfolder_1)(string) | Obtenir la collection de messages du dossier public |
| [ListPublicFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listpublicfolders)() | Obtient une collection de dossiers publics à partir du dossier public racine |
| [ListSubFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfolders#listsubfolders)(ExchangeFolderInfo) | Obtient la collection de dossiers publics enfants du parent |
| [ListSubFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfolders#listsubfolders_1)(string) | Obtient la collection de dossiers enfants du parent |
| [ListSubFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfolders#listsubfolders_2)(string, string) | Obtient la collection de dossiers enfants du parent |
| [ListSubFoldersByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage#listsubfoldersbypage_1)(string, int) | Recherche le dossier spécifié dans le dossier parent donné avec paging La méthode prend en charge la pagination. Appelle pour la première fois dans le cycle de pagination. |
| [ListSubFoldersByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage#listsubfoldersbypage)(string, PageInfo) | Recherche le dossier spécifié dans le dossier parent donné avec la pagination La méthode prend en charge la pagination. |
| [ListSubFoldersByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage#listsubfoldersbypage_2)(string, int, int) | Recherche le dossier spécifié dans le dossier parent donné avec la pagination La méthode prend en charge la pagination. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks)() | Récupère les listes de tâches d'échange pour le dossier par défaut. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_1)(string) | Récupère les listes des tâches d'échange. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_3)(string, int) | Récupère les listes des tâches d'échange. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_2)(string, MailQuery) | Récupère les listes des tâches d'échange. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_4)(string, int, MailQuery) | Récupère les listes des tâches d'échange. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_5)(string, int, MailQuery, bool) | Récupère les listes des tâches d'échange. |
| [LoadContactPhoto](../../aspose.email.clients.exchange.webservice/iewsclient/loadcontactphoto)(ContactPhoto) | Charge les données binaires de la photo de contact |
| [MailDisablePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/maildisablepublicfolder)(string) | Désactiver la messagerie d'un dossier public |
| [MailEnablePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/mailenablepublicfolder)(string) | Activer la messagerie pour un dossier public |
| [MarkAllItems](../../aspose.email.clients.exchange.webservice/iewsclient/markallitems#markallitems_2)(bool, params string[]) | Marque tous les éléments dans les dossiers spécifiés. |
| [MarkAllItems](../../aspose.email.clients.exchange.webservice/iewsclient/markallitems#markallitems)(bool, bool, IEnumerable&lt;string&gt;) | Marque tous les éléments dans les dossiers spécifiés. |
| [MarkAllItems](../../aspose.email.clients.exchange.webservice/iewsclient/markallitems#markallitems_1)(bool, bool, params string[]) | Marque tous les éléments dans les dossiers spécifiés. |
| [MarkAllItemsAsRead](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasread#markallitemsasread)() | Marque tous les éléments du dossier de la boîte de réception comme lus sans reçus. |
| [MarkAllItemsAsRead](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasread#markallitemsasread_1)(IEnumerable&lt;string&gt;) | Marque tous les éléments des dossiers spécifiés comme lus sans reçus. |
| [MarkAllItemsAsRead](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasread#markallitemsasread_2)(params string[]) | Marque tous les éléments des dossiers spécifiés comme lus sans reçus. |
| [MarkAllItemsAsUnread](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasunread#markallitemsasunread)() | Marque tous les éléments du dossier de la boîte de réception comme non lus. |
| [MarkAllItemsAsUnread](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasunread#markallitemsasunread_1)(IEnumerable&lt;string&gt;) | Marque tous les éléments des dossiers spécifiés comme non lus. |
| [MarkAllItemsAsUnread](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasunread#markallitemsasunread_2)(params string[]) | Marque tous les éléments des dossiers spécifiés comme non lus. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_2)(bool, IEnumerable&lt;string&gt;) | La méthode MarkAsJunk déplace les messages électroniques vers le dossier de courrier indésirable et bloque l'expéditeur du message. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_3)(bool, params string[]) | La méthode MarkAsJunk déplace les messages électroniques vers le dossier de courrier indésirable et bloque l'expéditeur du message. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk)(bool, bool, IEnumerable&lt;string&gt;) | La méthode MarkAsJunk déplace les messages électroniques vers le dossier de courrier indésirable et bloque l'expéditeur du message. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_1)(bool, bool, params string[]) | La méthode MarkAsJunk déplace les messages électroniques vers le dossier de courrier indésirable et bloque l'expéditeur du message. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_4)(bool, bool, IEnumerable&lt;string&gt;, out string[], out string[], out string[]) | La méthode MarkAsJunk déplace les messages électroniques vers le dossier de courrier indésirable et bloque l'expéditeur du message. |
| [MoveConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/moveconversationitems#moveconversationitems)(string, string) | Déplace les éléments de conversation dans le dossier cible spécifié |
| [MoveConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/moveconversationitems#moveconversationitems_1)(string, string, string) | Déplace les éléments de conversation, qui se trouvent dans le dossier spécifié, dans le dossier cible spécifié |
| [MoveItem](../../aspose.email.clients.exchange.webservice/iewsclient/moveitem)(string, string) | Déplace l'élément vers le dossier spécifié |
| [PlayOnPhone](../../aspose.email.clients.exchange.webservice/iewsclient/playonphone)(string, string) | L'opération PlayOnPhone initie un appel sortant et lit un message par téléphone. |
| [RemoveHeader](../../aspose.email.clients.exchange.webservice/iewsclient/removeheader)(string) | Supprimer WebHeader de WebHeaderCollection dans la demande EWS. |
| [Reply](../../aspose.email.clients.exchange.webservice/iewsclient/reply)(MailMessage, ExchangeMessageInfo) | Répondre au message de l'expéditeur. |
| [ReplyAll](../../aspose.email.clients.exchange.webservice/iewsclient/replyall)(MailMessage, ExchangeMessageInfo) | Répondre à l'expéditeur et à tous les destinataires d'un message. |
| [ResetImpersonation](../../aspose.email.clients.exchange.webservice/iewsclient/resetimpersonation)() | Réinitialise l'usurpation d'identité. |
| [ResetSubscription](../../aspose.email.clients.exchange.webservice/iewsclient/resetsubscription)() | Réinitialiser tous les abonnements |
| [ResolveContact](../../aspose.email.clients.exchange.webservice/iewsclient/resolvecontact)(string) | Résout les noms de boîtes aux lettres ambigus. |
| [ResolveContacts](../../aspose.email.clients.exchange.webservice/iewsclient/resolvecontacts#resolvecontacts)(string) | Résout les noms d'affichage de boîte aux lettres ambigus. Remarque : le nombre maximal de contacts renvoyés est de 100. Il s'agit d'une restriction de la commande d'échange utilisée. |
| [ResolveContacts](../../aspose.email.clients.exchange.webservice/iewsclient/resolvecontacts#resolvecontacts_1)(string, ExchangeListContactsOptions) | Résout les adresses e-mail et les noms d'affichage ambigus Remarque : le nombre maximal de contacts renvoyés est de 100. Il s'agit d'une restriction de l'opération EWS utilisée. |
| [Restore](../../aspose.email.clients.exchange.webservice/iewsclient/restore)(PersonalStorage, RestoreSettings) | Restaure les dossiers d'échange spécifiés à partir du stockage personnel donné. |
| [SaveMessage](../../aspose.email.clients.exchange.webservice/iewsclient/savemessage#savemessage)(string, Stream) | Enregistre le message. |
| [SaveMessage](../../aspose.email.clients.exchange.webservice/iewsclient/savemessage#savemessage_1)(string, string) | Enregistre le message. |
| [Send](../../aspose.email.clients.exchange.webservice/iewsclient/send#send)(MailMessage) | Envoie le message spécifié. |
| [Send](../../aspose.email.clients.exchange.webservice/iewsclient/send#send_1)(MailMessage, FollowUpOptions) | Envoie le message. |
| [Send](../../aspose.email.clients.exchange.webservice/iewsclient/send#send_2)(string, string, string, string) | Envoie le message spécifié |
| [SetConversationReadState](../../aspose.email.clients.exchange.webservice/iewsclient/setconversationreadstate#setconversationreadstate)(string, bool) | Définir l'état de lecture des éléments de conversation sur la valeur spécifiée |
| [SetConversationReadState](../../aspose.email.clients.exchange.webservice/iewsclient/setconversationreadstate#setconversationreadstate_1)(string, string, bool) | Définir l'état de lecture des éléments de conversation, qui se trouvent dans le dossier spécifié, sur la valeur spécifiée |
| [SetReadFlag](../../aspose.email.clients.exchange.webservice/iewsclient/setreadflag#setreadflag)(string) | Définit le drapeau de lecture. |
| [SetReadFlag](../../aspose.email.clients.exchange.webservice/iewsclient/setreadflag#setreadflag_1)(string, bool) | Marque le message spécifié comme lu. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_1)(string) | Récupère les modifications des éléments et des sous-dossiers dans un dossier spécifié. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder)(SyncState) | Récupère les modifications des éléments dans un dossier spécifié. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_3)(string, string) | Récupère les modifications des éléments dans un dossier spécifié. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_2)(string, SyncFolderType) | Récupère les modifications des éléments et des sous-dossiers dans un dossier spécifié. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_4)(string, string, IEnumerable&lt;string&gt;) | Récupère les modifications des éléments dans un dossier spécifié. |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment)(Appointment) | Mise à jour du rendez-vous. |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment_2)(MapiCalendar) | Mise à jour du rendez-vous. |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment_1)(Appointment, string) | Mise à jour du rendez-vous. |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment_3)(MapiCalendar, string) | Mise à jour du rendez-vous. |
| [UpdateContact](../../aspose.email.clients.exchange.webservice/iewsclient/updatecontact#updatecontact_1)(Contact) | Met à jour un élément de contact dans la boutique Exchange. |
| [UpdateContact](../../aspose.email.clients.exchange.webservice/iewsclient/updatecontact#updatecontact)(MapiContact) | Met à jour un élément de contact dans la boutique Exchange. |
| [UpdateDelegate](../../aspose.email.clients.exchange.webservice/iewsclient/updatedelegate)(ExchangeDelegateUser, string) | Met à jour les paramètres de l'utilisateur délégué qui est autorisé à accéder à la boîte aux lettres spécifiée. |
| [UpdateDelegates](../../aspose.email.clients.exchange.webservice/iewsclient/updatedelegates)(ExchangeDelegateUserCollection, string) | Met à jour les paramètres des utilisateurs délégués qui ont accès à la boîte aux lettres spécifiée. |
| [UpdateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/updateinboxrule#updateinboxrule)(InboxRule) | Met à jour la règle de boîte de réception spécifiée |
| [UpdateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/updateinboxrule#updateinboxrule_1)(InboxRule, string) | Met à jour la règle de boîte de réception spécifiée |
| [UpdateItems](../../aspose.email.clients.exchange.webservice/iewsclient/updateitems)(ExchangeStreamedItem[], string) | Met à jour les éléments spécifiés dans une boîte aux lettres |
| [UpdateNote](../../aspose.email.clients.exchange.webservice/iewsclient/updatenote#updatenote)(MapiNote) | Met à jour la note spécifiée. |
| [UpdateNote](../../aspose.email.clients.exchange.webservice/iewsclient/updatenote#updatenote_1)(string, MapiNote) | Met à jour la note spécifiée. |
| [UpdateNote](../../aspose.email.clients.exchange.webservice/iewsclient/updatenote#updatenote_2)(string, MapiNote, IEnumerable&lt;PropertyDescriptor&gt;) | Met à jour la note spécifiée. |
| [UpdateSubscription](../../aspose.email.clients.exchange.webservice/iewsclient/updatesubscription)() | Met à jour les abonnements |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_3)(ExchangeTask) | Met à jour la tâche spécifiée. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask)(MapiTask) | Met à jour la tâche spécifiée. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_4)(ExchangeTask, UpdateTaskOptions) | Met à jour la tâche spécifiée. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_1)(string, MapiTask) | Met à jour la tâche spécifiée. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_2)(string, MapiTask, IEnumerable&lt;PropertyDescriptor&gt;) | Met à jour la tâche spécifiée. |
| [UpdateUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/updateuserconfiguration)(UserConfiguration) | Met à jour la configuration utilisateur spécifiée |

### Voir également

* interface [IExchangeClientBase](../../aspose.email.clients.exchange/iexchangeclientbase)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
