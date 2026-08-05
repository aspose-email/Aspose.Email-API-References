---
title: "Aspose::Email::Clients::Google::IGmailClient::DeleteMessage method"
linktitle: "DeleteMessage"
articleTitle: "DeleteMessage"
second_title: "Aspose.Email for C++"
description: "Immediately and permanently deletes the specified message."
type: docs
weight: 150
url: /cpp/aspose.email.clients.google/igmailclient/deletemessage/
---

## DeleteMessage (1 of 2) {#deletemessage_1}

Immediately and permanently deletes the specified message. This operation cannot be undone. Prefer overriding method DeleteMessage with parameter moveToTrash instead.

**Returns:** virtual void Aspose::Email::Clients::Google::

```cpp
DeleteMessage(System::String id)
```

| Parameter | Description |
| --- | --- |
| id | The ID of the message to delete. |

---

## DeleteMessage (2 of 2) {#deletemessage_2}

Moves the specified message to the trash if moveToTrash true, or permanently deletes if false.

**Returns:** virtual void Aspose::Email::Clients::Google::

```cpp
DeleteMessage(System::String id, bool moveToTrash)
```

| Parameter | Description |
| --- | --- |
| id | The ID of the message to trash or delete. |
| moveToTrash | Moves the specified message to the trash if true, or permanently deletes if false. |

