---
title: SyncCollectionRequest
second_title: Référence de l'API Aspose.Email pour .NET
description: La classe contient des commandes et des options qui sappliquent à une collection particulière.
type: docs
weight: 2190
url: /fr/net/aspose.email.clients.activesync.transportlayer/synccollectionrequest/
---
## SyncCollectionRequest class

La classe contient des commandes et des options qui s'appliquent à une collection particulière.

```csharp
public class SyncCollectionRequest
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [SyncCollectionRequest](synccollectionrequest)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/collectionid) { get; set; } | Spécifie l'ID de serveur du dossier à synchroniser. |
| [Commands](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/commands) { get; set; } | Contient les opérations qui s'appliquent à une collection. Les opérations disponibles sont Ajouter, Supprimer, Modifier, Récupérer et SoftDelete. |
| [ConversationMode](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/conversationmode) { get; set; } | Spécifie s'il faut inclure les éléments qui sont inclus dans la modalité de conversation dans les résultats de la réponse Sync. La définition de la valeur de l'élément ConversationMode sur TRUE entraîne la récupération de tous les e-mails qui correspondent aux conversations reçues dans le filtre de date spécifié. Cependant, bien que le corps des e-mails en dehors de ce filtre temporel ne soit pas récupéré, les aperçus de texte seront récupérés si les aperçus ont été demandés. La définition de la valeur de l'élément ConversationMode sur FALSE dans une demande de synchronisation entraîne la synchronisation de éléments qui répondent aux critères de la valeur de l'élément FilterType (section 2.2.3.64). La définition de la valeur de l'élément ConversationMode sur TRUE élargit le jeu de résultats pour inclure également tous les éléments avec des valeurs email2:ConversationId ([MS-ASEMAIL] section 2.2.2.14) identiques à celles du jeu de résultats FilterType. La valeur de l'élément ConversationMode n'a aucun impact sur les éléments en dehors de la collection spécifiée par l'élément CollectionId (section 2.2.3.30.5) ; le jeu de résultats est toujours limité aux éléments de la collection spécifiée. La valeur de l'élément ConversationMode limite ou étend uniquement les résultats déterminés par la valeur de l'élément FilterType. |
| [DeletesAsMoves](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/deletesasmoves) { get; set; } | Requêtes indiquant que tous les éléments supprimés DEVRAIENT être déplacés vers le dossier Éléments supprimés. Si l'élément DeletesAsMoves est défini sur false, la suppression est définitive. Si le client souhaite supprimer définitivement des éléments, la demande DOIT inclure l'élément DeleteAsMoves avec une valeur FALSE. La valeur TRUE, qui est la valeur par défaut, indique que tous les éléments supprimés sont déplacés vers le dossier Éléments supprimés. |
| [GetChanges](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/getchanges) { get; set; } | Demande au serveur d'inclure dans sa réponse toute modification en attente de la collection spécifiée par l'élément ServerId (section 2.2.3.151.6). S'il y a eu des modifications depuis la dernière synchronisation, la réponse du serveur inclut un élément Commands (section 2.2.3.32) qui contient des ajouts, des suppressions et des modifications. Si le client ne souhaite pas que les modifications du serveur soient renvoyées, la demande DOIT inclure l'élément GetChanges avec la valeur FALSE. Une valeur TRUE indique que le client souhaite que les modifications du serveur soient renvoyées. La valeur TRUE est supposée lorsque l'élément GetChanges est vide. Lorsque l'élément GetChanges n'est pas présent dans la requête, le comportement dépend de la valeur de l'élément SyncKey, comme spécifié dans la section 2.2.3.166.4. Si l'élément SyncKey a une valeur de 0, la demande est traitée comme si l'élément GetChanges était défini sur FALSE. Si l'élément SyncKey a une valeur différente de zéro, la demande est traitée comme si l'élément GetChanges était défini. à VRAI. |
| [Options](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/options) { get; } | Spécifie les options qui contrôlent certains aspects de la façon dont la synchronisation est effectuée. Nombre autorisé 0...2. Les options de synchronisation permettent au client de spécifier les paramètres de troncature et de contenu. Ces paramètres sont encapsulés dans un élément enfant airsyncbase:BodyPreference, comme spécifié dans la section 2.2.2.7 de [MS-ASAIRS]. Étant donné que les options de synchronisation sont spécifiées sur une collection, le client peut spécifier une valeur d'élément airsyncbase:BodyPreference unique pour chaque collection en cours de synchronisation. Pour plus de détails sur l'élément airsyncbase:BodyPreference, voir [MS-ASAIRS] section 2.2. 2.7. Le serveur conserve le bloc Options à travers les requêtes, en utilisant un concept appelé "options collantes". Si le bloc Options n'est pas inclus dans une requête, le bloc Options précédent est utilisé. Chaque fois que le client spécifie de nouvelles options en incluant un bloc Options dans la requête, le serveur DOIT remplacer le bloc Options d'origine par le nouveau bloc Options. Si deux éléments Options sont inclus dans une seule requête de commande Sync, l'un des éléments Options DOIT spécifiez les options de synchronisation pour la classe SMS, tandis que l'autre élément Options spécifie les options pour la classe par défaut du dossier donné. |
| [Supported](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/supported) { get; } | Les éléments de la classe Contact et de la classe Calendar qui ne sont pas fantômes peuvent être inclus en tant qu'éléments enfants de l'élément Supported. Pour plus de détails sur l'utilisation des propriétés fantômes, voir la section 2.2.3.154. |
| [SyncKey](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/synckey) { get; set; } | La valeur SyncKey est utilisée par le serveur pour marquer l'état de synchronisation d'une collection. Une clé de synchronisation de valeur 0 (zéro) initialise l'état de synchronisation sur le serveur et provoque une synchronisation complète de la collection. |
| [WindowSize](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/windowsize) { get; set; } | Spécifie un nombre maximum d'éléments modifiés dans une collection ou une demande qui DEVRAIT être inclus dans la réponse de synchronisation. Si WindowSize n'est pas défini, le serveur se comporte comme si un élément WindowSize avec une valeur de 100 était soumis. Le serveur interprète la valeur 0 (zéro) et les valeurs supérieures à 512 comme 512. |

### Voir également

* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
