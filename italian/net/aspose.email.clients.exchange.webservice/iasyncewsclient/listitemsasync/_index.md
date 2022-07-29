---
title: ListItemsAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Recupera lelenco degli URI degli elementi nella cartella specificata
type: docs
weight: 430
url: /it/net/aspose.email.clients.exchange.webservice/iasyncewsclient/listitemsasync/
---
## IAsyncEwsClient.ListItemsAsync method

Recupera l'elenco degli URI degli elementi nella cartella specificata

```csharp
public Task<string[]> ListItemsAsync(string folder, string mailbox = null, MailQuery query = null, 
    bool recursive = false, CancellationToken cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folder | String | cartella per cercare gli elementi |
| mailbox | String | La cassetta postale utilizzata per inizializzare la classe ID cartella. |
| query | MailQuery | Condizioni aggiuntive per selezionare gli articoli |
| recursive | Boolean | Specifica se la richiesta deve essere obbligatoria. |
| cancellationToken | CancellationToken | Il token di annullamento. |

### Valore di ritorno

Restituisce l'elenco degli URI degli elementi

### Guarda anche

* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->