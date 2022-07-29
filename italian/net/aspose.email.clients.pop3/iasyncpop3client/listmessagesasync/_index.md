---
title: ListMessagesAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Elenca i messaggi.
type: docs
weight: 130
url: /it/net/aspose.email.clients.pop3/iasyncpop3client/listmessagesasync/
---
## IAsyncPop3Client.ListMessagesAsync method

Elenca i messaggi.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(
    Pop3ListFields fields = Pop3ListFields.All, bool closeTransaction = false, 
    MailQuery query = null, IConnection connection = null, CancellationToken token = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | Pop3ListFields | Connessione a un server |
| fields | Boolean | I campi che vogliamo ottenere |
| closeTransaction | MailQuery | Indica se la transazione corrente deve essere chiusa, prima che l'elenco venga recuperato. |
| query | IConnection | Il[`MailQuery`](../../../aspose.email.tools.search/mailquery) oggetto. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncPop3Client](../../iasyncpop3client)
* spazio dei nomi [Aspose.Email.Clients.Pop3](../../iasyncpop3client)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->