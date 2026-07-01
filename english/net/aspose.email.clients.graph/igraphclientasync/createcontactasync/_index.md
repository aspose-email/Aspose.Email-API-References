---
title: IGraphClientAsync.CreateContactAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously creates a contact in the specified folder
type: docs
weight: 70
url: /net/aspose.email.clients.graph/igraphclientasync/createcontactasync/
---
## IGraphClientAsync.CreateContactAsync method

Asynchronously creates a contact in the specified folder.

```csharp
public Task<MapiContact> CreateContactAsync(string folderId, MapiContact contact, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderId | String | The ID of the folder where the contact will be created. |
| contact | MapiContact | The [`MapiContact`](../../../aspose.email.mapi/mapicontact/) to create. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the created [`MapiContact`](../../../aspose.email.mapi/mapicontact/).

### See Also

* class [MapiContact](../../../aspose.email.mapi/mapicontact/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


