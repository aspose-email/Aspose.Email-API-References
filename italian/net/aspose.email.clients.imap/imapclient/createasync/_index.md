---
title: CreateAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Crea una nuova istanza diImapClientaspose.email.clients.imap/imapclient classe
type: docs
weight: 1320
url: /it/net/aspose.email.clients.imap/imapclient/createasync/
---
## ImapClient.CreateAsync method

Crea una nuova istanza di[`ImapClient`](../../imapclient) classe

```csharp
public static Task<IAsyncImapClient> CreateAsync(string host, string username, 
    IAsyncTokenProvider asyncTokenProvider, int port = 143, 
    SecurityOptions securityOptions = SecurityOptions.Auto, 
    CancellationToken cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| host | String | Il nome dell'ospite |
| port | String | Il numero di porta |
| username | IAsyncTokenProvider | Il nome utente |
| asyncTokenProvider | Int32 | Il provider del token di accesso. |
| securityOptions | SecurityOptions | Modalità di sicurezza per un client di posta |
| cancellationToken | CancellationToken | Il token di annullamento. |

### Guarda anche

* interface [IAsyncImapClient](../../iasyncimapclient)
* interface [IAsyncTokenProvider](../../../aspose.email.clients/iasynctokenprovider)
* enum [SecurityOptions](../../../aspose.email.clients/securityoptions)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->