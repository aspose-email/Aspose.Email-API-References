---
title: IAsyncEwsClient.GetContactsAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncEwsClient method. Lists contacts located in the specified folder on server
type: docs
weight: 330
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/getcontactsasync/
---
## IAsyncEwsClient.GetContactsAsync method

Lists contacts located in the specified folder on server

```csharp
public Task<Contact[]> GetContactsAsync(string folder, 
    ExchangeListContactsOptions options = ExchangeListContactsOptions.FetchPhoto, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | A folder to search contacts in |
| options | ExchangeListContactsOptions | Enumerates the list contacts options |
| cancellationToken | CancellationToken | The cancellation token |

### Return Value

An array of read [`Contact`](../../../aspose.email.personalinfo/contact/) that represents contact information

### See Also

* class [Contact](../../../aspose.email.personalinfo/contact/)
* enum [ExchangeListContactsOptions](../../exchangelistcontactsoptions/)
* interface [IAsyncEwsClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient/)
* assembly [Aspose.Email](../../../)


