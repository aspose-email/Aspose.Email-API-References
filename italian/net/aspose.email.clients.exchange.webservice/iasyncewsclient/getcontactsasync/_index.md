---
title: GetContactsAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Elenca i contatti che si trovano nella cartella specificata sul server
type: docs
weight: 330
url: /it/net/aspose.email.clients.exchange.webservice/iasyncewsclient/getcontactsasync/
---
## IAsyncEwsClient.GetContactsAsync method

Elenca i contatti che si trovano nella cartella specificata sul server

```csharp
public Task<Contact[]> GetContactsAsync(string folder, 
    ExchangeListContactsOptions options = ExchangeListContactsOptions.FetchPhoto, 
    CancellationToken cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folder | String | Una cartella in cui cercare i contatti |
| options | ExchangeListContactsOptions | Enumera le opzioni dell'elenco dei contatti |
| cancellationToken | CancellationToken | Il token di annullamento |

### Valore di ritorno

Un array di lettura[`Contact`](../../../aspose.email.personalinfo/contact) che rappresenta le informazioni di contatto

### Guarda anche

* class [Contact](../../../aspose.email.personalinfo/contact)
* enum [ExchangeListContactsOptions](../../exchangelistcontactsoptions)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->