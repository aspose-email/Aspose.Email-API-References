---
title: IAsyncPop3Client.FetchMessagesAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncPop3Client method. Fetches the messages asynchronously
type: docs
weight: 50
url: /net/aspose.email.clients.pop3/iasyncpop3client/fetchmessagesasync/
---
## FetchMessagesAsync(IEnumerable&lt;int&gt;, IConnection, CancellationToken) {#fetchmessagesasync}

Fetches the messages asynchronously

```csharp
public Task<IEnumerable<MailMessage>> FetchMessagesAsync(IEnumerable<int> sequenceNumbers, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IEnumerable`1 | Connection to a server |
| sequenceNumbers | IConnection | The sequence numbers of the messages |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

The messages

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncPop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../iasyncpop3client/)
* assembly [Aspose.Email](../../../)

---

## FetchMessagesAsync(IEnumerable&lt;string&gt;, IConnection, CancellationToken) {#fetchmessagesasync_1}

Fetches the messages asynchronously

```csharp
public Task<IEnumerable<MailMessage>> FetchMessagesAsync(IEnumerable<string> uIds, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IEnumerable`1 | Connection to a server |
| uIds | IConnection | The sequence numbers of the messages |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

The messages

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncPop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../iasyncpop3client/)
* assembly [Aspose.Email](../../../)


