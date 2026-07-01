---
title: IGmailClientAsync.CreateContactPhotoAsync
second_title: Aspose.Email for .NET API Reference
description: IGmailClientAsync method. Asynchronously creates a contact photo
type: docs
weight: 70
url: /net/aspose.email.clients.google/igmailclientasync/createcontactphotoasync/
---
## IGmailClientAsync.CreateContactPhotoAsync method

Asynchronously creates a contact photo.

```csharp
public Task<ContactPhoto> CreateContactPhotoAsync(Contact contact, byte[] imageData, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| contact | Contact | The contact to associate the photo with. |
| imageData | Byte[] | The image data for the photo. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task that represents the asynchronous operation. The task result contains the created [`ContactPhoto`](../../../aspose.email.personalinfo/contactphoto/).

### See Also

* class [ContactPhoto](../../../aspose.email.personalinfo/contactphoto/)
* class [Contact](../../../aspose.email.personalinfo/contact/)
* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)


