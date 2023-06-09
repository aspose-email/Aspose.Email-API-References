---
title: IAsyncPop3Client.GetMessageCountAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncPop3Client method. Gets the message count
type: docs
weight: 80
url: /net/aspose.email.clients.pop3/iasyncpop3client/getmessagecountasync/
---
## IAsyncPop3Client.GetMessageCountAsync method

Gets the message count

```csharp
public Task<int> GetMessageCountAsync(bool closeTransaction = false, IConnection connection = null, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | Boolean | Connection to a server |
| closeTransaction | IConnection | Indicates if current transaction has to be closed, before the list is retrieved. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

The message count

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncPop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../iasyncpop3client/)
* assembly [Aspose.Email](../../../)


