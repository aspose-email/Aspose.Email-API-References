---
title: IAsyncImapClient.SortMessageThreadsAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Sort message threads
type: docs
weight: 360
url: /net/aspose.email.clients.imap/iasyncimapclient/sortmessagethreadsasync/
---
## IAsyncImapClient.SortMessageThreadsAsync method

Sort message threads.

```csharp
public Task<List<MessageThreadResult>> SortMessageThreadsAsync(SortConditions conditions, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | SortConditions | Connection to a server |
| conditions | IConnection | Thread conditions. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Message threads

### See Also

* class [MessageThreadResult](../../messagethreadresult/)
* class [SortConditions](../../sortconditions/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


