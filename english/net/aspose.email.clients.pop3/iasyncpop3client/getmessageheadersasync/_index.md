---
title: IAsyncPop3Client.GetMessageHeadersAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncPop3Client method. Gets the message headers
type: docs
weight: 90
url: /net/aspose.email.clients.pop3/iasyncpop3client/getmessageheadersasync/
---
## GetMessageHeadersAsync(int, IConnection, CancellationToken) {#getmessageheadersasync}

Gets the message headers

```csharp
public Task<HeaderCollection> GetMessageHeadersAsync(int sequenceNumber, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | Int32 | Connection to a server |
| sequenceNumber | IConnection | The sequence number of the message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

The message headers

### See Also

* class [HeaderCollection](../../../aspose.email.mime/headercollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncPop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../iasyncpop3client/)
* assembly [Aspose.Email](../../../)

---

## GetMessageHeadersAsync(string, IConnection, CancellationToken) {#getmessageheadersasync_1}

Gets the message headers

```csharp
public Task<HeaderCollection> GetMessageHeadersAsync(string uniqueId, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | String | Connection to a server |
| uniqueId | IConnection | The unique id of the message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

The message headers

### See Also

* class [HeaderCollection](../../../aspose.email.mime/headercollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncPop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../iasyncpop3client/)
* assembly [Aspose.Email](../../../)


