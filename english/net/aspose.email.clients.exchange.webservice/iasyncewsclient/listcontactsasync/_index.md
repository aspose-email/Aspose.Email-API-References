---
title: IAsyncEwsClient.ListContactsAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncEwsClient method. Lists contacts located in the specified folder on server
type: docs
weight: 420
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/listcontactsasync/
---
## IAsyncEwsClient.ListContactsAsync method

Lists contacts located in the specified folder on server.

```csharp
public Task<IEnumerable<MapiContact>> ListContactsAsync(string folderUri, 
    IEnumerable<PropertyDescriptor> mapiProperties = null, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | String | A folder to search contacts in. |
| mapiProperties | IEnumerable`1 | Required additional mapi properties. |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

An array of read [`MapiContact`](../../../aspose.email.mapi/mapicontact/) that represents contact information.

### See Also

* class [MapiContact](../../../aspose.email.mapi/mapicontact/)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor/)
* interface [IAsyncEwsClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient/)
* assembly [Aspose.Email](../../../)


