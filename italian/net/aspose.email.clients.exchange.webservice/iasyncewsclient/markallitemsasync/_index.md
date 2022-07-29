---
title: MarkAllItemsAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Contrassegna tutti gli elementi nelle cartelle specificate.
type: docs
weight: 540
url: /it/net/aspose.email.clients.exchange.webservice/iasyncewsclient/markallitemsasync/
---
## IAsyncEwsClient.MarkAllItemsAsync method

Contrassegna tutti gli elementi nelle cartelle specificate.

```csharp
public Task MarkAllItemsAsync(IEnumerable<string> folderIds = null, bool read = true, 
    bool suppressReadReceipts = true, CancellationToken cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| read | IEnumerable`1 | Imposta lo stato letto/non letto sui messaggi nella cartella specificata. True per contrassegnare i messaggi nella cartella come letti. False per contrassegnare i messaggi come non letti. |
| suppressReadReceipts | Boolean | True per sopprimere l'invio di conferme di lettura per i messaggi; altrimenti falso. |
| folderIds | Boolean | Elenco degli URI delle cartelle per l'elaborazione. Impostare su Inbox URI per impostazione predefinita. |
| cancellationToken | CancellationToken | Il token di annullamento. |

### Guarda anche

* interface [IAsyncEwsClient](../../iasyncewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->