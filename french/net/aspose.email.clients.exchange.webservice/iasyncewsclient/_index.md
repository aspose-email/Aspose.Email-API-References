---
title: IAsyncEwsClient
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente linterface asynchrone pour le client Exchange.
type: docs
weight: 3950
url: /fr/net/aspose.email.clients.exchange.webservice/iasyncewsclient/
---
## IAsyncEwsClient interface

Représente l'interface asynchrone pour le client Exchange.

```csharp
public interface IAsyncEwsClient : IExchangeClientBase
```

## Propriétés

| Nom | La description |
| --- | --- |
| [MailboxInfo](../../aspose.email.clients.exchange.webservice/iasyncewsclient/mailboxinfo) { get; } | Obtient les informations de la boîte aux lettres. |
| [UseSlashAsFolderSeparator](../../aspose.email.clients.exchange.webservice/iasyncewsclient/useslashasfolderseparator) { get; set; } | Obtient ou définit la valeur qui détermine si la barre oblique '/' est utilisée comme séparateur de dossier. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AppendMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/appendmessagesasync)(EwsAppendMessage) | Télécharge les messages électroniques dans le dossier spécifié. |
| [ArchiveItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/archiveitemsasync)(EwsArchiveItems) | L'opération ArchiveItem déplace un élément dans la boîte aux lettres d'archivage de l'utilisateur de la boîte aux lettres. |
| [BackupAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/backupasync#backupasync)(ExchangeFolderInfoCollection, Stream, BackupOptions, CancellationToken) | Sauvegarde le contenu des dossiers spécifiés. |
| [BackupAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/backupasync#backupasync_1)(ExchangeFolderInfoCollection, string, BackupOptions, CancellationToken) | Sauvegarde le contenu des dossiers spécifiés. |
| [CancelAppointmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/cancelappointmentasync)(string, string, CancellationToken) | Annule une réunion sortante sur le calendrier d'un organisateur |
| [CopyConversationItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/copyconversationitemsasync)(string, string, string, CancellationToken) | Copie les éléments de conversation, qui se trouvent dans le dossier spécifié, dans le dossier cible spécifié |
| [CopyItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/copyitemasync)(string, string, CancellationToken) | Copie l'élément dans le dossier spécifié |
| [CreateAppointmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createappointmentasync)(Appointment, string, CancellationToken) | Crée un rendez-vous. |
| [CreateFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createfolderasync)(string, string, ExchangeFolderPermissionCollection, string, CancellationToken) | Crée le nouveau dossier |
| [CreateItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createitemasync)(MapiMessageItemBase, string, CancellationToken) | Crée l'élément donné dans le dossier spécifié. |
| [CreateItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createitemsasync)(IEnumerable&lt;ExchangeStreamedItem&gt;, string, CancellationToken) | Crée les éléments spécifiés dans le dossier spécifié |
| [CreatePublicFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createpublicfolderasync#createpublicfolderasync_1)(string, ExchangeFolderPermissionCollection, string, CancellationToken) | Crée le dossier public spécifié dans le dossier public racine |
| [CreatePublicFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createpublicfolderasync#createpublicfolderasync)(string, ExchangeFolderPermissionCollection, ExchangeFolderType, string, CancellationToken) | Crée le dossier public spécifié dans le dossier public racine |
| [CreateTaskAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/createtaskasync)(ExchangeTask, string, CancellationToken) | Crée la tâche donnée dans le dossier spécifié. |
| [DeleteConversationItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deleteconversationitemsasync)(string, string, CancellationToken) | Supprime les éléments de conversation, qui se trouvent dans le dossier spécifié |
| [DeleteFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deletefolderasync)(string, bool, CancellationToken) | Supprime le dossier |
| [DeleteFoldersAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deletefoldersasync)(IEnumerable&lt;string&gt;, bool, CancellationToken) | Supprime les dossiers |
| [DeleteItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deleteitemasync)(string, DeletionOptions, CancellationToken) | Supprime l'élément spécifié |
| [DeleteItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/deleteitemsasync)(IEnumerable&lt;string&gt;, DeletionOptions, CancellationToken) | Supprime les éléments spécifiés |
| [EmptyFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/emptyfolderasync)(string, EmptyFolderOptions, CancellationToken) | Vide le dossier spécifié |
| [ExportItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/exportitemsasync)(IEnumerable&lt;string&gt;, CancellationToken) | Exporte les éléments spécifiés de la boîte aux lettres |
| [FetchAppointmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchappointmentasync)(string, string, CancellationToken) | Récupérer le rendez-vous spécifié à partir du serveur. |
| [FetchAttachmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchattachmentasync)(string, CancellationToken) | Récupère la pièce jointe |
| [FetchConversationMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchconversationmessagesasync)(string, CancellationToken) | Récupère les messages de conversation spécifiés |
| [FetchItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchitemasync)(string, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Récupère l'élément complet avec les pièces jointes. |
| [FetchItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchitemsasync)(EwsFetchItems) | Récupère les éléments spécifiés. |
| [FetchMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchmessagesasync)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Récupère les messages spécifiés. |
| [FetchTaskAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/fetchtaskasync)(string, CancellationToken) | Récupère la tâche spécifiée. |
| [FindConversationsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/findconversationsasync)(string, CancellationToken) | Trouve les conversations dans le dossier spécifié |
| [FindPeopleAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/findpeopleasync)(EwsFindPeople) | Rechercher des contacts. |
| [FolderExistsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/folderexistsasync)(string, string, CancellationToken) | Vérifie si le dossier spécifié existe. |
| [GetContactAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getcontactasync)(string, ExchangeListContactsOptions, CancellationToken) | Récupère les informations de contact selon l'identifiant spécifié. |
| [GetContactsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getcontactsasync)(string, ExchangeListContactsOptions, CancellationToken) | Répertorie les contacts situés dans le dossier spécifié sur le serveur |
| [GetFolderInfoAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getfolderinfoasync)(string, CancellationToken) | Obtient les informations du dossier |
| [GetFolderPermissionsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getfolderpermissionsasync)(string, CancellationToken) | Obtient les autorisations du dossier. |
| [GetMailboxesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getmailboxesasync)(CancellationToken) | Répertorie les boîtes aux lettres ayant des adresses smtp. Remarque : le nombre maximum de contacts renvoyés est de 100. Il s'agit d'une restriction de l'opération EWS utilisée. |
| [GetMailboxInfoAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getmailboxinfoasync)(string, CancellationToken) | Obtient les informations de la boîte aux lettres |
| [GetServerTimeZoneIdsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/getservertimezoneidsasync)(IEnumerable&lt;string&gt;, CancellationToken) | Le GetServerTimeZoneIds renvoie des informations à partir de l'ID de fuseau horaire qui sont disponibles sur un serveur Exchange. |
| [GetTimezoneIdAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/gettimezoneidasync)(CancellationToken) | Obtient l'identifiant du fuseau horaire. |
| [ListAppointmentsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listappointmentsasync)(string, MailQuery, bool, CancellationToken) | Récupère la liste des rendez-vous pour le dossier de calendrier spécifié |
| [ListAppointmentsByPageAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listappointmentsbypageasync)(string, MailQuery, int, int, CancellationToken) | Récupère la page avec les rendez-vous pour le dossier de calendrier spécifié |
| [ListContactsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listcontactsasync)(string, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Répertorie les contacts situés dans le dossier spécifié sur le serveur. |
| [ListItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listitemsasync)(string, string, MailQuery, bool, CancellationToken) | Récupérer la liste des URI d'éléments dans le dossier spécifié |
| [ListMailboxesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmailboxesasync)(string, CancellationToken) | Répertorie les boîtes aux lettres ayant des adresses smtp. Remarque : le nombre maximum de contacts renvoyés est de 100. Il s'agit d'une restriction de l'opération EWS utilisée. |
| [ListMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesasync#listmessagesasync)(IEnumerable&lt;string&gt;, CancellationToken) | Liste les messages dans le dossier spécifié. |
| [ListMessagesAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesasync#listmessagesasync_1)(string, string, int, MailQuery, bool, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Liste les messages dans le dossier spécifié. |
| [ListMessagesByPageAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesbypageasync#listmessagesbypageasync)(string, PageInfo, CancellationToken) | Liste les messages dans le dossier spécifié. |
| [ListMessagesByPageAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesbypageasync#listmessagesbypageasync_1)(string, int, int, MailQuery, CancellationToken) | Liste les messages dans le dossier spécifié. |
| [ListPublicFoldersAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listpublicfoldersasync)(CancellationToken) | Obtient une collection de dossiers publics à partir du dossier public racine |
| [ListSubFoldersAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listsubfoldersasync)(string, string, CancellationToken) | Obtient la collection de dossiers enfants du parent |
| [ListSubFoldersByPageAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listsubfoldersbypageasync)(string, PageInfo, CancellationToken) | Recherche le dossier spécifié dans le dossier parent donné avec la pagination La méthode prend en charge la pagination. |
| [ListTasksAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/listtasksasync)(string, int, MailQuery, bool, CancellationToken) | Récupère les listes des tâches d'échange. |
| [LoadContactPhotoAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/loadcontactphotoasync)(ContactPhoto, CancellationToken) | Charge les données binaires de la photo de contact |
| [MailDisablePublicFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/maildisablepublicfolderasync)(string, CancellationToken) | Désactiver la messagerie d'un dossier public |
| [MailEnablePublicFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/mailenablepublicfolderasync)(string, CancellationToken) | Activer la messagerie pour un dossier public |
| [MarkAllItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/markallitemsasync)(IEnumerable&lt;string&gt;, bool, bool, CancellationToken) | Marque tous les éléments dans les dossiers spécifiés. |
| [MarkAsJunkAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/markasjunkasync)(IEnumerable&lt;string&gt;, bool, bool, CancellationToken) | La méthode MarkAsJunk déplace les messages électroniques vers le dossier de courrier indésirable et bloque l'expéditeur du message. |
| [MoveConversationItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/moveconversationitemsasync)(string, string, string, CancellationToken) | Déplace les éléments de conversation, qui se trouvent dans le dossier spécifié, dans le dossier cible spécifié |
| [MoveItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/moveitemasync)(string, string, CancellationToken) | Déplace l'élément vers le dossier spécifié |
| [ResolveContactsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/resolvecontactsasync)(string, ExchangeListContactsOptions, CancellationToken) | Résout les adresses e-mail et les noms d'affichage ambigus Remarque : le nombre maximal de contacts renvoyés est de 100. Il s'agit d'une restriction de l'opération EWS utilisée. |
| [ResolveMapiContactsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/resolvemapicontactsasync)(string, CancellationToken) | Résout les adresses e-mail et les noms d'affichage ambigus Remarque : le nombre maximal de contacts renvoyés est de 100. Il s'agit d'une restriction de l'opération EWS utilisée. |
| [RestoreAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/restoreasync)(PersonalStorage, RestoreSettings, CancellationToken) | Restaure les dossiers d'échange spécifiés à partir du stockage personnel donné. |
| [SendAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/sendasync)(MailMessage, FollowUpOptions, CancellationToken) | Envoie le message. |
| [SetConversationReadStateAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/setconversationreadstateasync)(string, bool, string, CancellationToken) | Définir l'état de lecture des éléments de conversation, qui se trouvent dans le dossier spécifié, sur la valeur spécifiée |
| [SetReadFlagAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/setreadflagasync)(string, bool, CancellationToken) | Marque le message spécifié comme lu. |
| [SetTimezoneIdAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/settimezoneidasync)(string, CancellationToken) | Définit l'identifiant du fuseau horaire. |
| [SyncFolderAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/syncfolderasync)(SyncState, CancellationToken) | Récupère les modifications des éléments dans un dossier spécifié. |
| [UpdateAppointmentAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updateappointmentasync)(Appointment, string, CancellationToken) | Mise à jour du rendez-vous. |
| [UpdateContactAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updatecontactasync)(Contact, CancellationToken) | Met à jour un élément de contact dans la boutique Exchange. |
| [UpdateItemAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updateitemasync)(EwsUpdateItem) | Met à jour l'élément. |
| [UpdateItemsAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updateitemsasync)(IEnumerable&lt;ExchangeStreamedItem&gt;, CancellationToken) | Met à jour les éléments spécifiés dans une boîte aux lettres. |
| [UpdateTaskAsync](../../aspose.email.clients.exchange.webservice/iasyncewsclient/updatetaskasync)(ExchangeTask, CancellationToken) | Met à jour la tâche spécifiée. |

### Voir également

* interface [IExchangeClientBase](../../aspose.email.clients.exchange/iexchangeclientbase)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
