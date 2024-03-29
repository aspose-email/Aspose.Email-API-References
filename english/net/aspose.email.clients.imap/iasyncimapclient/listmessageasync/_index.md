---
title: IAsyncImapClient.ListMessageAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Gets information about a message
type: docs
weight: 230
url: /net/aspose.email.clients.imap/iasyncimapclient/listmessageasync/
---
## ListMessageAsync(int, IEnumerable&lt;string&gt;, IConnection, CancellationToken) {#listmessageasync}

Gets information about a message.

```csharp
public Task<ImapMessageInfo> ListMessageAsync(int sequenceNumber, 
    IEnumerable<string> messageExtraFields = null, IConnection connection = null, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | Int32 | Connection to a server |
| sequenceNumber | IEnumerable`1 | The sequence number of message |
| messageExtraFields | IConnection | List of extra parameters for a message wich will be requested. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessageAsync(string, IEnumerable&lt;string&gt;, IConnection, CancellationToken) {#listmessageasync_1}

Gets information about a message.

```csharp
public Task<ImapMessageInfo> ListMessageAsync(string uniqueId, 
    IEnumerable<string> messageExtraFields = null, IConnection connection = null, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | String | Connection to a server |
| uniqueId | IEnumerable`1 | The unique Id of the message |
| messageExtraFields | IConnection | List of extra parameters for a message wich will be requested. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfo](../../imapmessageinfo/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


