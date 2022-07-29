---
title: ListSubFoldersAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Ottiene la raccolta di cartelle figlie da genitore
type: docs
weight: 480
url: /it/net/aspose.email.clients.exchange.webservice/iasyncewsclient/listsubfoldersasync/
---
## IAsyncEwsClient.ListSubFoldersAsync method

Ottiene la raccolta di cartelle figlie da genitore

```csharp
public Task<ExchangeFolderInfoCollection> ListSubFoldersAsync(string mailbox, 
    string parentFolderUri, CancellationToken cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mailbox | String | La cassetta postale utilizzata per inizializzare la classe ID cartella. |
| parentFolderUri | String | Una cartella principale |
| cancellationToken | CancellationToken | Il token di annullamento. |

### Valore di ritorno

[`ExchangeFolderInfoCollection`](../../../aspose.email.clients.exchange/exchangefolderinfocollection) che contiene le sottocartelle dalla cartella principale

### Guarda anche

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->