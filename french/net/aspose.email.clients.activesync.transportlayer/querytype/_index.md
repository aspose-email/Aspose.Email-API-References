---
title: QueryType
second_title: Référence de l'API Aspose.Email pour .NET
description: Spécifie les mots-clés à utiliser pour faire correspondre les entrées du magasin recherché. La valeur de la requête est utilisée comme modèle de correspondance de chaîne de préfixe et renvoie les entrées qui correspondent au début de la chaîne. Par exemple la recherche de John correspondrait à John Frum ou Barry Johnson mais ne correspondrait pas à James Littlejohn. Toutes les propriétés de texte non vides dans la GAL qui sont indexées à laide de lANR sont comparées à lélément Query évaluer. Les comparaisons de recherche sont effectuées à laide dune correspondance insensible à la casse. Pour une recherche dans la bibliothèque de documents Windows SharePoint Services ce protocole prend en charge les requêtes de la forme suivante  LinkId  valeur où valeur spécifie lURL de lélément ou du dossier et LinkId indique que la valeur doit être comparée à la propriété dID de lien. Pour la recherche de boîte aux lettres la syntaxe de la requête est la suivante  - Les dossiers peuvent être spécifiés des manières suivantes  ID spécifié Dossier et sous-dossiers spécifiés Tous les dossiers de messagerie y compris les brouillons Boîte de réception et sous-dossiers Boîte denvoi et Éléments envoyés - La requête de mot-clé de base peut être composée des éléments suivants  Lopérateur de base  Et section 2.2.3.10 Un filtre dateTime spécifié à laide de GreaterThan section 2.2.3.78 et LessThan éléments section 2.2.3.87 éléments FreeText section 2.2.3.73 qui contiennent des mots-clés La requête de mot-clé de base est exécutée sur toutes les propriétés indexées.
type: docs
weight: 1780
url: /fr/net/aspose.email.clients.activesync.transportlayer/querytype/
---
## QueryType class

Spécifie les mots-clés à utiliser pour faire correspondre les entrées du magasin recherché. La valeur de la requête est utilisée comme modèle de correspondance de chaîne de préfixe et renvoie les entrées qui correspondent au début de la chaîne. Par exemple, la recherche de "John" correspondrait à "John Frum" ou "Barry Johnson", mais ne correspondrait pas à "James Littlejohn". Toutes les propriétés de texte non vides dans la GAL qui sont indexées à l'aide de l'ANR sont comparées à l'élément Query évaluer. Les comparaisons de recherche sont effectuées à l'aide d'une correspondance insensible à la casse. Pour une recherche dans la bibliothèque de documents Windows SharePoint Services, ce protocole prend en charge les requêtes de la forme suivante : LinkId == valeur, où valeur spécifie l'URL de l'élément ou du dossier et LinkId indique que la valeur doit être comparée à la propriété d'ID de lien. Pour la recherche de boîte aux lettres, la syntaxe de la requête est la suivante : - Les dossiers peuvent être spécifiés des manières suivantes : ID spécifié Dossier et sous-dossiers spécifiés Tous les dossiers de messagerie, y compris les brouillons, Boîte de réception et sous-dossiers, Boîte d'envoi et Éléments envoyés - La requête de mot-clé de base peut être composée des éléments suivants : L'opérateur de base : Et (section 2.2.3.10) Un filtre dateTime spécifié à l'aide de GreaterThan (section 2.2.3.78) et LessThan éléments (section 2.2.3.87) éléments FreeText (section 2.2.3.73) qui contiennent des mots-clés La requête de mot-clé de base est exécutée sur toutes les propriétés indexées.

```csharp
public class QueryType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [QueryType](querytype)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [Class](../../aspose.email.clients.activesync.transportlayer/querytype/class) { get; } | Identifie la classe de l'élément. Les valeurs d'élément airsync:Class valides sont : - Tasks - Email - Calendar - Contacts - Notes - SMS Les classes suivantes sont prises en charge pour les recherches de boîte aux lettres lorsque la version du protocole est 12.1 : Email, Calendar, Contacts, Tâches. Les classes SMS et Notes ne sont disponibles que si la version du protocole est 14.0 ou 14.1. La requête Search peut inclure un ou plusieurs éléments Class dans la requête pour limiter le type de données incluses dans la réponse Search. Si un ou plusieurs éléments Class ne sont pas inclus dans la requête de recherche, le serveur renverra toutes les classes prises en charge. Si Class est inclus en tant qu'enfant d'un élément autre que l'élément And, le serveur répond avec une valeur Status de 8 (RechercheTropComplexe). |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/querytype/collectionid) { get; } | Spécifie le dossier dans lequel effectuer la recherche. Si le DeepTraversal est présent, il s'applique à tous les dossiers sous chaque CollectionId. Si le CollectionId est inclus en tant qu'enfant d'un élément autre que And, le serveur répond avec une valeur Status de 8 (SearchTooComplex). |
| [ConversationId](../../aspose.email.clients.activesync.transportlayer/querytype/conversationid) { get; set; } | Spécifie la conversation à rechercher. La valeur est un GUID. Le ConversationId n'est pas pris en charge lorsque la version du protocole est 12.1. Si le ConversationId est inclus en tant qu'enfant d'un élément autre que l'élément And, le serveur répond avec une valeur Status de 8 (SearchTooComplex). |
| [FreeText](../../aspose.email.clients.activesync.transportlayer/querytype/freetext) { get; set; } | Spécifie une valeur de chaîne à rechercher. Si la propriété FreeText est définie autre que la propriété And, le serveur répond avec une valeur Status de 8 (SearchTooComplex). |
| [GreaterThan](../../aspose.email.clients.activesync.transportlayer/querytype/greaterthan) { get; set; } | Spécifie une propriété et une valeur qui sont comparées pour une condition "Supérieur à" lors d'une recherche. |
| [LessThan](../../aspose.email.clients.activesync.transportlayer/querytype/lessthan) { get; set; } | Spécifie une propriété et une valeur qui sont comparées pour une condition « Inférieur à » lors d'une recherche. |

### Voir également

* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
