---
title: LogEntry
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente un message de journal. Contient les propriétés communes requises pour tous les messages de journal.
type: docs
weight: 20520
url: /fr/net/aspose.email.tools.logging/logentry/
---
## LogEntry class

Représente un message de journal. Contient les propriétés communes requises pour tous les messages de journal.

```csharp
public class LogEntry
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [LogEntry](logentry#constructor)() | Initialiser une nouvelle instance d'un[`LogEntry`](../logentry) classe. |
| [LogEntry](logentry#constructor_1)(byte[]) | Créer une nouvelle instance de[`LogEntry`](../logentry) avec un ensemble complet de paramètres de constructeur |
| [LogEntry](logentry#constructor_5)(string) | Initialiser une nouvelle instance d'un[`LogEntry`](../logentry) classe. |
| [LogEntry](logentry#constructor_3)(byte[], Encoding) | Créer une nouvelle instance de[`LogEntry`](../logentry) avec un ensemble complet de paramètres de constructeur |
| [LogEntry](logentry#constructor_2)(byte[], IDictionary&lt;string, string&gt;) | Créer une nouvelle instance de[`LogEntry`](../logentry) avec un ensemble complet de paramètres de constructeur |
| [LogEntry](logentry#constructor_9)(string, DateTime) | Initialiser une nouvelle instance d'un[`LogEntry`](../logentry) classe. |
| [LogEntry](logentry#constructor_10)(string, Exception) | Initialiser une nouvelle instance d'un[`LogEntry`](../logentry) classe. |
| [LogEntry](logentry#constructor_8)(string, IDictionary&lt;string, string&gt;) | Créer une nouvelle instance de[`LogEntry`](../logentry) avec un ensemble complet de paramètres de constructeur |
| [LogEntry](logentry#constructor_6)(string, LogLevel) | Initialiser une nouvelle instance d'un[`LogEntry`](../logentry) classe. |
| [LogEntry](logentry#constructor_4)(byte[], Encoding, IDictionary&lt;string, string&gt;) | Créer une nouvelle instance de[`LogEntry`](../logentry) avec un ensemble complet de paramètres de constructeur |
| [LogEntry](logentry#constructor_11)(string, Exception, LogLevel) | Initialiser une nouvelle instance d'un[`LogEntry`](../logentry) classe. |
| [LogEntry](logentry#constructor_7)(string, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) | Créer une nouvelle instance de[`LogEntry`](../logentry) avec un ensemble complet de paramètres de constructeur |
| [LogEntry](logentry#constructor_12)(string, Exception, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) | Créer une nouvelle instance de[`LogEntry`](../logentry) avec un ensemble complet de paramètres de constructeur |

## Propriétés

| Nom | La description |
| --- | --- |
| [AppDomainName](../../aspose.email.tools.logging/logentry/appdomainname) { get; set; } | L'AppDomain dans lequel nous exécutons |
| [BinaryDataMessage](../../aspose.email.tools.logging/logentry/binarydatamessage) { get; set; } | Corps du message binaire à consigner. |
| [Category](../../aspose.email.tools.logging/logentry/category) { get; set; } | Nom de catégorie utilisé pour acheminer l'entrée de journal vers un ou plusieurs récepteurs. |
| [ContextualProperties](../../aspose.email.tools.logging/logentry/contextualproperties) { get; set; } | Dictionnaire des couples clé/valeur à enregistrer. |
| [ErrorMessages](../../aspose.email.tools.logging/logentry/errormessages) { get; } | Obtient le message d'erreur avec le[`LogEntry`](../logentry) |
| [EventId](../../aspose.email.tools.logging/logentry/eventid) { get; set; } | Numéro ou identifiant de l'événement. |
| [InnerException](../../aspose.email.tools.logging/logentry/innerexception) { get; set; } | Obtient ou définit l'objet d'exception interne. |
| [MachineName](../../aspose.email.tools.logging/logentry/machinename) { get; set; } | Nom de l'ordinateur. |
| [Message](../../aspose.email.tools.logging/logentry/message) { get; set; } | Corps du message à consigner. Valeur de la méthode ToString() de l'objet message. |
| [MessageEncoding](../../aspose.email.tools.logging/logentry/messageencoding) { get; set; } | Encodage pour le corps du message binaire |
| [SequenceId](../../aspose.email.tools.logging/logentry/sequenceid) { get; } | L'identifiant unique de l'événement de journal qui est généré automatiquement et augmente de manière monotone. |
| [Severity](../../aspose.email.tools.logging/logentry/severity) { get; set; } | Gravité de l'entrée du journal en tant que[`Severity`](./severity) énumération. (Non spécifié, Information, Avertissement ou Erreur). |
| [ThreadName](../../aspose.email.tools.logging/logentry/threadname) { get; set; } | Le nom du thread .NET. |
| [TimeStamp](../../aspose.email.tools.logging/logentry/timestamp) { get; set; } | Date et heure du message d'entrée de journal. |
| [Title](../../aspose.email.tools.logging/logentry/title) { get; set; } | Description supplémentaire du message d'entrée de journal. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [AddErrorMessage](../../aspose.email.tools.logging/logentry/adderrormessage)(string) | Ajouter un message d'erreur ou d'avertissement au début du générateur de chaînes de messages. Utilisé par le distributeur pour enregistrer les problèmes. |
| [Clone](../../aspose.email.tools.logging/logentry/clone)() | Crée un nouveau[`LogEntry`](../logentry) c'est une copie de l'instance actuelle. |
| override [ToString](../../aspose.email.tools.logging/logentry/tostring)() |  |

### Voir également

* espace de noms [Aspose.Email.Tools.Logging](../../aspose.email.tools.logging)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
