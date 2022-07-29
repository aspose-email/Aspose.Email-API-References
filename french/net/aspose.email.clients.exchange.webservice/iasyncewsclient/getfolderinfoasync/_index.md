---
title: GetFolderInfoAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Obtient les informations du dossier
type: docs
weight: 340
url: /fr/net/aspose.email.clients.exchange.webservice/iasyncewsclient/getfolderinfoasync/
---
## IAsyncEwsClient.GetFolderInfoAsync method

Obtient les informations du dossier

```csharp
public Task<ExchangeFolderInfo> GetFolderInfoAsync(string folder, 
    CancellationToken cancellationToken = default)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Un dossier uri, nom de dossier distinctif. path/to/folder peut également être utilisé, si UseSlashAsFolderSeparator est défini |
| cancellationToken | CancellationToken | Le jeton d'annulation |

### Return_Value

UN[`ExchangeFolderInfo`](../../../aspose.email.clients.exchange/exchangefolderinfo) qui représente les informations du dossier

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *folder* est`nul`ou`vide` |
| [ExchangeException](../../../aspose.email/exchangeexception) | Le serveur a répondu un message d'erreur |

### Voir également

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->