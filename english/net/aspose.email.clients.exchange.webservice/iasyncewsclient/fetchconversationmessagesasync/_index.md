---
title: IAsyncEwsClient.FetchConversationMessagesAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncEwsClient method. Fetches the specified conversation messages
type: docs
weight: 240
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/fetchconversationmessagesasync/
---
## IAsyncEwsClient.FetchConversationMessagesAsync method

Fetches the specified conversation messages

```csharp
public Task<MailMessageCollection> FetchConversationMessagesAsync(string conversationId, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| conversationId | String | Id of conversation |
| cancellationToken | CancellationToken | The cancellation token. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *conversationId* is `null` or `empty` |

### See Also

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection/)
* interface [IAsyncEwsClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient/)
* assembly [Aspose.Email](../../../)


