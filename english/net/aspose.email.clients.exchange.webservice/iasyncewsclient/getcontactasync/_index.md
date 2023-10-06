---
title: IAsyncEwsClient.GetContactAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncEwsClient method. Retrieves contact information according to specified identifier
type: docs
weight: 320
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/getcontactasync/
---
## IAsyncEwsClient.GetContactAsync method

Retrieves contact information according to specified identifier.

```csharp
public Task<Contact> GetContactAsync(string contactId, 
    ExchangeListContactsOptions options = ExchangeListContactsOptions.FetchPhoto, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| contactId | String | Contact identifier. |
| options | ExchangeListContactsOptions | Settings for retrieving contact. |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

Contact information

### See Also

* class [Contact](../../../aspose.email.personalinfo/contact/)
* enum [ExchangeListContactsOptions](../../exchangelistcontactsoptions/)
* interface [IAsyncEwsClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient/)
* assembly [Aspose.Email](../../../)


