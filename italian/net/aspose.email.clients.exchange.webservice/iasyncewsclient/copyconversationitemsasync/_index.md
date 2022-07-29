---
title: CopyConversationItemsAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Copia gli elementi della conversazione che si trovano nella cartella specificata nella cartella di destinazione specificata
type: docs
weight: 70
url: /it/net/aspose.email.clients.exchange.webservice/iasyncewsclient/copyconversationitemsasync/
---
## IAsyncEwsClient.CopyConversationItemsAsync method

Copia gli elementi della conversazione, che si trovano nella cartella specificata, nella cartella di destinazione specificata

```csharp
public Task CopyConversationItemsAsync(string conversationId, string destinationFolderId, 
    string contextFolderId = null, CancellationToken cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| conversationId | String | Id della conversazione da copiare |
| destinationFolderId | String | ID della cartella in cui copiare gli elementi |
| contextFolderId | String | ID della cartella in cui si trovano gli elementi della conversazione. Nota: se è impostato su null(o vuoto), tutti gli elementi della conversazione verranno copiati |
| cancellationToken | CancellationToken | Il token di annullamento. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *conversationId* è`nullo`o`vuoto` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *destinationFolderId* è`nullo`o`vuoto` |

### Guarda anche

* interface [IAsyncEwsClient](../../iasyncewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->