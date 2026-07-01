---
title: IGmailClientAsync.GetContactsFromGroupAsync
second_title: Aspose.Email for .NET API Reference
description: IGmailClientAsync method. Asynchronously retrieves contacts from a contact group
type: docs
weight: 280
url: /net/aspose.email.clients.google/igmailclientasync/getcontactsfromgroupasync/
---
## GetContactsFromGroupAsync(GoogleContactGroup, CancellationToken) {#getcontactsfromgroupasync}

Asynchronously retrieves contacts from a contact group.

```csharp
public Task<Contact[]> GetContactsFromGroupAsync(GoogleContactGroup contactGroup, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| contactGroup | GoogleContactGroup | The contact group. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task that represents the asynchronous operation. The task result contains an array of [`Contact`](../../../aspose.email.personalinfo/contact/).

### See Also

* class [Contact](../../../aspose.email.personalinfo/contact/)
* class [GoogleContactGroup](../../googlecontactgroup/)
* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)

---

## GetContactsFromGroupAsync(string, CancellationToken) {#getcontactsfromgroupasync_1}

Asynchronously retrieves contacts from a contact group by group ID.

```csharp
public Task<Contact[]> GetContactsFromGroupAsync(string groupId, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| groupId | String | The group ID. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task that represents the asynchronous operation. The task result contains an array of [`Contact`](../../../aspose.email.personalinfo/contact/).

### See Also

* class [Contact](../../../aspose.email.personalinfo/contact/)
* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)


