---
title: Aspose.Email.Clients.Imap
second_title: Référence de l'API Aspose.Email pour .NET
description: Le Aspose.Email.Clients.Imap Lespace de noms fournit des classes pour accéder à et manipuler les messages à laide du protocole IMAP Internet Message Access Protocol.
type: docs
weight: 220
url: /fr/net/aspose.email.clients.imap/
---
Le **Aspose.Email.Clients.Imap** L'espace de noms fournit des classes pour accéder à et manipuler les messages à l'aide du protocole IMAP (Internet Message Access Protocol).

## Des classes

| Classer | La description |
| --- | --- |
| [AppendMessagesResult](./appendmessagesresult) | Contient le résultat de l'opération avec messages |
| [BackupSettings](./backupsettings) | La classe contient des options pour l'opération de sauvegarde |
| [BaseSearchConditions](./basesearchconditions) | Fournit une classe de base pour les conditions de recherche. |
| [ESearchOptions](./esearchoptions) | Options de résultat ESEARCH Cette méthode ne fonctionne que si le serveur prend en charge l'extension ESEARCH. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |
| [FetchTimeoutException](./fetchtimeoutexception) | Représente l'exception levée lorsqu'un message ne peut pas être lu dans le délai spécifié. |
| [ImapAttachmentInfo](./imapattachmentinfo) | Représente une information de pièce jointe. |
| [ImapAttachmentInfoCollection](./imapattachmentinfocollection) | Représente la collection de[`ImapAttachmentInfo`](../aspose.email.clients.imap/imapattachmentinfo) |
| [ImapClient](./imapclient) | Permet aux applications d'accéder aux messages et de les manipuler à l'aide du protocole IMAP (Internet Message Access Protocol). |
| [ImapFolderInfo](./imapfolderinfo) | Représente un dossier IMAP. |
| [ImapFolderInfoCollection](./imapfolderinfocollection) | Fournit un conteneur pour une collection d'objets ImapFolderInfo. |
| [ImapIdentificationInfo](./imapidentificationinfo) | Représente un conteneur de classe avec des informations d'identification à échanger entre le client de messagerie et le serveur. S'il vous plaît, lisez plus rfc2971 https://tools.ietf.org/html/rfc2971 |
| [ImapMailboxInfo](./imapmailboxinfo) | Contient un ensemble de boîtes aux lettres à usage spécial |
| [ImapMessageFlags](./imapmessageflags) | Représente les drapeaux associés au message. |
| [ImapMessageInfo](./imapmessageinfo) | Représente un objet de message Imap. |
| [ImapMessageInfoCollection](./imapmessageinfocollection) | Fournit un conteneur pour une collection de[`ImapMessageInfo`](../aspose.email.clients.imap/imapmessageinfo) objets |
| [ImapMonitoringErrorEventArgs](./imapmonitoringerroreventargs) | La classe contient des données d'événement d'erreur de surveillance. |
| [ImapMonitoringErrorEventHandler](./imapmonitoringerroreventhandler) | Représente la méthode qui gérera un événement d'erreur de surveillance d'imap |
| [ImapMonitoringEventArgs](./imapmonitoringeventargs) | La classe contient des données d'événement de surveillance. |
| [ImapMonitoringEventHandler](./imapmonitoringeventhandler) | Représente la méthode qui gérera un événement de surveillance imap |
| [ImapNamespace](./imapnamespace) | Représente l'espace de noms IMAP Plus de détails : https://tools.ietf.org/html/rfc2342 |
| [ImapPageInfo](./imappageinfo) | Contient des informations sur la page récupérée lorsque des méthodes de pagination sont utilisées. |
| [ImapQueryBuilder](./imapquerybuilder) | Représente le générateur de l'expression de recherche utilisée par le protocole IMAP. |
| [ImapQuota](./imapquota) | Contient des informations sur le quota de la ressource de boîte aux lettres. |
| [ImapQuotaRoot](./imapquotaroot) | Contient des informations sur la racine de quota pour la ressource de boîte aux lettres. |
| [MessageThreadResult](./messagethreadresult) | Contient le résultat des méthodes SORT ou THREAD Voir plus : https://tools.ietf.org/html/rfc5256 |
| [ModificationSequenceField](./modificationsequencefield) | Définit un ensemble de valeurs pour le champ sélectionné à rechercher. |
| [PageSettings](./pagesettings) | Les paramètres de la méthode ImapClient.ListMessagesByPage |
| [PageSettingsAsync](./pagesettingsasync) | Les paramètres de la méthode asynchrone ImapClient.BeginListMessagesByPage. |
| [RangeSeqSet](./rangeseqset) | Conteneur avec plage de valeurs à rechercher. |
| [ReadLinesTimeoutException](./readlinestimeoutexception) | Représente l'exception qui est levée lorsqu'une réponse du serveur ne peut pas être lue dans le délai spécifié. |
| [RestoreSettings](./restoresettings) | Les paramètres de la méthode ImapClient.Restore |
| [RestoreSettingsAsync](./restoresettingsasync) | Les paramètres de la méthode asynchrone ImapClient.Restore. |
| [SequenceSetBaseValue](./sequencesetbasevalue) | Classe de base pour différents conteneurs pour les valeurs à rechercher. |
| [SequenceSetField](./sequencesetfield) | Définit un ensemble de valeurs pour le champ sélectionné à rechercher. |
| [SimpleSeqSet](./simpleseqset) | Conteneur simple pour la valeur à rechercher. |
| [SortConditions](./sortconditions) | Fournit les conditions de recherche pour l'extension SORT. Compatibles avec l'extension SORT IMAP décrite sur https://tools.ietf.org/html/rfc5256 |
| [ThreadSearchConditions](./threadsearchconditions) | Fournit les conditions de recherche pour récupérer le fil de discussion. Compatible avec l'extension THREAD IMAP décrite sur https://tools.ietf.org/html/rfc5256 |
| [XGMThreadSearchConditions](./xgmthreadsearchconditions) | Fournit les conditions de recherche pour récupérer le fil de discussion. Compatible avec l'extension IMAP X-GM-EXT-1 décrite sur https://developers.google.com/gmail/imap/imap-extensions#checking_for_the_presence_of_extensions. |
## Interfaces

