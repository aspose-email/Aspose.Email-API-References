---
title: IAsyncImapClient.AppendMessagesAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Uploads the mail messages to the current folder
type: docs
weight: 30
url: /net/aspose.email.clients.imap/iasyncimapclient/appendmessagesasync/
---
## IAsyncImapClient.AppendMessagesAsync method

Uploads the mail messages to the current folder

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IEnumerable<MailMessage> messages, 
    string folderName = null, IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IEnumerable`1 | Connection to a server |
| folderName | String | Folder that will receive the mail message |
| messages | IConnection | Enumeration of email messages to be upload |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [AppendMessagesResult](../../appendmessagesresult/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


