---
title: IAsyncPop3Client.GetMailboxInfoAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncPop3Client method. Gets the mailbox status info
type: docs
weight: 60
url: /net/aspose.email.clients.pop3/iasyncpop3client/getmailboxinfoasync/
---
## IAsyncPop3Client.GetMailboxInfoAsync method

Gets the mailbox status info

```csharp
public Task<Pop3MailboxInfo> GetMailboxInfoAsync(bool closeTransaction = false, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | Boolean | Connection to a server |
| closeTransaction | IConnection | Indicates if current transaction has to be closed, before the list is retrieved. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

The mailbox info.

### See Also

* class [Pop3MailboxInfo](../../pop3mailboxinfo/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncPop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../iasyncpop3client/)
* assembly [Aspose.Email](../../../)


