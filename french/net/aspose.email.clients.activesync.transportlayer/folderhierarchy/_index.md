---
title: FolderHierarchy
second_title: Référence de l'API Aspose.Email pour .NET
description: Espace de noms FolderHierarchy du protocole ActiveSync
type: docs
weight: 1250
url: /fr/net/aspose.email.clients.activesync.transportlayer/folderhierarchy/
---
## FolderHierarchy enumeration

Espace de noms FolderHierarchy du protocole ActiveSync

```csharp
public enum FolderHierarchy
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| DisplayName | `7` | Spécifie le nom du dossier qui est montré à l'utilisateur. |
| ServerId | `8` | Identifie un dossier sur un serveur. |
| ParentId | `9` | Spécifie l'ID de serveur du dossier parent du dossier sur le serveur |
| Type | `10` | Spécifie le type de dossier à créer. |
| Status | `12` | Indique la raison de l'échec d'une demande de commande. |
| Changes | `14` | Contient les modifications apportées à la hiérarchie des dossiers. |
| Add | `15` | Crée un nouveau dossier sur le client |
| Delete | `16` | Spécifie qu'un dossier sur le serveur a été supprimé depuis la dernière synchronisation de dossier. |
| Update | `17` | Identifie un dossier sur le serveur qui a été mis à jour (renommé ou déplacé). |
| SyncKey | `18` | Il est utilisé par le serveur pour suivre l'état actuel du client. |
| FolderCreate | `19` | L'élément FolderCreate est un élément obligatoire dans les demandes de commande FolderCreate et les réponses de commande FolderCreate qui identifie le corps du HTTP POST comme contenant une commande FolderCreate (section 2.2.2.2). |
| FolderDelete | `20` | L'élément FolderDelete est un élément obligatoire dans les demandes de commande FolderDelete et les réponses de commande FolderDelete qui identifie le corps du HTTP POST comme contenant une commande FolderDelete (section 2.2.2.3). |
| FolderUpdate | `21` | L'élément FolderUpdate est un élément obligatoire dans les demandes de commande FolderUpdate et les réponses de commande FolderUpdate qui identifie le corps du HTTP POST comme contenant une commande FolderUpdate (section 2.2.2.5). |
| FolderSync | `22` | L'élément FolderSync est un élément obligatoire dans les demandes de commande FolderSync et les réponses de commande FolderSync qui identifie le corps du HTTP POST comme contenant une commande FolderSync (section 2.2.2.4). |
| Count | `23` | Spécifie le nombre de dossiers ajoutés, supprimés et mis à jour sur le serveur depuis la dernière synchronisation de dossiers. |

### Voir également

* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->