| Interface | La description |
| --- | --- |
| [IAsyncImapClient](./iasyncimapclient) | Permet aux applications d'accéder aux messages et de les manipuler à l'aide du protocole IMAP (Internet Message Access Protocol). |
| [IImapMonitoringState](./iimapmonitoringstate) | Contient l'état de surveillance du dossier. Cela peut être utilisé pour reprendre la surveillance du dossier à partir de place où il s'est arrêté lorsqu'une erreur s'est produite. Utilisation[`ResumeMonitoring`](../aspose.email.clients.imap/imapclient/resumemonitoring) méthode. |
## Énumération

| Énumération | La description |
| --- | --- |
| [ImapCommandResult](./imapcommandresult) | Énumère les résultats de la commande imap. |
| [ImapKnownAuthenticationType](./imapknownauthenticationtype) |  |
| [ImapListFields](./imaplistfields) | Champs pouvant être récupérés depuis le serveur |
| [ImapNamespaceType](./imapnamespacetype) | Représente le type d'espace de noms IMAP Plus de détails : https://tools.ietf.org/html/rfc2342 |
| [ImapSpecialFolderTypes](./imapspecialfoldertypes) | Représente l'énumération des boîtes aux lettres à usage spécial Plus de détails voir dans RFC6154 http://tools.ietf.org/html/rfc6154 |
| [ImapStatusCode](./imapstatuscode) | Représente les réponses d'état. |
| [ListFoldersOptions](./listfoldersoptions) | Les options de sélection de liste de dossiers Veuillez noter que ces options sont prises en charge si le serveur prend en charge RFC 5258 "IMAP LIST Command Extensions" Voir plus de détails dans https://tools.ietf.org/html/rfc5258 |
| [ListFoldersReturnOptions](./listfoldersreturnoptions) | Options de retour pour l'opération ListFolders Veuillez noter que ces options sont prises en charge si le serveur prend en charge RFC 5258 "IMAP LIST Command Extensions" Voir plus de détails dans https://tools.ietf.org/html/rfc5258 |
| [SortingKey](./sortingkey) | Critères de tri pour la commande "SORT" Voir plus : https://tools.ietf.org/html/rfc5256 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
