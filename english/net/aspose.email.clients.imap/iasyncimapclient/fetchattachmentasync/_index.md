---
title: IAsyncImapClient.FetchAttachmentAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Fetches the specified attachment
type: docs
weight: 140
url: /net/aspose.email.clients.imap/iasyncimapclient/fetchattachmentasync/
---
## IAsyncImapClient.FetchAttachmentAsync method

Fetches the specified attachment.

```csharp
public Task<Attachment> FetchAttachmentAsync(int sequenceNumber, string attachmentName, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | Int32 | Connection to a server. |
| sequenceNumber | String | The sequence number of a message. |
| attachmentName | IConnection | A name of attachment. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

[`Attachment`](../../../aspose.email/attachment/) that represents the attachment.

### See Also

* class [Attachment](../../../aspose.email/attachment/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


