---
title: IAsyncImapClient.GetMessageThreadsAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Get message threads
type: docs
weight: 170
url: /net/aspose.email.clients.imap/iasyncimapclient/getmessagethreadsasync/
---
## IAsyncImapClient.GetMessageThreadsAsync method

Get message threads.

```csharp
public Task<IEnumerable<MessageThreadResult>> GetMessageThreadsAsync(
    BaseSearchConditions conditions, IConnection connection = null, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | BaseSearchConditions | Connection to a server |
| conditions | IConnection | Thread conditions. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Message threads

### See Also

* class [MessageThreadResult](../../messagethreadresult/)
* class [BaseSearchConditions](../../basesearchconditions/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


