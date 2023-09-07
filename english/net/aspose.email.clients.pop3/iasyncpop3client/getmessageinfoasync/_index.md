---
title: IAsyncPop3Client.GetMessageInfoAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncPop3Client method. Gets the information for that message
type: docs
weight: 100
url: /net/aspose.email.clients.pop3/iasyncpop3client/getmessageinfoasync/
---
## GetMessageInfoAsync(string, Pop3ListFields, IConnection, CancellationToken) {#getmessageinfoasync_1}

Gets the information for that message

```csharp
public Task<Pop3MessageInfo> GetMessageInfoAsync(string uniqueId, 
    Pop3ListFields fields = Pop3ListFields.Main, IConnection connection = null, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | String | Connection to a server |
| uniqueId | Pop3ListFields | The unique id of the message |
| fields | IConnection | The fields that we want get |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

The message information.

### See Also

* class [Pop3MessageInfo](../../pop3messageinfo/)
* enum [Pop3ListFields](../../pop3listfields/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncPop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../iasyncpop3client/)
* assembly [Aspose.Email](../../../)

---

## GetMessageInfoAsync(int, Pop3ListFields, IConnection, CancellationToken) {#getmessageinfoasync}

Gets the information for that message

```csharp
public Task<Pop3MessageInfo> GetMessageInfoAsync(int sequenceNumber, 
    Pop3ListFields fields = Pop3ListFields.Main, IConnection connection = null, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | Int32 | Connection to a server |
| sequenceNumber | Pop3ListFields | The sequence number of the message |
| fields | IConnection | The fields that we want get |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

The message information.

### See Also

* class [Pop3MessageInfo](../../pop3messageinfo/)
* enum [Pop3ListFields](../../pop3listfields/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncPop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../iasyncpop3client/)
* assembly [Aspose.Email](../../../)


