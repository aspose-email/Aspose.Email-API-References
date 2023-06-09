---
title: IAsyncPop3Client.GetMessageUniqueIdAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncPop3Client method. Gets the message unique id
type: docs
weight: 120
url: /net/aspose.email.clients.pop3/iasyncpop3client/getmessageuniqueidasync/
---
## IAsyncPop3Client.GetMessageUniqueIdAsync method

Gets the message unique id

```csharp
public Task<string> GetMessageUniqueIdAsync(int sequenceNumber, IConnection connection = null, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | Int32 | Connection to a server |
| sequenceNumber | IConnection | The sequence number of the message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

The message unique identifier.

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncPop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../iasyncpop3client/)
* assembly [Aspose.Email](../../../)


