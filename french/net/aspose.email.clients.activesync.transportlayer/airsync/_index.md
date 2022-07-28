---
title: AirSync
second_title: Référence de l'API Aspose.Email pour .NET
description: Espace de noms AirSync du protocole ActiveSync
type: docs
weight: 960
url: /fr/net/aspose.email.clients.activesync.transportlayer/airsync/
---
## AirSync enumeration

Espace de noms AirSync du protocole ActiveSync

```csharp
public enum AirSync
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| Sync | `5` | L'élément Sync est un élément obligatoire dans les demandes et réponses de commande Sync qui identifie le corps du HTTP POST comme contenant une commande Sync (section 2.2.2.19). Il s'agit de l'élément de niveau supérieur dans le flux XML. |
| Responses | `6` | Contient les réponses aux opérations qui sont traitées par le serveur. |
| Add | `7` | Crée un nouvel objet dans une collection sur le client ou sur le serveur. |
| Change | `8` | Modifie les propriétés d'un objet existant sur l'appareil client ou le serveur. |
| Delete | `9` | Supprime un objet sur l'appareil client ou le serveur. L'objet est identifié par son élément ServerId. |
| Fetch | `10` | Utilisé pour demander les données d'application d'un élément qui a été tronqué dans une réponse de synchronisation du serveur. |
| SyncKey | `11` | Contient une valeur utilisée par le serveur pour marquer l'état de synchronisation d'une collection. |
| ClientId | `12` | Contient un identifiant unique (généralement un nombre entier) généré par le client pour identifier temporairement un nouvel objet créé à l'aide de l'élément Add. |
| ServerId | `13` | Il représente un identifiant unique attribué par le serveur à chaque objet pouvant être synchronisé. |
| Status | `14` | Indique la raison de l'échec d'une demande de commande. |
| Collection | `15` | Contient des commandes et des options qui s'appliquent à une collection particulière. |
| Class | `16` | Identifie la classe de l'élément ajouté à la collection. |
| CollectionId | `18` | Spécifie l'ID de serveur du dossier à synchroniser. |
| GetChanges | `19` | Demande au serveur d'inclure dans sa réponse toute modification en attente de la collection spécifiée par l'élément ServerId (section 2.2.3.151.6). |
| MoreAvailable | `20` | Indique qu'il y a plus de modifications que le nombre demandé dans l'élément WindowSize (section 2.2.3.183). |
| WindowSize | `21` | Spécifie un nombre maximum d'éléments modifiés dans une collection ou une demande qui DEVRAIENT être inclus dans la réponse de synchronisation. |
| Commands | `22` | Contient les opérations qui s'appliquent à une collection. |
| Options | `23` | Contient des éléments qui contrôlent certains aspects de la façon dont la synchronisation est effectuée. |
| FilterType | `24` | Spécifie une fenêtre de temps facultative pour les objets qui sont envoyés du serveur au client. Il s'applique aux collections d'e-mails et d'agendas. |
| Conflict | `27` | Spécifie comment résoudre le conflit qui se produit lorsqu'un objet a été modifié à la fois sur le client et sur le serveur. |
| Collections | `28` | Sert de conteneur pour l'élément Collection. |
| ApplicationData | `29` | Contient des données pour un objet particulier, tel qu'un contact, un message électronique, un rendez-vous de calendrier ou un élément de tâche. Peut être utilisé pour modifier des éléments, ajouter des éléments ou récupérer des éléments sur l'appareil client ou le serveur. |
| DeletesAsMoves | `30` | Indique que tous les éléments supprimés DOIVENT être déplacés vers le dossier Éléments supprimés. |
| Supported | `32` | Spécifie quels éléments de contact et de calendrier dans une demande de synchronisation sont gérés par le client. |
| SoftDelete | `33` | Supprime un objet du client lorsqu'il tombe en dehors des résultats de FilterType (section 2.2.3.64.2) ou qu'il n'est plus inclus dans les instructions SyncOptions (section 2.2.3.115.5). |
| MIMESupport | `34` | Active la prise en charge MIME pour les éléments de courrier électronique envoyés du serveur au client. |
| MIMETruncation | `35` | Spécifie si les données MIME de l'élément de courrier électronique DOIVENT être tronquées lorsqu'elles sont envoyées du serveur au client. |
| Wait | `36` | Spécifie le nombre de minutes pendant lesquelles le serveur DEVRAIT retarder une réponse si aucun nouvel élément n'est ajouté aux dossiers inclus, comme spécifié dans la section 3.1.5.4. |
| Limit | `37` | Spécifie soit le nombre maximal de collectes pouvant être synchronisées, soit la valeur maximale/minimale autorisée pour l'intervalle d'attente (section 2.2.3.182) ou l'intervalle HeartbeatInterval (section 2.2.3.79.2). |
| Partial | `38` | Indique au serveur que le client a envoyé une liste partielle de collections, auquel cas le serveur obtient le reste des collections depuis son cache. |
| ConversationMode | `39` | Spécifie s'il faut inclure les éléments inclus dans la modalité de conversation dans les résultats de la réponse de synchronisation. |
| MaxItems | `40` | Spécifie le nombre maximal de destinataires (c'est-à-dire les N premiers destinataires les plus fréquemment utilisés) à maintenir synchronisés à partir du cache d'informations sur les destinataires. |
| HeartbeatInterval | `41` | Spécifie le nombre de secondes pendant lesquelles le serveur DEVRAIT retarder une réponse si aucun nouvel élément n'est ajouté aux dossiers inclus, comme spécifié dans la section 3.1.5.4. |

### Voir également

* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
