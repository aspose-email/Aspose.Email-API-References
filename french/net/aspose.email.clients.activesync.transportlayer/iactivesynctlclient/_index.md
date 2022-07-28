---
title: IActiveSyncTLClient
second_title: Référence de l'API Aspose.Email pour .NET
description: interface client ActiveSync
type: docs
weight: 1310
url: /fr/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/
---
## IActiveSyncTLClient interface

interface client ActiveSync

```csharp
public interface IActiveSyncTLClient : IBaseActiveSyncTLClient
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AirSyncKeys](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/airsynckeys) { get; } | Contient une valeur utilisée par le serveur pour marquer l'état de synchronisation de chaque collection synchronisée. Où la clé du dictionnaire est l'ID du serveur et la valeur du dictionnaire est SyncKey. Pour les commandes GetItemEstimate et Sync. |
| [FoldersSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderssynckey) { get; } | Utilisé par le serveur pour suivre l'état actuel du client. Pour les opérations avec des dossiers uniquement |
| [HeartbeatInterval](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/heartbeatinterval) { get; set; } | L'élément HeartbeatInterval est un élément enfant de l'élément Ping dans les demandes et réponses de commande Ping. Dans les demandes de commande Ping, il spécifie la durée, en secondes, pendant laquelle le serveur DEVRAIT attendre avant d'envoyer une réponse si aucun nouvel élément n'est ajouté à l'ensemble de dossiers spécifié, comme spécifié dans la section 3.1.5.6. L'élément HeartbeatInterval est également renvoyé par le serveur avec un code d'état de 5 et spécifie l'intervalle minimum ou maximum autorisé lorsque le client a demandé un intervalle de pulsation en dehors de la plage acceptable. |

## Méthodes

| Nom | La description |
| --- | --- |
| [FolderCreate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldercreate)(string, string, UserCreatedFolderTypes) | Le FolderCreate crée un nouveau dossier en tant que dossier enfant du dossier parent spécifié. |
| [FolderDelete](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderdelete)(string) | Supprime la collection avec l'identifiant correspondant. |
| [FolderSync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldersync#foldersync)() | Le FolderSync synchronise la hiérarchie des collections mais ne synchronise pas les éléments des collections elles-mêmes. |
| [FolderSync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldersync#foldersync_1)(bool) | Le FolderSync synchronise la hiérarchie des collections mais ne synchronise pas les éléments des collections elles-mêmes. |
| [FolderUpdate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderupdate#folderupdate)(FolderInfo) | La commande FolderUpdate déplace un dossier d'un emplacement à un autre sur le serveur. La commande est également utilisée pour renommer un dossier. |
| [FolderUpdate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderupdate#folderupdate_1)(string, string, string) | La commande FolderUpdate déplace un dossier d'un emplacement à un autre sur le serveur. La commande est également utilisée pour renommer un dossier. |
| [GetAttachment](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getattachment)(string) | Le GetAttachment récupère une pièce jointe à partir du serveur. Le GetAttachment n'est pas pris en charge lorsque la version du protocole est 14.0 ou 14.1. Utilisez plutôt l'élément Fetch de la commande ItemOperations. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate_2)(IEnumerable&lt;ItemEstimateRequest&gt;) | La commande GetItemEstimate obtient une estimation du nombre d'éléments d'une collection ou d'un dossier sur le serveur qui doivent être synchronisés. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate)(ItemEstimateRequest) | La commande GetItemEstimate obtient une estimation du nombre d'éléments d'une collection ou d'un dossier sur le serveur qui doivent être synchronisés. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate_1)(params ItemEstimateRequest[]) | La commande GetItemEstimate obtient une estimation du nombre d'éléments d'une collection ou d'un dossier sur le serveur qui doivent être synchronisés. |
| [ItemOperations](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/itemoperations)(ItemOperationsRequest) | ItemOperations fournit une gestion en ligne par lots des opérations Fetch, EmptyFolderContents et Move. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_3)(IEnumerable&lt;MeetingResponseRequest&gt;) | Accepte, accepte provisoirement ou refuse une demande de réunion dans le dossier Boîte de réception ou Calendrier de l'utilisateur. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_2)(params MeetingResponseRequest[]) | Accepte, accepte provisoirement ou refuse une demande de réunion dans le dossier Boîte de réception ou Calendrier de l'utilisateur. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse)(UserResponse, string, string) | Accepte, accepte provisoirement ou refuse une demande de réunion dans le dossier Boîte de réception ou Calendrier de l'utilisateur. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_1)(UserResponse, string, string, string, string) | Accepte, accepte provisoirement ou refuse une demande de réunion dans le dossier Boîte de réception ou Calendrier de l'utilisateur. |
| [MoveItem](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitem)(string, string, string) | La commande MoveItems déplace un ou plusieurs éléments d'un dossier sur le serveur vers un autre. |
| [MoveItems](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitems#moveitems_1)(IEnumerable&lt;MoveItemData&gt;) | La commande MoveItems déplace un ou plusieurs éléments d'un dossier sur le serveur vers un autre. |
| [MoveItems](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitems#moveitems)(params MoveItemData[]) | La commande MoveItems déplace un ou plusieurs éléments d'un dossier sur le serveur vers un autre. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_4)(IEnumerable&lt;PingParameter&gt;) | La commande Ping est utilisée pour demander au serveur de surveiller les dossiers spécifiés à la recherche de modifications nécessitant une resynchronisation du client. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping)(params PingParameter[]) | La commande Ping est utilisée pour demander au serveur de surveiller les dossiers spécifiés à la recherche de modifications nécessitant une resynchronisation du client. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_2)(int, IEnumerable&lt;PingParameter&gt;) | La commande Ping est utilisée pour demander au serveur de surveiller les dossiers spécifiés à la recherche de modifications nécessitant une resynchronisation du client. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_1)(int, params PingParameter[]) | La commande Ping est utilisée pour demander au serveur de surveiller les dossiers spécifiés à la recherche de modifications nécessitant une resynchronisation du client. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_5)(string, FolderClass) | La commande Ping est utilisée pour demander au serveur de surveiller les dossiers spécifiés à la recherche de modifications nécessitant une resynchronisation du client. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_3)(int, string, FolderClass) | La commande Ping est utilisée pour demander au serveur de surveiller les dossiers spécifiés à la recherche de modifications nécessitant une resynchronisation du client. |
| [Provision](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/provision)(ProvisionRequest) | La commande Provision permet aux appareils clients de demander au serveur les paramètres de politique de sécurité définis par l'administrateur, tels que l'exigence minimale de longueur de mot de passe du numéro d'identification personnel (PIN). |
| [ResetAirSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetairsynckey#resetairsynckey)() | Réinitialiser SyncKeys pour les opérations GetItemEstimate et Sync pour toutes les collections. |
| [ResetAirSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetairsynckey#resetairsynckey_1)(string) | Réinitialiser SyncKey pour les opérations GetItemEstimate et Sync pour la collection définie. |
| [ResetFoldersSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetfolderssynckey)() | Réinitialiser SyncKey pour les opérations avec les dossiers |
| [ResolveRecipients](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resolverecipients)(ResolveRecipientsRequest) | ResolveRecipients est utilisé pour résoudre une liste de destinataires fournis, pour récupérer leurs informations de disponibilité et, éventuellement, pour récupérer leurs certificats S/MIME afin que les clients puissent envoyer des messages électroniques S/MIME chiffrés. Récupération des informations de disponibilité l'utilisation de l'élément Disponibilité dans la commande ResolveRecipients n'est pas prise en charge lorsque la version du protocole est 12.1. |
| [Search](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/search)(SearchRequest) | La recherche est utilisée pour trouver des entrées dans un carnet d'adresses, une boîte aux lettres ou une bibliothèque de documents (UNC ou Windows SharePoint Services). |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail)(string) | Le SendMail est utilisé par les clients pour envoyer des e-mails au format MIME au serveur. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_1)(string, bool) | Le SendMail est utilisé par les clients pour envoyer des e-mails au format MIME au serveur. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_2)(string, bool, string) | Le SendMail est utilisé par les clients pour envoyer des e-mails au format MIME au serveur. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_3)(string, bool, string, string) | Le SendMail est utilisé par les clients pour envoyer des e-mails au format MIME au serveur. |
| [Settings](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/settings)(SettingsRequest) | Les paramètres prennent en charge les opérations d'obtention et de définition sur les propriétés globales et les paramètres d'absence du bureau (OOF) pour l'utilisateur. Les paramètres envoient également des informations sur l'appareil au serveur, implémentent la récupération du mot de passe/numéro d'identification personnel (PIN) de l'appareil et récupèrent une liste des adresses e-mail de l'utilisateur. |
| [SmartForward](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/smartforward)(SmartRequest) | La commande SmartForward est utilisée par les clients pour transférer des messages sans récupérer le message d'origine complet du serveur. |
| [SmartReply](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/smartreply)(SmartRequest) | La commande SmartReply est utilisée par les clients pour répondre aux messages sans récupérer le message d'origine complet du serveur. |
| [Sync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sync)(SyncRequest) | Le Sync synchronise les changements dans une collection entre le client et le serveur. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert)(IEnumerable&lt;X509Certificate&gt;) | Le ValidateCert est utilisé par le client pour valider un certificat qui a été reçu via un courrier S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_4)(X509Certificate) | La commande ValidateCert est utilisée par le client pour valider un certificat qui a été reçu via un courrier S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_1)(IEnumerable&lt;X509Certificate&gt;, bool) | Le ValidateCert est utilisé par le client pour valider un certificat qui a été reçu via un courrier S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_2)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;) | Le ValidateCert est utilisé par le client pour valider un certificat qui a été reçu via un courrier S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_5)(X509Certificate, bool) | Le ValidateCert est utilisé par le client pour valider un certificat qui a été reçu via un courrier S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_6)(X509Certificate, IEnumerable&lt;X509Certificate&gt;) | Le ValidateCert est utilisé par le client pour valider un certificat qui a été reçu via un courrier S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_3)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;, bool) | Le ValidateCert est utilisé par le client pour valider un certificat qui a été reçu via un courrier S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_7)(X509Certificate, IEnumerable&lt;X509Certificate&gt;, bool) | Le ValidateCert est utilisé par le client pour valider un certificat qui a été reçu via un courrier S/MIME. |

### Voir également

* interface [IBaseActiveSyncTLClient](../ibaseactivesynctlclient)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
