---
title: IAsyncImapClient.CopyMessageAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Copies the message
type: docs
weight: 80
url: /net/aspose.email.clients.imap/iasyncimapclient/copymessageasync/
---
## CopyMessageAsync(int, string, IConnection, CancellationToken) {#copymessageasync}

Copies the message

```csharp
public Task<string> CopyMessageAsync(int sequenceNumber, string folderName, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | Int32 | Connection to a server |
| sequenceNumber | String | The sequence number of the message |
| folderName | IConnection | Folder name where a message is to be copied |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

If server supports UIDPLUS extension returns unique id of the copied message, otherwise returns null Please, read more https://tools.ietf.org/html/rfc4315

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)

---

## CopyMessageAsync(string, string, IConnection, CancellationToken) {#copymessageasync_1}

Copies the message.

```csharp
public Task<string> CopyMessageAsync(string uniqueId, string folderName, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | String | Connection to a server. |
| uniqueId | String | The uid of the message. |
| folderName | IConnection | Folder name where a message is to be copied. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

If server supports UIDPLUS extension returns unique id of the copied message, otherwise returns null. Please, read more https://tools.ietf.org/html/rfc4315

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


