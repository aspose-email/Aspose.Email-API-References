---
title: IGraphClient
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente linterface pour le client Exchange REST.
type: docs
weight: 15950
url: /fr/net/aspose.email.clients.graph/igraphclient/
---
## IGraphClient interface

Représente l'interface pour le client Exchange REST.

```csharp
public interface IGraphClient : IDisposable
```

## Propriétés

| Nom | La description |
| --- | --- |
| [MultipleServicesTokenProvider](../../aspose.email.clients.graph/igraphclient/multipleservicestokenprovider) { get; set; } | Obtient ou définit qu'un objet permet de récupérer le jeton d'accès OAuth. |
| [Proxy](../../aspose.email.clients.graph/igraphclient/proxy) { get; set; } | Obtient ou définit des données pour accéder par proxy au serveur Exchange. |
| [Resource](../../aspose.email.clients.graph/igraphclient/resource) { get; set; } | Obtient ou définit le type de ressource. |
| [ResourceId](../../aspose.email.clients.graph/igraphclient/resourceid) { get; set; } | Obtient ou définit l'ID de ressource. Par exemple, pour les utilisateurs, il peut s'agir du nom d'utilisateur principal (UPN) ou de l'ID d'utilisateur |
| [TenantId](../../aspose.email.clients.graph/igraphclient/tenantid) { get; set; } | Obtient ou définit l'identifiant du locataire |
| [Timeout](../../aspose.email.clients.graph/igraphclient/timeout) { get; set; } | Obtient ou définit le nombre de millisecondes à attendre avant l'expiration de l'opération. La valeur par défaut est 100 000 millisecondes (100 secondes). |
| [TokenProvider](../../aspose.email.clients.graph/igraphclient/tokenprovider) { get; set; } | Obtient ou définit qu'un objet permet de récupérer le jeton d'accès OAuth. |

## Méthodes

