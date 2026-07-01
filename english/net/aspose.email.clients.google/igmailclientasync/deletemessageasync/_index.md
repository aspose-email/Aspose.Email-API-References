---
title: IGmailClientAsync.DeleteMessageAsync
second_title: Aspose.Email for .NET API Reference
description: IGmailClientAsync method. Asynchronously deletes a message by its ID moving it to trash by default
type: docs
weight: 170
url: /net/aspose.email.clients.google/igmailclientasync/deletemessageasync/
---
## DeleteMessageAsync(string, CancellationToken) {#deletemessageasync_1}

Asynchronously deletes a message by its ID, moving it to trash by default.

```csharp
public Task DeleteMessageAsync(string id, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | String | The message ID. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task representing the asynchronous operation.

### See Also

* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, bool, CancellationToken) {#deletemessageasync}

Asynchronously deletes a message by its ID, with an option to move to trash.

```csharp
public Task DeleteMessageAsync(string id, bool moveToTrash, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | String | The message ID. |
| moveToTrash | Boolean | Whether to move the message to trash. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task representing the asynchronous operation.

### See Also

* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)


