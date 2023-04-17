---
title: IAsyncImapClient.AppendMessageAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Uploads the mail message to the specified folder
type: docs
weight: 20
url: /net/aspose.email.clients.imap/iasyncimapclient/appendmessageasync/
---
## IAsyncImapClient.AppendMessageAsync method

Uploads the mail message to the specified folder

```csharp
public Task<string> AppendMessageAsync(MailMessage message, string folderName = null, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | MailMessage | Connection to a server |
| folderName | String | Folder that will receive the mail message |
| message | IConnection | Mail message to be upload |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


