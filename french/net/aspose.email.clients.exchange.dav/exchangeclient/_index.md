---
title: ExchangeClient
second_title: Référence de l'API Aspose.Email pour .NET
description: La classe ExchangeClient permet aux applications de gérer la boîte de courrier électronique dans Microsoft Exchange Server à laide du protocole WebDav Exchange Store.
type: docs
weight: 3150
url: /fr/net/aspose.email.clients.exchange.dav/exchangeclient/
---
## ExchangeClient class

La classe ExchangeClient permet aux applications de gérer la boîte de courrier électronique dans Microsoft Exchange Server à l'aide du protocole WebDav Exchange Store.

```csharp
public sealed class ExchangeClient : ExchangeClientBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ExchangeClient](exchangeclient#constructor)(string, ICredentials) | Initialiser une nouvelle instance de la classe[`Client d'échange`](../exchangeclient) |
| [ExchangeClient](exchangeclient#constructor_1)(string, string, string) | Initialiser une nouvelle instance de la classe[`Client d'échange`](../exchangeclient) |
| [ExchangeClient](exchangeclient#constructor_2)(string, string, string, string) | Initialiser une nouvelle instance de la classe[`Client d'échange`](../exchangeclient) |

## Propriétés

| Nom | La description |
| --- | --- |
| [ClientCertificate](../../aspose.email.clients.exchange.dav/exchangeclient/clientcertificate) { get; set; } | Obtient ou définit le certificat client. |
| [CookieContainer](../../aspose.email.clients.exchange.dav/exchangeclient/cookiecontainer) { get; set; } | Obtient ou définit le conteneur de cookies. |
| virtual [Credentials](../../aspose.email.clients.exchange/exchangeclientbase/credentials) { get; set; } | Obtient ou définit les informations d'identification |
| [Encoding](../../aspose.email.clients.exchange.dav/exchangeclient/encoding) { get; set; } | Obtient ou définit l'encodage. |
| [KeepAlive](../../aspose.email.clients.exchange.dav/exchangeclient/keepalive) { get; set; } | Indique s'il faut rester en vie. |
| [LogFileName](../../aspose.email.clients.exchange/exchangeclientbase/logfilename) { get; set; } | Obtient ou définit le nom du fichier journal |
| [MailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/mailboxinfo) { get; } | Obtient les informations de la boîte aux lettres. |
| virtual [MailboxUri](../../aspose.email.clients.exchange/exchangeclientbase/mailboxuri) { get; set; } | Obtient ou définit la boîte aux lettres uri |
| [PreAuthenticate](../../aspose.email.clients.exchange.dav/exchangeclient/preauthenticate) { get; set; } | Indique s'il faut faire une pré-authentification. |
| virtual [Proxy](../../aspose.email.clients.exchange/exchangeclientbase/proxy) { get; set; } | Obtient ou définit le proxy. |
| [SendChunked](../../aspose.email.clients.exchange.dav/exchangeclient/sendchunked) { get; set; } | Obtient ou définit une valeur indiquant si [send chunked]. |
| virtual [Timeout](../../aspose.email.clients.exchange/exchangeclientbase/timeout) { get; set; } | Obtient ou définit le nombre de millisecondes à attendre avant l'expiration de l'opération. La valeur par défaut est 100 000 millisecondes (100 secondes). |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/exchangeclientbase/usedateinlogfilename) { get; set; } | Obtient ou définit la valeur qui indique si la date doit être utilisée dans le nom du fichier journal. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage#appendmessage)(string, MailMessage) | télécharge le message électronique dans le dossier spécifié |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage#appendmessage_1)(string, MailMessage, bool) | télécharge le message électronique dans le dossier spécifié |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup#backup)(ExchangeFolderInfoCollection, Stream, BackupOptions) | Sauvegarde le contenu des dossiers spécifiés |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup#backup_1)(ExchangeFolderInfoCollection, string, BackupOptions) | Sauvegarde le contenu des dossiers spécifiés |
| [CreateContact](../../aspose.email.clients.exchange.dav/exchangeclient/createcontact)(Contact) | Crée un élément de contact dans la boutique Exchange. |
| [CreateFolder](../../aspose.email.clients.exchange.dav/exchangeclient/createfolder)(string, string) | Crée le nouveau dossier avec le nom spécifié dans le dossier parent spécifié. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact_1)(Contact) | Supprime le contact. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact)(MapiContact) | Supprime le contact. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact_2)(string) | Supprime le contact. |
| [DeleteFolder](../../aspose.email.clients.exchange.dav/exchangeclient/deletefolder)(string) | Supprime le dossier |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage#deletemessage)(string) | Supprime le message électronique. |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage#deletemessage_1)(string, bool) | Supprime le message électronique. |
| [Dispose](../../aspose.email.clients.exchange/exchangeclientbase/dispose)() | Effectue des tâches définies par l'application associées à la libération, à la libération ou à la réinitialisation des ressources non gérées. |
| [FetchAttachment](../../aspose.email.clients.exchange.dav/exchangeclient/fetchattachment)(string) | Récupère la pièce jointe |
| [FetchMapiMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmapimessage)(string) | Récupère le message mapi avec l'uri spécifié. |
| [FetchMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmessage)(string) | Récupère le message électronique avec l'uri spécifié. |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists#folderexists)(string, string) | Vérifie si le dossier spécifié existe. |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists#folderexists_1)(string, string, out ExchangeFolderInfo) | Vérifie si le dossier spécifié existe. |
| [GetContacts](../../aspose.email.clients.exchange.dav/exchangeclient/getcontacts)(string) | Répertorie les contacts situés dans le dossier spécifié sur le serveur |
| [GetFolderInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getfolderinfo)(string) | Obtient les informations du dossier. |
| [GetMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxes)() | Répertorie les boîtes aux lettres dans la liste d'adresses globale. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo#getmailboxinfo)() | Obtenir les informations de la boîte aux lettres |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo#getmailboxinfo_1)(string) | Obtient les informations de la boîte aux lettres |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize#getmailboxsize)() | Obtenir la taille de la maibox |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize#getmailboxsize_1)(string) | Obtenir la taille de la maibox |
| [GetVersionInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getversioninfo)() | Renvoie la version du serveur Exchange info |
| [ListContacts](../../aspose.email.clients.exchange.dav/exchangeclient/listcontacts)(string) | Répertorie les contacts situés dans le dossier spécifié sur le serveur |
| [ListMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/listmailboxes)() | Répertorie les boîtes aux lettres dans la liste d'adresses globale. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages)(string) | Liste les messages. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_3)(string, bool) | Lister les messages dans le dossier spécifié |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_1)(string, ExchangeListMessagesOptions) | Répertorie le message électronique dans le dossier spécifié. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_4)(string, int) | Liste les messages. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_6)(string, string) | Liste les messages. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_5)(string, int, ExchangeListMessagesOptions) | Lister les messages dans le dossier spécifié |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_2)(string, MailQuery, bool) | Liste les messages. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_7)(string, string, bool) | Liste les messages. |
| [ListMessagesById](../../aspose.email.clients.exchange.dav/exchangeclient/listmessagesbyid)(string, string) | Liste les messages par id. |
| [ListPublicFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listpublicfolders)() | Obtient une collection de dossiers publics à partir du dossier public racine |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders#listsubfolders)(ExchangeFolderInfo) | Obtient la collection de dossiers publics enfants du parent |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders#listsubfolders_1)(string) | Obtient la collection de dossiers enfants du parent |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems#moveitems_1)(string, params string[]) | Déplace les éléments. |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems#moveitems)(string, bool, params string[]) | Déplace les éléments. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage)(ExchangeMessageInfo, string) | Déplace le message. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_3)(string, string) | Déplace le message. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_1)(ExchangeMessageInfo, string, bool) | Déplace le message. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_2)(string, bool, string) | Déplace le message. |
| [ResolveContacts](../../aspose.email.clients.exchange.dav/exchangeclient/resolvecontacts)(string) | Résout les noms d'affichage de boîte aux lettres ambigus. Remarque : le nombre maximal de contacts renvoyés est de 100. Il s'agit d'une restriction de la commande d'échange utilisée. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_1)(PersonalStorage, RestoreOptions) | Restaure les dossiers d'échange à partir du stockage personnel donné. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_3)(Stream, RestoreOptions) | Restaure les dossiers d'échange à partir du stockage personnel donné. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_5)(string, RestoreOptions) | Restaure les dossiers d'échange à partir du fichier de stockage personnel spécifié. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore)(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) | Restaure les dossiers d'échange spécifiés à partir du stockage personnel donné. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_2)(Stream, ExchangeFolderInfoCollection, RestoreOptions) | Restaure les dossiers d'échange spécifiés à partir du stockage personnel donné. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_4)(string, ExchangeFolderInfoCollection, RestoreOptions) | Restaure les dossiers d'échange spécifiés à partir du fichier de stockage personnel spécifié. |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage#savemessage)(string, Stream) | Enregistre le message. |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage#savemessage_1)(string, string) | Enregistre le message électronique spécifié par l'uri dans le système de fichiers local. Le fichier de message électronique est au format compatible RFC 822 (EML).  si vous souhaitez analyser les fichiers de messages électroniques, utilisez[`MailMessage`](../../aspose.email/mailmessage). |
| [Send](../../aspose.email.clients.exchange.dav/exchangeclient/send)(MailMessage) | Envoie le message électronique. |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag#setreadflag)(string) | Marque le message spécifié comme lu. |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag#setreadflag_1)(string, bool) | Marque le message spécifié comme lu. |

### Voir également

* class [ExchangeClientBase](../../aspose.email.clients.exchange/exchangeclientbase)
* espace de noms [Aspose.Email.Clients.Exchange.Dav](../../aspose.email.clients.exchange.dav)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
