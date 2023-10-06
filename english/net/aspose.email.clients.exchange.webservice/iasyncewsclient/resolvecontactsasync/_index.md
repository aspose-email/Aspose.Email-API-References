---
title: IAsyncEwsClient.ResolveContactsAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncEwsClient method. Resolves ambiguous email addresses and display names Note the maximum count of returned contacts is 100. This is a restriction of used EWS operation
type: docs
weight: 580
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/resolvecontactsasync/
---
## IAsyncEwsClient.ResolveContactsAsync method

Resolves ambiguous e-mail addresses and display names Note: the maximum count of returned contacts is 100. This is a restriction of used EWS operation.

```csharp
public Task<Contact[]> ResolveContactsAsync(string unresolvedEntry, 
    ExchangeListContactsOptions options = ExchangeListContactsOptions.None, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| unresolvedEntry | String | A name of contact to resolve |
| options | ExchangeListContactsOptions | Enumerates the list contacts options |
| cancellationToken | CancellationToken | The cancellation token |

### Return Value

Contacts that represent contact information

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *unresolvedEntry* is `null` or `empty` |

### See Also

* class [Contact](../../../aspose.email.personalinfo/contact/)
* enum [ExchangeListContactsOptions](../../exchangelistcontactsoptions/)
* interface [IAsyncEwsClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient/)
* assembly [Aspose.Email](../../../)


