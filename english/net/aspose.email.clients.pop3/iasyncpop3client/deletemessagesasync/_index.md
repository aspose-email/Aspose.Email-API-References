---
title: IAsyncPop3Client.DeleteMessagesAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncPop3Client method. Deletes all messages
type: docs
weight: 30
url: /net/aspose.email.clients.pop3/iasyncpop3client/deletemessagesasync/
---
## IAsyncPop3Client.DeleteMessagesAsync method

Deletes all messages

```csharp
public Task DeleteMessagesAsync(IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Remarks

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state.

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncPop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../iasyncpop3client/)
* assembly [Aspose.Email](../../../)


