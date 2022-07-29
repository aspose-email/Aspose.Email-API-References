---
title: CreateAsync
second_title: Aspose.Email för .NET API-referens
description: Skapar en ny instans avImapClientaspose.email.clients.imap/imapclient klass
type: docs
weight: 1320
url: /sv/net/aspose.email.clients.imap/imapclient/createasync/
---
## ImapClient.CreateAsync method

Skapar en ny instans av[`ImapClient`](../../imapclient) klass

```csharp
public static Task<IAsyncImapClient> CreateAsync(string host, string username, 
    IAsyncTokenProvider asyncTokenProvider, int port = 143, 
    SecurityOptions securityOptions = SecurityOptions.Auto, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| host | String | Värdnamnet |
| port | String | Portnumret |
| username | IAsyncTokenProvider | Användarnamnet |
| asyncTokenProvider | Int32 | Leverantören av åtkomsttoken. |
| securityOptions | SecurityOptions | Säkerhetsläge för en e-postklient |
| cancellationToken | CancellationToken | Avbokningstoken. |

### Se även

* interface [IAsyncImapClient](../../iasyncimapclient)
* interface [IAsyncTokenProvider](../../../aspose.email.clients/iasynctokenprovider)
* enum [SecurityOptions](../../../aspose.email.clients/securityoptions)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->