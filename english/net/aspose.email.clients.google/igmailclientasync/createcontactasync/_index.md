---
title: IGmailClientAsync.CreateContactAsync
second_title: Aspose.Email for .NET API Reference
description: IGmailClientAsync method. Asynchronously creates a contact using the default email address
type: docs
weight: 60
url: /net/aspose.email.clients.google/igmailclientasync/createcontactasync/
---
## CreateContactAsync(Contact, CancellationToken) {#createcontactasync_1}

Asynchronously creates a contact using the default email address.

```csharp
public Task<string> CreateContactAsync(Contact contact, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| contact | Contact | The contact to create. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task that represents the asynchronous operation. The task result contains the contact URI.

### See Also

* class [Contact](../../../aspose.email.personalinfo/contact/)
* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)

---

## CreateContactAsync(Contact, string, CancellationToken) {#createcontactasync}

Asynchronously creates a contact with the specified email address.

```csharp
public Task<string> CreateContactAsync(Contact contact, string emailAddress, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| contact | Contact | The contact to create. |
| emailAddress | String | The email address to use. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task that represents the asynchronous operation. The task result contains the contact URI.

### See Also

* class [Contact](../../../aspose.email.personalinfo/contact/)
* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)


