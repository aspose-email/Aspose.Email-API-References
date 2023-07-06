---
title: IAsyncEwsClient.GetMailboxesAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncEwsClient method. Lists mailboxes having smtp addresses. Note the maximum count of returned contacts is 100. This is a restriction of used EWS operation
type: docs
weight: 360
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/getmailboxesasync/
---
## IAsyncEwsClient.GetMailboxesAsync method

Lists mailboxes having smtp addresses. Note: the maximum count of returned contacts is 100. This is a restriction of used EWS operation.

```csharp
public Task<Contact[]> GetMailboxesAsync(CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cancellationToken | CancellationToken | The cancellation token |

### Return Value

Contacts that represent contact information

### See Also

* interface [IAsyncEwsClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient/)
* assembly [Aspose.Email](../../../)


