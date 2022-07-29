---
title: SetQuotaAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Imposta le informazioni sulla quota
type: docs
weight: 350
url: /it/net/aspose.email.clients.imap/iasyncimapclient/setquotaasync/
---
## IAsyncImapClient.SetQuotaAsync method

Imposta le informazioni sulla quota

```csharp
public Task<ImapQuota[]> SetQuotaAsync(string quotaRootName, string resourceName, 
    int resourceLimit, IConnection connection = null, CancellationToken token = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | String | Connessione a un server |
| quotaRootName | String | nome radice della quota |
| resourceName | Int32 | nome della risorsa |
| resourceLimit | IConnection | limite di risorse |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Informazioni sulle quote

### Guarda anche

* class [ImapQuota](../../imapquota)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->