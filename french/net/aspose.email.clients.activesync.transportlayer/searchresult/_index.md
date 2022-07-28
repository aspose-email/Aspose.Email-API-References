---
title: SearchResult
second_title: Référence de l'API Aspose.Email pour .NET
description: Conteneur pour un élément de boîte aux lettres correspondant individuel. Lorsque le magasin recherché est la boîte aux lettres  - Il existe un élément de résultat pour chaque correspondance trouvée dans la boîte aux lettres. Si aucune correspondance nest trouvée un élément Result vide est présent dans lélément Conteneur Store du XML de réponse. - Dans lélément Result lélément Properties contient une liste des propriétés demandées pour lélément de boîte aux lettres. Lorsque le magasin qui est faisant lobjet de la recherche est la bibliothèque de documents  - Le premier résultat renvoyé dans la réponse de recherche correspond aux métadonnées du dossier racine ou de lélément vers lequel la valeur LinkId pointe. Le client peut choisir dignorer cette entrée sil ne lexige pas. - Si la valeur de lélément documentlibraryLinkId dans la requête pointe vers un dossier les propriétés de métadonnées du dossier sont renvoyées en tant que premier élément et le contenu de le dossier sont renvoyés en tant que résultats ultérieurs. La plage sapplique à ces résultats sans différence  par exemple lindex 0 serait toujours pour lélément racine vers lequel le lien pointe. - Si la valeur de lélément documentlibraryLinkId dans la requête pointe vers un élément un seul résultat est renvoyé  les métadonnées de lélément. - À lintérieur de lélément Result lélément Properties contient une liste des propriétés demandées pour lélément de boîte aux lettres.
type: docs
weight: 2010
url: /fr/net/aspose.email.clients.activesync.transportlayer/searchresult/
---
## SearchResult class

Conteneur pour un élément de boîte aux lettres correspondant individuel. Lorsque le magasin recherché est la boîte aux lettres : - Il existe un élément de résultat pour chaque correspondance trouvée dans la boîte aux lettres. Si aucune correspondance n'est trouvée, un élément Result vide est présent dans l'élément Conteneur Store du XML de réponse. - Dans l'élément Result, l'élément Properties contient une liste des propriétés demandées pour l'élément de boîte aux lettres. Lorsque le magasin qui est faisant l'objet de la recherche est la bibliothèque de documents : - Le premier résultat renvoyé dans la réponse de recherche correspond aux métadonnées du dossier racine ou de l'élément vers lequel la valeur LinkId pointe. Le client peut choisir d'ignorer cette entrée s'il ne l'exige pas. - Si la valeur de l'élément documentlibrary:LinkId dans la requête pointe vers un dossier, les propriétés de métadonnées du dossier sont renvoyées en tant que premier élément, et le contenu de le dossier sont renvoyés en tant que résultats ultérieurs. La plage s'applique à ces résultats sans différence ; par exemple, l'index 0 serait toujours pour l'élément racine vers lequel le lien pointe. - Si la valeur de l'élément documentlibrary:LinkId dans la requête pointe vers un élément, un seul résultat est renvoyé : les métadonnées de l'élément. - À l'intérieur de l'élément Result, l'élément Properties contient une liste des propriétés demandées pour l'élément de boîte aux lettres.

```csharp
public class SearchResult
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [SearchResult](searchresult)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [Class](../../aspose.email.clients.activesync.transportlayer/searchresult/class) { get; set; } | Identifie la classe de l'article. |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/searchresult/collectionid) { get; } | Spécifie les dossiers dans lesquels l'élément a été trouvé. |
| [LongId](../../aspose.email.clients.activesync.transportlayer/searchresult/longid) { get; set; } | Spécifie un identifiant unique attribué par le serveur à chaque ensemble de résultats renvoyé. La valeur de LongId peut être utilisée comme ID long spécifié dans la demande de commande ItemOperations, la demande de commande SmartReply, la demande de commande SmartForward ou la demande de commande MeetingResponse pour référencer l'ensemble de résultats. Le client DOIT stocker la valeur de LongId sous la forme d'une chaîne opaque de 256 caractères maximum. |
| [Properties](../../aspose.email.clients.activesync.transportlayer/searchresult/properties) { get; set; } | Les propriétés de réponse de la commande de recherche sont un conteneur pour les propriétés qui s'appliquent à une entrée individuelle qui correspond à la chaîne de recherche de l'élément Query. Par exemple, l'élément Propriétés contient un élément pour chaque propriété GAL à valeur texte non vide qui est attachée à l'entrée GAL correspondante. Seules les propriétés associées à l'entrée GAL spécifique sont renvoyées ; par conséquent, différents ensembles de propriétés peuvent être renvoyés dans la réponse XML pour différentes entrées GAL correspondantes. Chaque élément du conteneur Propriétés est limité à l'espace de noms approprié qui est spécifié dans l'élément de recherche de niveau supérieur. |

### Voir également

* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
