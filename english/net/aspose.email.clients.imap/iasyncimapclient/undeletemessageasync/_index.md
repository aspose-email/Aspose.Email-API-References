---
title: IAsyncImapClient.UndeleteMessageAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Marks a message with the specified sequence number as not deleted
type: docs
weight: 400
url: /net/aspose.email.clients.imap/iasyncimapclient/undeletemessageasync/
---
## UndeleteMessageAsync(int, long, IConnection, CancellationToken) {#undeletemessageasync}

Marks a message with the specified sequence number as not deleted

```csharp
public Task UndeleteMessageAsync(int sequenceNumber, long modificationSequence = 0, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | Int32 | Connection to a server |
| sequenceNumber | Int64 | The sequence number of the message |
| modificationSequence | IConnection | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)

---

## UndeleteMessageAsync(string, long, IConnection, CancellationToken) {#undeletemessageasync_1}

Marks a message with the specified sequence number as not deleted.

```csharp
public Task UndeleteMessageAsync(string uniqueId, long modificationSequence = 0, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | String | Connection to a server |
| uniqueId | Int64 | The unique Id of the message |
| modificationSequence | IConnection | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


