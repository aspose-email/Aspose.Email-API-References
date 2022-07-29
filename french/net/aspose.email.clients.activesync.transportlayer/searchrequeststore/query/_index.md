---
title: Query
second_title: Référence de l'API Aspose.Email pour .NET
description: Spécifie les mots-clés à utiliser pour faire correspondre les entrées du magasin recherché. La valeur de la requête est utilisée comme modèle de correspondance de chaîne de préfixe et renvoie les entrées qui correspondent au début de la chaîne. Par exemple la recherche de John correspondrait à John Frum ou Barry Johnson mais ne correspondrait pas à James Littlejohn. Toutes les propriétés de texte non vides dans la GAL qui sont indexées à laide de lANR sont comparées à lélément Query évaluer. Les comparaisons de recherche sont effectuées à laide dune correspondance insensible à la casse. Pour une recherche dans la bibliothèque de documents Windows SharePoint Services ce protocole prend en charge les requêtes de la forme suivante  LinkId  valeur où la valeur spécifie lURL de lélément ou du dossier et LinkId indique que la valeur doit être comparée à la propriété dID de lien. Pour la recherche de boîte aux lettres la syntaxe de la requête est la suivante  - Les dossiers peuvent être spécifiés des manières suivantes  ID spécifié Dossier et sous-dossiers spécifiés Tous les dossiers de messagerie y compris les brouillons Boîte de réception et sous-dossiers Boîte denvoi et Éléments envoyés - La requête de mot-clé de base peut être composée des éléments suivants  Lopérateur de base  Et section 2.2.3.10 Un filtre dateTime spécifié à laide de GreaterThan section 2.2.3.78 et LessThan éléments section 2.2.3.87 éléments FreeText section 2.2.3.73 qui contiennent des mots-clés La requête de mot-clé de base est exécutée sur toutes les propriétés indexées.
type: docs
weight: 40
url: /fr/net/aspose.email.clients.activesync.transportlayer/searchrequeststore/query/
---
## SearchRequestStore.Query property

Spécifie les mots-clés à utiliser pour faire correspondre les entrées du magasin recherché. La valeur de la requête est utilisée comme modèle de correspondance de chaîne de préfixe et renvoie les entrées qui correspondent au début de la chaîne. Par exemple, la recherche de "John" correspondrait à "John Frum" ou "Barry Johnson", mais ne correspondrait pas à "James Littlejohn". Toutes les propriétés de texte non vides dans la GAL qui sont indexées à l'aide de l'ANR sont comparées à l'élément Query évaluer. Les comparaisons de recherche sont effectuées à l'aide d'une correspondance insensible à la casse. Pour une recherche dans la bibliothèque de documents Windows SharePoint Services, ce protocole prend en charge les requêtes de la forme suivante : LinkId == valeur, où la valeur spécifie l'URL de l'élément ou du dossier et LinkId indique que la valeur doit être comparée à la propriété d'ID de lien. Pour la recherche de boîte aux lettres, la syntaxe de la requête est la suivante : - Les dossiers peuvent être spécifiés des manières suivantes : ID spécifié Dossier et sous-dossiers spécifiés Tous les dossiers de messagerie, y compris les brouillons, Boîte de réception et sous-dossiers, Boîte d'envoi et Éléments envoyés - La requête de mot-clé de base peut être composée des éléments suivants : L'opérateur de base : Et (section 2.2.3.10) Un filtre dateTime spécifié à l'aide de GreaterThan (section 2.2.3.78) et LessThan éléments (section 2.2.3.87) éléments FreeText (section 2.2.3.73) qui contiennent des mots-clés La requête de mot-clé de base est exécutée sur toutes les propriétés indexées.

```csharp
public SearchQuery Query { get; set; }
```

### Voir également

* class [SearchQuery](../../searchquery)
* class [SearchRequestStore](../../searchrequeststore)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../searchrequeststore)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->