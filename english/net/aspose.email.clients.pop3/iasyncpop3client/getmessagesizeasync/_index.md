---
title: IAsyncPop3Client.GetMessageSizeAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncPop3Client method. Gets the size of the message
type: docs
weight: 110
url: /net/aspose.email.clients.pop3/iasyncpop3client/getmessagesizeasync/
---
## GetMessageSizeAsync(string, IConnection, CancellationToken) {#getmessagesizeasync_1}

Gets the size of the message

```csharp
public Task<long> GetMessageSizeAsync(string uniqueId, IConnection connection = null, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | String | Connection to a server |
| uniqueId | IConnection | The unique id of the message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

The message size

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncPop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../iasyncpop3client/)
* assembly [Aspose.Email](../../../)

---

## GetMessageSizeAsync(int, IConnection, CancellationToken) {#getmessagesizeasync}

Gets the size of the message

```csharp
public Task<long> GetMessageSizeAsync(int sequenceNumber, IConnection connection = null, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | Int32 | Connection to a server |
| sequenceNumber | IConnection | The sequence number of the message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

The message size

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncPop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../iasyncpop3client/)
* assembly [Aspose.Email](../../../)


