---
title: IAsyncPop3Client.FetchMessageAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncPop3Client method. Fetches the message
type: docs
weight: 40
url: /net/aspose.email.clients.pop3/iasyncpop3client/fetchmessageasync/
---
## FetchMessageAsync(string, IConnection, CancellationToken) {#fetchmessageasync_1}

Fetches the message

```csharp
public Task<MailMessage> FetchMessageAsync(string uniqueId, IConnection connection = null, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | String | Connection to a server |
| uniqueId | IConnection | The unique id of the message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

The message

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncPop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../iasyncpop3client/)
* assembly [Aspose.Email](../../../)

---

## FetchMessageAsync(int, IConnection, CancellationToken) {#fetchmessageasync}

Fetches the message

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber, IConnection connection = null, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | Int32 | Connection to a server |
| sequenceNumber | IConnection | The sequence number of the message |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

The message

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncPop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../iasyncpop3client/)
* assembly [Aspose.Email](../../../)


