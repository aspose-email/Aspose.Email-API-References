---
title: IAsyncImapClient.ListMessagesAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Gets the list of messages in the specified folder
type: docs
weight: 240
url: /net/aspose.email.clients.imap/iasyncimapclient/listmessagesasync/
---
## ListMessagesAsync(string, long, bool, IEnumerable&lt;string&gt;, IConnection, CancellationToken) {#listmessagesasync_1}

Gets the list of messages in the specified folder

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName = null, 
    long modificationSequence = 0, bool retrieveRecursively = false, 
    IEnumerable<string> messageExtraFields = null, IConnection connection = null, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | String | Connection to a server |
| folderName | Int64 | Folder to retrieve messages. |
| modificationSequence | Boolean | Modification sequence |
| retrieveRecursively | IEnumerable`1 | Indicates, if messages have to be retrieved recursively. |
| messageExtraFields | IConnection | List of extra parameters for a message wich will be requested. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, string, int, IConnection, CancellationToken) {#listmessagesasync}

Gets the list of messages in the current folder.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, string folderName = null, 
    int maxNumberOfMessages = 0, IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | MailQuery | Connection to a server |
| folderName | String | Messages location |
| query | Int32 | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query. |
| maxNumberOfMessages | IConnection | Maximum number of messages. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Collection of ImapMessageInfo objects.

### See Also

* class [ImapMessageInfoCollection](../../imapmessageinfocollection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


