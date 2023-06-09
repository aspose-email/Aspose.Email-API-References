---
title: IAsyncImapClient.GetQuotaAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Gets quota information
type: docs
weight: 190
url: /net/aspose.email.clients.imap/iasyncimapclient/getquotaasync/
---
## IAsyncImapClient.GetQuotaAsync method

Gets quota information

```csharp
public Task<ImapQuota[]> GetQuotaAsync(string quotaRootName, IConnection connection = null, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| quotaRootName | String | quota root name |
| connection | IConnection | Connection to a server |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Quota information

### See Also

* class [ImapQuota](../../imapquota/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