| Nom | La description |
| --- | --- |
| [CopyFolder](../../aspose.email.clients.graph/igraphclient/copyfolder)(string, string) | Copier un dossier de messagerie et son contenu dans un autre dossier de messagerie. |
| [CopyMessage](../../aspose.email.clients.graph/igraphclient/copymessage)(string, string) | Copiez un message dans un autre dossier de messagerie. |
| [CopyNotebook](../../aspose.email.clients.graph/igraphclient/copynotebook)(string, string, string) | Copie un bloc-notes dans le dossier Blocs-notes de la bibliothèque Documents de destination. Le dossier est créé s'il n'existe pas. Pour les opérations de copie, vous suivez un modèle d'appel asynchrone : appelez d'abord l'action de copie, puis interrogez le point de terminaison de l'opération pour obtenir le résultat. Permissions L'une des autorisations suivantes est requise pour appeler cette API. Délégué (compte professionnel ou scolaire) Notes.Create, Notes.ReadWrite, Notes.ReadWrite.All Délégué (compte Microsoft personnel) Notes.Create, Notes.ReadWrite Application Notes.ReadWrite.All |
| [CreateAttachment](../../aspose.email.clients.graph/igraphclient/createattachment)(string, MapiAttachment) | Crée une nouvelle pièce jointe pour l'élément spécifié |
| [CreateCategory](../../aspose.email.clients.graph/igraphclient/createcategory)(string, CategoryPreset) | Crée un[`OutlookCategory`](../outlookcategory) objet dans la liste principale des catégories de l'utilisateur. |
| [CreateFolder](../../aspose.email.clients.graph/igraphclient/createfolder#createfolder)(string) | Créer un nouveau dossier. |
| [CreateFolder](../../aspose.email.clients.graph/igraphclient/createfolder#createfolder_1)(string, string) | Créer un nouveau dossier. |
| [CreateMessage](../../aspose.email.clients.graph/igraphclient/createmessage)(string, MapiMessage) | Crée un message dans le dossier spécifié |
| [CreateNotebook](../../aspose.email.clients.graph/igraphclient/createnotebook)(Notebook) | Créer un nouveau bloc-notes OneNote. Permissions L'une des autorisations suivantes est requise pour appeler cette API. Notes déléguées (compte professionnel ou scolaire) Notes.Create, Notes.ReadWrite, Notes.ReadWrite.All Notes déléguées (compte Microsoft personnel). Créer, Notes.ReadWrite Notes d'application.ReadWrite.All |
| [CreateOrUpdateOverride](../../aspose.email.clients.graph/igraphclient/createorupdateoverride#createorupdateoverride)(ClassificationOverride) | Créer un remplacement pour un expéditeur identifié par une adresse SMTP. Les futurs messages provenant de cette adresse SMTP seront systématiquement classés comme spécifié dans le remplacement. Remarque : - Si un remplacement existe déjà avec la même adresse SMTP, les champs classifyAs et name de ce remplacement sont mis à jour avec les valeurs fournies. - Le nombre maximal de remplacements pris en charge pour une boîte aux lettres est de 1000, basé sur des adresses SMTP d'expéditeur uniques. |
| [CreateOrUpdateOverride](../../aspose.email.clients.graph/igraphclient/createorupdateoverride#createorupdateoverride_1)(MailAddress, ClassificationType) | Créer un remplacement pour un expéditeur identifié par une adresse SMTP. Les futurs messages provenant de cette adresse SMTP seront systématiquement classés comme spécifié dans le remplacement. Remarque : - Si un remplacement existe déjà avec la même adresse SMTP, les champs classifyAs et name de ce remplacement sont mis à jour avec les valeurs fournies. - Le nombre maximal de remplacements pris en charge pour une boîte aux lettres est de 1000, basé sur des adresses SMTP d'expéditeur uniques. |
| [CreateRule](../../aspose.email.clients.graph/igraphclient/createrule)(InboxRule) | Créez une règle de message en spécifiant un ensemble de conditions et d'actions. Outlook exécute ces actions si un message entrant dans la boîte de réception de l'utilisateur répond aux conditions spécifiées. Autorisations : L'une des autorisations suivantes est requise pour appeler cette API.Pour Pour en savoir plus, y compris sur la manière de choisir les autorisations, consultez Autorisations. Delegated (compte professionnel ou scolaire) MailboxSettings.ReadWrite Delegated (compte Microsoft personnel) MailboxSettings.ReadWrite Application MailboxSettings.ReadWrite |
| [Delete](../../aspose.email.clients.graph/igraphclient/delete)(string) | Supprimer l'objet. |
| [DeleteAttachment](../../aspose.email.clients.graph/igraphclient/deleteattachment)(string) | Supprime la pièce jointe |
| [FetchAttachment](../../aspose.email.clients.graph/igraphclient/fetchattachment)(string) | Obtient la pièce jointe pour l'identifiant spécifié |
| [FetchCategory](../../aspose.email.clients.graph/igraphclient/fetchcategory)(string) | Obtenir les propriétés et les relations de l'objet outlookCategory spécifié. |
| [FetchMessage](../../aspose.email.clients.graph/igraphclient/fetchmessage)(string) | Obtient le message dans l'identifiant spécifié |
| [FetchNotebook](../../aspose.email.clients.graph/igraphclient/fetchnotebook)(string) | Récupérer les propriétés et les relations d'un objet bloc-notes. Permissions L'une des autorisations suivantes est requise pour appeler cette API. Délégué (compte professionnel ou scolaire) Notes.Create, Notes.Read, Notes.ReadWrite, Notes.Read.All , Notes.ReadWrite.All Delegated (compte Microsoft personnel) Notes.Create, Notes.Read, Notes.ReadWrite Application Notes.Read.All, Notes.ReadWrite.All |
| [FetchRule](../../aspose.email.clients.graph/igraphclient/fetchrule)(string) | Obtenez les propriétés et les relations d'un objet de règle de message. Permissions L'une des autorisations suivantes est requise pour appeler cette API. Délégué (compte Microsoft personnel) MailboxSettings.Read Application MailboxSettings.Read |
| [GetFolder](../../aspose.email.clients.graph/igraphclient/getfolder)(string) | Obtient le dossier par un identifiant. |
| [GetOneNoteOperationStatus](../../aspose.email.clients.graph/igraphclient/getonenoteoperationstatus)(string) | Obtenir l'état d'une opération OneNote de longue durée. Cela s'applique aux opérations qui renvoient l'en-tête Operation-Location dans la réponse, telles que CopyNotebook, CopyToNotebook, CopyToSectionGroup et CopyToSection. Vous pouvez interroger le point de terminaison Operation-Location jusqu'à ce que le La propriété status renvoie terminé ou échoué. Si le statut est terminé, la propriété resourceLocation contient l'URI du point de terminaison de la ressource. Si le statut échoue, les propriétés error et @api.diagnostics fournissent des informations sur l'erreur. |
| [ListAttachments](../../aspose.email.clients.graph/igraphclient/listattachments)(string) | Liste des pièces jointes du message parent. |
| [ListCategories](../../aspose.email.clients.graph/igraphclient/listcategories)() | Obtenir toutes les catégories qui ont été définies pour l'utilisateur. |
| [ListFolders](../../aspose.email.clients.graph/igraphclient/listfolders#listfolders)() | Répertorier les dossiers du dossier parent pour les dossiers affichés dans les clients de messagerie normaux, tels que la boîte de réception. |
| [ListFolders](../../aspose.email.clients.graph/igraphclient/listfolders#listfolders_1)(string) | Répertorier les dossiers du dossier parent pour les dossiers affichés dans les clients de messagerie normaux, tels que la boîte de réception. |
| [ListMessages](../../aspose.email.clients.graph/igraphclient/listmessages#listmessages_1)(string) | Liste MessageInfo du dossier parent. |
| [ListMessages](../../aspose.email.clients.graph/igraphclient/listmessages#listmessages)(string, PageInfo, MailQuery) | Liste MessageInfo du dossier parent. |
| [ListNotebooks](../../aspose.email.clients.graph/igraphclient/listnotebooks)() | Récupérer une liste d'objets de bloc-notes. Permissions L'une des autorisations suivantes est requise pour appeler cette API. Délégué (compte professionnel ou scolaire) Notes.Create, Notes.Read, Notes.ReadWrite, Notes.Read.All, Notes. ReadWrite.All Délégué (compte Microsoft personnel) Notes.Create, Notes.Read, Notes.ReadWrite Application Notes.Read.All, Notes.ReadWrite.All |
| [ListOverrides](../../aspose.email.clients.graph/igraphclient/listoverrides)() | Obtenez les remplacements qu'un utilisateur a configurés pour toujours classer les messages de certains expéditeurs de manière spécifique. Chaque remplacement correspond à une adresse SMTP d'un expéditeur. Initialement, un utilisateur n'a aucun remplacement. Autorisations : les autorisations suivantes sont requises pour appeler cette API. Pour en savoir plus, notamment sur la manière de choisir les autorisations, consultez Autorisations. Delegated (compte professionnel ou scolaire) Mail.Read Delegated (compte Microsoft personnel) Mail.Read Application Mail.Read |
| [ListRules](../../aspose.email.clients.graph/igraphclient/listrules)() | Obtenir tous les objets messageRule définis pour la boîte de réception de l'utilisateur. Permissions L'une des autorisations suivantes est requise pour appeler cette API. Délégué (compte Microsoft personnel) MailboxSettings.Read Application MailboxSettings.Read |
| [MoveFolder](../../aspose.email.clients.graph/igraphclient/movefolder)(string, string) | Déplacer un dossier de messagerie et son contenu vers un autre dossier de messagerie. |
| [MoveMessage](../../aspose.email.clients.graph/igraphclient/movemessage)(string, string) | Déplacer un message vers un autre dossier de messagerie. |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send)(MapiMessage) | envoie un e-mail |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send_2)(string) | Envoyer un message dans le dossier brouillon. Le brouillon de message peut être un brouillon de nouveau message, un brouillon de réponse, un brouillon de réponse à tous ou un brouillon de transfert. Le message est ensuite enregistré dans le dossier Éléments envoyés. |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send_1)(MapiMessage, bool) | envoie un e-mail |
| [SetRead](../../aspose.email.clients.graph/igraphclient/setread)(string) | Marquer le message comme lu |
| [UpdateCategory](../../aspose.email.clients.graph/igraphclient/updatecategory)(OutlookCategory) | Met à jour la constante de couleur prédéfinie pour la catégorie spécifiée |
| [UpdateFolder](../../aspose.email.clients.graph/igraphclient/updatefolder)(FolderInfo) | Dossier des mises à jour. |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage#updatemessage)(MapiMessage) | Message de mise à jour |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage#updatemessage_1)(MapiMessage, UpdateSettings) | Message de mise à jour |
| [UpdateOverride](../../aspose.email.clients.graph/igraphclient/updateoverride)(ClassificationOverride) | Modifiez le champ classifyAs d'un remplacement comme spécifié. Vous ne pouvez pas utiliser cette méthode pour modifier d'autres champs dans une instance ClassificationOverride. Si un remplacement existe pour un expéditeur et que l'expéditeur modifie son nom d'affichage, vous pouvez utiliser CreateOrUpdateOverride pour forcer une mise à jour du champ de nom dans le remplacement existant. Si un remplacement existe pour un expéditeur et que l'expéditeur modifie son adresse SMTP, supprimer le remplacement existant et en créer un nouveau avec la nouvelle adresse SMTP est le seul moyen de "mettre à jour" le remplacement pour cet expéditeur. Autorisations : L'une des autorisations suivantes est requise pour appeler cette API. (compte personnel Microsoft) Mail.ReadWrite Application Mail.ReadWrite |
| [UpdateRule](../../aspose.email.clients.graph/igraphclient/updaterule)(InboxRule) | Modifiez les propriétés inscriptibles d'un objet messageRule et enregistrez les modifications. Permissions L'une des autorisations suivantes est requise pour appeler cette API. ReadWrite Délégué (compte Microsoft personnel) MailboxSettings.ReadWrite Application MailboxSettings.ReadWrite |

### Voir également

* espace de noms [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
