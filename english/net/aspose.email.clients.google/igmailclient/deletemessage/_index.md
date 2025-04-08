---
title: IGmailClient.DeleteMessage
second_title: Aspose.Email for .NET API Reference
description: IGmailClient method. Moves the specified message to the trash if moveToTrash true or permanently deletes if false
type: docs
weight: 150
url: /net/aspose.email.clients.google/igmailclient/deletemessage/
---
## DeleteMessage(string, bool) {#deletemessage_1}

Moves the specified message to the trash if moveToTrash true, or permanently deletes if false.

```csharp
public void DeleteMessage(string id, bool moveToTrash)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | String | The ID of the message to trash or delete. |
| moveToTrash | Boolean | Moves the specified message to the trash if true, or permanently deletes if false. |

### See Also

* interface [IGmailClient](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessage(string) {#deletemessage}

Immediately and permanently deletes the specified message. This operation cannot be undone. Prefer overriding method DeleteMessage with parameter moveToTrash instead.

```csharp
public void DeleteMessage(string id)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | String | The ID of the message to delete. |

### See Also

* interface [IGmailClient](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclient/)
* assembly [Aspose.Email](../../../)


