---
title: RebuildResults
second_title: Référence de l'API Aspose.Email pour .NET
description: Force le serveur à reconstruire le dossier de recherche 2 qui correspond à une requête donnée. Les résultats de la recherche cest-à-dire lensemble de résultats sont stockés dans un dossier de recherche sur le serveur. De cette façon lorsquun client revient avec la même requête mais une nouvelle plage de lignes les lignes sont extraites du jeu de résultats actuellement stocké dans le dossier de recherche. Lensemble de résultats na pas besoin dêtre reconstruit. Le dossier de recherche reste inchangé jusquà ce que le client effectue lune des actions suivantes pour mettre à jour lensemble de résultats  - Envoie une requête de recherche en spécifiant une nouvelle requête. Dans ce cas le dossier de recherche est automatiquement reconstruit. Le nœud RebuildResults na pas besoin dêtre inclus. - Envoie une demande de recherche qui inclut le nœud RebuildResults. Dans ce cas le serveur est obligé de reconstruire le dossier de recherche. Si un nouvel élément est ajouté lélément napparaît pas dans le jeu de résultats tant que le jeu de résultats nest pas mis à jour. Si un élément est supprimé le serveur filtrera lélément supprimé du jeu de résultats. Le client DEVRAIT envoyer une nouvelle requête de recherche avec la requête donnée et inclure loption RebuildResults tous les quelques jours pour garantir des résultats précis pour cette requête.
type: docs
weight: 90
url: /fr/net/aspose.email.clients.activesync.transportlayer/searchoptions/rebuildresults/
---
## SearchOptions.RebuildResults property

Force le serveur à reconstruire le dossier de recherche (2) qui correspond à une requête donnée. Les résultats de la recherche (c'est-à-dire l'ensemble de résultats) sont stockés dans un dossier de recherche sur le serveur. De cette façon, lorsqu'un client revient avec la même requête mais une nouvelle plage de lignes, les lignes sont extraites du jeu de résultats actuellement stocké dans le dossier de recherche. L'ensemble de résultats n'a pas besoin d'être reconstruit. Le dossier de recherche reste inchangé jusqu'à ce que le client effectue l'une des actions suivantes pour mettre à jour l'ensemble de résultats : - Envoie une requête de recherche, en spécifiant une nouvelle requête. Dans ce cas, le dossier de recherche est automatiquement reconstruit. Le nœud RebuildResults n'a pas besoin d'être inclus. - Envoie une demande de recherche qui inclut le nœud RebuildResults. Dans ce cas, le serveur est obligé de reconstruire le dossier de recherche. Si un nouvel élément est ajouté, l'élément n'apparaît pas dans le jeu de résultats tant que le jeu de résultats n'est pas mis à jour. Si un élément est supprimé, le serveur filtrera l'élément supprimé du jeu de résultats. Le client DEVRAIT envoyer une nouvelle requête de recherche avec la requête donnée et inclure l'option RebuildResults tous les quelques jours pour garantir des résultats précis pour cette requête.

```csharp
public bool RebuildResults { get; set; }
```

### Voir également

* class [SearchOptions](../../searchoptions)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../searchoptions)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->