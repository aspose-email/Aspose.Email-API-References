---
title: ExchangeQueryBuilder
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente le générateur de lexpression de recherche basée sur les filtres de recherche utilisés par le protocole Exchange.
type: docs
weight: 3440
url: /fr/net/aspose.email.clients.exchange/exchangequerybuilder/
---
## ExchangeQueryBuilder class

Représente le générateur de l'expression de recherche basée sur les filtres de recherche utilisés par le protocole Exchange.

```csharp
public sealed class ExchangeQueryBuilder : MailQueryBuilder
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ExchangeQueryBuilder](exchangequerybuilder)() | Initialise une nouvelle instance du[`ExchangeQueryBuilder`](../exchangequerybuilder) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Appointment](../../aspose.email.clients.exchange/exchangequerybuilder/appointment) { get; } | Obtient un objet avec des propriétés de rendez-vous pour créer une requête |
| [Bcc](../../aspose.email.tools.search/mailquerybuilder/bcc) { get; } | Obtient le champ qui permet de trouver les messages contenant la chaîne spécifiée dans le champ BCC de la structure de l'enveloppe. |
| [Body](../../aspose.email.tools.search/mailquerybuilder/body) { get; } | Obtient le champ qui permet de trouver les messages contenant la chaîne spécifiée dans le corps du message. |
| [Cc](../../aspose.email.tools.search/mailquerybuilder/cc) { get; } | Obtient le champ qui permet de trouver les messages contenant la chaîne spécifiée dans le champ CC de la structure de l'enveloppe. |
| [Contact](../../aspose.email.clients.exchange/exchangequerybuilder/contact) { get; } | Obtient un objet avec des propriétés de contact pour créer une requête |
| [ContentClass](../../aspose.email.clients.exchange/exchangequerybuilder/contentclass) { get; } | Obtient des éléments avec une classe de contenu spécifiée. |
| [DefaultEncoding](../../aspose.email.tools.search/mailquerybuilder/defaultencoding) { get; } | Obtient l'encodage par défaut (jeu de caractères) pour le générateur de requêtes |
| [ExtendedProperties](../../aspose.email.clients.exchange/exchangequerybuilder/extendedproperties) { get; } | Obtient un dictionnaire avec des paires de descripteurs de propriété et un champ de comparaison pour effectuer une recherche par propriétés étendues. |
| [From](../../aspose.email.tools.search/mailquerybuilder/from) { get; } | Obtient le champ qui permet de trouver les messages contenant la chaîne spécifiée dans le champ FROM de la structure de l'enveloppe. |
| [InternalDate](../../aspose.email.tools.search/mailquerybuilder/internaldate) { get; } | Récupère le champ qui permet de retrouver les messages par date interne. |
| [ItemSize](../../aspose.email.clients.exchange/exchangequerybuilder/itemsize) { get; } | Obtient le champ qui permet de trouver des éléments avec une taille spécifiée. |
| [MessageId](../../aspose.email.clients.exchange/exchangequerybuilder/messageid) { get; } | Obtient le champ qui permet de trouver les messages contenant la chaîne spécifiée dans le champ MessageId de la structure de l'enveloppe. |
| [SentDate](../../aspose.email.tools.search/mailquerybuilder/sentdate) { get; } | Récupère le champ qui permet de retrouver les messages par date d'envoi. |
| [Subject](../../aspose.email.tools.search/mailquerybuilder/subject) { get; } | Obtient le champ qui permet de trouver les messages contenant la chaîne spécifiée dans le champ SUBJECT de la structure de l'enveloppe. |
| [TaskStatus](../../aspose.email.clients.exchange/exchangequerybuilder/taskstatus) { get; } | Obtient le champ qui permet de trouver les tâches qui contiennent le statut spécifié. Compatibilité serveur : Exchange 2010 et supérieur |
| [Text](../../aspose.email.tools.search/mailquerybuilder/text) { get; } | Obtient le champ qui permet de trouver les messages qui contiennent la chaîne spécifiée dans les en-têtes (sujet, de, à, cc) et le corps du message. |
| [To](../../aspose.email.tools.search/mailquerybuilder/to) { get; } | Obtient le champ qui permet de trouver les messages contenant la chaîne spécifiée dans le champ TO de la structure de l'enveloppe. |

## Méthodes

| Nom | La description |
| --- | --- |
| [GetQuery](../../aspose.email.tools.search/mailquerybuilder/getquery)() | Obtient la requête. |
| [HasFlags](../../aspose.email.clients.exchange/exchangequerybuilder/hasflags)(ExchangeMessageFlag) | Rechercher les messages avec les drapeaux spécifiés. |
| [HasNoFlags](../../aspose.email.clients.exchange/exchangequerybuilder/hasnoflags)(ExchangeMessageFlag) | Rechercher les messages avec les drapeaux non spécifiés. |
| [Or](../../aspose.email.tools.search/mailquerybuilder/or)(MailQuery, MailQuery) | Rechercher les messages qui correspondent à l'une ou l'autre des clés de recherche. Fournit une disjonction entre deux expressions (OU). |

### Voir également

* class [MailQueryBuilder](../../aspose.email.tools.search/mailquerybuilder)
* espace de noms [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
