---
title: ListFoldersAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Obtient la liste des sous-dossiers dans le dossier spécifié
type: docs
weight: 220
url: /fr/net/aspose.email.clients.imap/iasyncimapclient/listfoldersasync/
---
## IAsyncImapClient.ListFoldersAsync method

Obtient la liste des sous-dossiers dans le dossier spécifié

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(string parentFolder = null, 
    bool loadFullInfo = false, ListFoldersOptions options = ListFoldersOptions.None, 
    ListFoldersReturnOptions returnOptions = ListFoldersReturnOptions.None, 
    IConnection connection = null, CancellationToken token = default)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| parentFolder | String | Nom du dossier |
| loadFullInfo | Boolean | Si true indique que les informations de dossier doivent être entièrement récupérées à partir d'un serveur, sinon, seuls les noms de dossier sont récupérés. |
| options | ListFoldersOptions | Options de fonctionnement |
| returnOptions | ListFoldersReturnOptions | Options de retour pour l'opération |
| connection | IConnection | Connexion à un serveur |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* enum [ListFoldersOptions](../../listfoldersoptions)
* enum [ListFoldersReturnOptions](../../listfoldersreturnoptions)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->