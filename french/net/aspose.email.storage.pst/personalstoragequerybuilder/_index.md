---
title: PersonalStorageQueryBuilder
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente le générateur de lexpression de recherche utilisée par pst.
type: docs
weight: 20310
url: /fr/net/aspose.email.storage.pst/personalstoragequerybuilder/
---
## PersonalStorageQueryBuilder class

Représente le générateur de l'expression de recherche utilisée par pst.

```csharp
public sealed class PersonalStorageQueryBuilder : MailQueryBuilder
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PersonalStorageQueryBuilder](personalstoragequerybuilder)() | Initialise une nouvelle instance du[`PersonalStorageQueryBuilder`](../personalstoragequerybuilder) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Bcc](../../aspose.email.tools.search/mailquerybuilder/bcc) { get; } | Obtient le champ qui permet de trouver les messages contenant la chaîne spécifiée dans le champ BCC de la structure de l'enveloppe. |
| [Body](../../aspose.email.tools.search/mailquerybuilder/body) { get; } | Obtient le champ qui permet de trouver les messages contenant la chaîne spécifiée dans le corps du message. |
| [Cc](../../aspose.email.tools.search/mailquerybuilder/cc) { get; } | Obtient le champ qui permet de trouver les messages contenant la chaîne spécifiée dans le champ CC de la structure de l'enveloppe. |
| [ContainerClass](../../aspose.email.storage.pst/personalstoragequerybuilder/containerclass) { get; } | Obtient les dossiers avec une classe de message spécifiée. |
| [ContentsCount](../../aspose.email.storage.pst/personalstoragequerybuilder/contentscount) { get; } | Rechercher des dossiers avec un nombre de contenus spécifié. |
| [DefaultEncoding](../../aspose.email.tools.search/mailquerybuilder/defaultencoding) { get; } | Obtient l'encodage par défaut (jeu de caractères) pour le générateur de requêtes |
| [FolderName](../../aspose.email.storage.pst/personalstoragequerybuilder/foldername) { get; } | Rechercher des dossiers avec un nom d'affichage spécifié. |
| [From](../../aspose.email.tools.search/mailquerybuilder/from) { get; } | Obtient le champ qui permet de trouver les messages contenant la chaîne spécifiée dans le champ FROM de la structure de l'enveloppe. |
| [Importance](../../aspose.email.storage.pst/personalstoragequerybuilder/importance) { get; } | Rechercher des messages avec une importance spécifiée. |
| [InternalDate](../../aspose.email.tools.search/mailquerybuilder/internaldate) { get; } | Récupère le champ qui permet de retrouver les messages par date interne. |
| [MessageClass](../../aspose.email.storage.pst/personalstoragequerybuilder/messageclass) { get; } | Obtient les messages avec une classe de message spécifiée. |
| [MessageId](../../aspose.email.storage.pst/personalstoragequerybuilder/messageid) { get; } | Obtient le champ qui permet de trouver les messages contenant la chaîne spécifiée dans le champ MessageId de la structure de l'enveloppe. |
| [MessageSize](../../aspose.email.storage.pst/personalstoragequerybuilder/messagesize) { get; } | Rechercher des messages avec une taille spécifiée. |
| [OnlyFoldersCreatedByUser](../../aspose.email.storage.pst/personalstoragequerybuilder/onlyfolderscreatedbyuser) { get; } | Obtient les dossiers créés par l'utilisateur, c'est-à-dire exclut tous les dossiers IPM standard. |
| [SentDate](../../aspose.email.tools.search/mailquerybuilder/sentdate) { get; } | Récupère le champ qui permet de retrouver les messages par date d'envoi. |
| [Subject](../../aspose.email.tools.search/mailquerybuilder/subject) { get; } | Obtient le champ qui permet de trouver les messages contenant la chaîne spécifiée dans le champ SUBJECT de la structure de l'enveloppe. |
| [Text](../../aspose.email.tools.search/mailquerybuilder/text) { get; } | Obtient le champ qui permet de trouver les messages qui contiennent la chaîne spécifiée dans les en-têtes (sujet, de, à, cc) et le corps du message. |
| [To](../../aspose.email.tools.search/mailquerybuilder/to) { get; } | Obtient le champ qui permet de trouver les messages contenant la chaîne spécifiée dans le champ TO de la structure de l'enveloppe. |
| [UnreadContentsCount](../../aspose.email.storage.pst/personalstoragequerybuilder/unreadcontentscount) { get; } | Rechercher des dossiers avec un nombre de contenus non lus spécifié. |

## Méthodes

| Nom | La description |
| --- | --- |
| [FindConversationThread](../../aspose.email.storage.pst/personalstoragequerybuilder/findconversationthread)(MessageInfo) | Trouve le fil de conversation. |
| [GetQuery](../../aspose.email.tools.search/mailquerybuilder/getquery)() | Obtient la requête. |
| [HasFlags](../../aspose.email.storage.pst/personalstoragequerybuilder/hasflags)(MapiMessageFlags) | Rechercher les messages avec les drapeaux spécifiés. |
| [HasNoFlags](../../aspose.email.storage.pst/personalstoragequerybuilder/hasnoflags)(MapiMessageFlags) | Rechercher les messages avec les drapeaux non spécifiés. |
| [HasNoSubfolders](../../aspose.email.storage.pst/personalstoragequerybuilder/hasnosubfolders)() | Rechercher les dossiers qui ne contiennent pas de sous-dossiers. |
| [HasSubfolders](../../aspose.email.storage.pst/personalstoragequerybuilder/hassubfolders)() | Rechercher les dossiers contenant des sous-dossiers. |
| [Or](../../aspose.email.tools.search/mailquerybuilder/or)(MailQuery, MailQuery) | Rechercher les messages qui correspondent à l'une ou l'autre des clés de recherche. Fournit une disjonction entre deux expressions (OU). |

### Voir également

* class [MailQueryBuilder](../../aspose.email.tools.search/mailquerybuilder)
* espace de noms [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
