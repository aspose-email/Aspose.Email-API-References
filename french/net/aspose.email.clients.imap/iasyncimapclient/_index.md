---
title: IAsyncImapClient
second_title: Référence de l'API Aspose.Email pour .NET
description: Permet aux applications daccéder aux messages et de les manipuler à laide du protocole IMAP Internet Message Access Protocol.
type: docs
weight: 16240
url: /fr/net/aspose.email.clients.imap/iasyncimapclient/
---
## IAsyncImapClient interface

Permet aux applications d'accéder aux messages et de les manipuler à l'aide du protocole IMAP (Internet Message Access Protocol).

```csharp
public interface IAsyncImapClient
```

## Méthodes

| Nom | La description |
| --- | --- |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/addmessageflagsasync)(ImapChangeMessageFlags) | Ajoute les drapeaux au message |
| [AppendMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/appendmessageasync)(MailMessage, string, IConnection, CancellationToken) | télécharge le message électronique dans le dossier spécifié |
| [AppendMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/appendmessagesasync)(IEnumerable&lt;MailMessage&gt;, string, IConnection, CancellationToken) | télécharge les messages électroniques dans le dossier actuel |
| [BackupAsync](../../aspose.email.clients.imap/iasyncimapclient/backupasync#backupasync)(ImapFolderInfoCollection, Stream, BackupSettings, IConnection, CancellationToken) | Sauvegarde le contenu des dossiers spécifiés |
| [BackupAsync](../../aspose.email.clients.imap/iasyncimapclient/backupasync#backupasync_1)(ImapFolderInfoCollection, string, BackupSettings, IConnection, CancellationToken) | Sauvegarde le contenu des dossiers spécifiés |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/changemessageflagsasync)(ImapChangeMessageFlags) | Change les drapeaux du message |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/iasyncimapclient/clientcapabilitiesasync)(IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Informe le serveur des extensions prises en charge par le client. Veuillez noter que cette opération ne fonctionne que si le serveur prend en charge RFC5161 Voir plus https://tools.ietf.org/html/rfc5161 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/iasyncimapclient/commitdeletesasync)(ImapUniqueIdParameterSet) | Valider les suppressions |
| [CopyMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessageasync#copymessageasync)(int, string, IConnection, CancellationToken) | Copie le message |
| [CopyMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessageasync#copymessageasync_1)(string, string, IConnection, CancellationToken) | Copie le message. |
| [CopyMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessagesasync)(ImapCopyMessages) | Copiez les messages. |
| [CreateFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/createfolderasync)(string, IConnection, CancellationToken) | Crée un dossier avec le nom spécifié. |
| [DeleteFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/deletefolderasync)(string, IConnection, CancellationToken) | Supprime un dossier spécifié. Cette méthode représente la commande IMAP DELETE. |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/deletemessagesasync)(ImapDeleteMessages) | Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |
| [ExistFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/existfolderasync)(string, IConnection, CancellationToken) | Vérifiez si ce dossier existe |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/iasyncimapclient/fetchattachmentasync)(int, string, IConnection, CancellationToken) | Récupère la pièce jointe spécifiée. |
| [FetchMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/fetchmessagesasync)(ImapFetchMessages) | Récupère les messages de manière asynchrone |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/iasyncimapclient/getfolderinfoasync)(string, IConnection, CancellationToken) | Renvoie des informations sur le dossier spécifié sans le sélectionner |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/iasyncimapclient/getmessagethreadsasync)(BaseSearchConditions, IConnection, CancellationToken) | Obtenir les fils de discussion. |
| [GetNamespacesAsync](../../aspose.email.clients.imap/iasyncimapclient/getnamespacesasync)(IConnection, CancellationToken) | Obtient les espaces de noms disponibles sur un serveur. |
| [GetQuotaAsync](../../aspose.email.clients.imap/iasyncimapclient/getquotaasync)(string, IConnection, CancellationToken) | Obtient des informations sur les quotas |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/iasyncimapclient/getquotarootasync)(string, IConnection, CancellationToken) | Obtient les informations de racine de quota pour la boîte aux lettres |
| [IntroduceClientAsync](../../aspose.email.clients.imap/iasyncimapclient/introduceclientasync)(ImapIdentificationInfo, IConnection, CancellationToken) | Présente les informations client à un serveur. |
| [ListFoldersAsync](../../aspose.email.clients.imap/iasyncimapclient/listfoldersasync)(string, bool, ListFoldersOptions, ListFoldersReturnOptions, IConnection, CancellationToken) | Obtient la liste des sous-dossiers dans le dossier spécifié |
| [ListMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessageasync#listmessageasync)(int, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Obtient des informations sur un message. |
| [ListMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessageasync#listmessageasync_1)(string, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Obtient des informations sur un message. |
| [ListMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesasync#listmessagesasync)(MailQuery, string, int, IConnection, CancellationToken) | Obtient la liste des messages dans le dossier actuel. |
| [ListMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesasync#listmessagesasync_1)(string, long, bool, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Obtient la liste des messages dans le dossier spécifié |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesbypageasync#listmessagesbypageasync_1)(int, int, PageSettings, CancellationToken) | Obtient la liste des messages |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesbypageasync#listmessagesbypageasync)(MailQuery, PageInfo, PageSettings, CancellationToken) | Obtient la liste des messages |
| [MoveFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/movefolderasync)(string, string, IConnection, CancellationToken) | Déplace le dossier spécifié et ses sous-dossiers vers un nouvel emplacement. |
| [MoveMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/movemessagesasync)(ImapMoveMessages) | Déplace les messages. |
| [NoopAsync](../../aspose.email.clients.imap/iasyncimapclient/noopasync)(IConnection, CancellationToken) | Commande 'Aucune opération' |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/removemessageflagsasync)(ImapChangeMessageFlags) | Supprime les drapeaux du message |
| [RenameFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/renamefolderasync)(string, string, IConnection, CancellationToken) | Renomme un dossier spécifié en un nouveau nom |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/iasyncimapclient/requestcheckpointasync)(IConnection, CancellationToken) | Demande un point de contrôle de la boîte aux lettres actuellement sélectionnée. |
| [RestoreAsync](../../aspose.email.clients.imap/iasyncimapclient/restoreasync)(PersonalStorage, RestoreSettings, CancellationToken) | Commence à restaurer les dossiers imap à partir du stockage personnel donné. |
| [ResumeMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/resumemonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, IImapMonitoringState, CancellationToken) | Reprend la surveillance des modifications de message pour le dossier spécifié. Contrairement à la méthode StartMonitoring, elle trouvera toutes les modifications de boîte aux lettres manquantes et appellera le rappel correspondant. |
| [SelectFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/selectfolderasync)(string, bool?, IConnection, CancellationToken) | Sélectionne le dossier spécifié |
| [SetQuotaAsync](../../aspose.email.clients.imap/iasyncimapclient/setquotaasync)(string, string, int, IConnection, CancellationToken) | Définit les informations de quota |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/iasyncimapclient/sortmessagethreadsasync)(SortConditions, IConnection, CancellationToken) | Trier les fils de messages. |
| [StartMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/startmonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, string) | Démarre la surveillance des modifications de message pour le dossier spécifié. |
| [StopMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/stopmonitoringasync)(string, CancellationToken) | Arrête la surveillance des modifications de message pour le dossier spécifié. Arrête la surveillance de tous les dossiers si folderName est null. |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/subscribefolderasync)(string, IConnection, CancellationToken) | Envoyé la commande SUBSCRIBE qui ajoute le nom de boîte aux lettres spécifié à l'ensemble de boîtes aux lettres "actives" du serveur. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/undeletemessageasync#undeletemessageasync)(int, long, IConnection, CancellationToken) | Marque un message avec le numéro de séquence spécifié comme non supprimé |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/undeletemessageasync#undeletemessageasync_1)(string, long, IConnection, CancellationToken) | Marque un message avec le numéro de séquence spécifié comme non supprimé. |
| [UnselectFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/unselectfolderasync)(bool, IConnection, CancellationToken) | Désélectionne le dossier actuellement sélectionné. si la propriété doNotExpunge est vraie, tous les messages sont marqués comme supprimés sont supprimés, sinon la suppression est annulée. Veuillez noter que cette opération ne fonctionne que si le serveur prend en charge RFC3691 Voir plus https://tools. ietf.org/html/rfc3691 |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/unsubscribefolderasync)(string, IConnection, CancellationToken) | Envoyé la commande UNSUBSCRIBE qui supprime le nom de boîte aux lettres spécifié de l'ensemble de boîtes aux lettres "actives" du serveur |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/iasyncimapclient/validatecredentialsasync)(IConnection, CancellationToken) | Exécute la validation des identifiants |

### Voir également

* espace de noms [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
