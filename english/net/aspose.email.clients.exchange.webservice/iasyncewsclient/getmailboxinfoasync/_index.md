---
title: IAsyncEwsClient.GetMailboxInfoAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncEwsClient method. Gets the mailbox information
type: docs
weight: 370
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/getmailboxinfoasync/
---
## IAsyncEwsClient.GetMailboxInfoAsync method

Gets the mailbox information

```csharp
public Task<ExchangeMailboxInfo> GetMailboxInfoAsync(string mailbox = null, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mailbox | String | A mailbox to read from. Note: if mailbox is set to `null` or `empty` the default mailbox will be used |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

[`ExchangeMailboxInfo`](../../../aspose.email.clients.exchange/exchangemailboxinfo/) that represents mailbox information

### Exceptions

| exception | condition |
| --- | --- |
| [ExchangeException](../../../aspose.email/exchangeexception/) | Mailbox information can not be read. |

### See Also

* class [ExchangeMailboxInfo](../../../aspose.email.clients.exchange/exchangemailboxinfo/)
* interface [IAsyncEwsClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient/)
* assembly [Aspose.Email](../../../)


