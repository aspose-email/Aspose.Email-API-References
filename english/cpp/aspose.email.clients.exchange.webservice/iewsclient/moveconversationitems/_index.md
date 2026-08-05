---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::MoveConversationItems method"
linktitle: "MoveConversationItems"
articleTitle: "MoveConversationItems"
second_title: "Aspose.Email for C++"
description: "Moves the conversation items, which are located in the specified folder, into the specified target folder"
type: docs
weight: 1150
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/moveconversationitems/
---

## MoveConversationItems (1 of 2) {#moveconversationitems_1}

Moves the conversation items, which are located in the specified folder, into the specified target folder

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
MoveConversationItems(System::String conversationId, System::String contextFolderId, System::String destinationFolderId)
```

| Parameter | Description |
| --- | --- |
| conversationId | Id of conversation to move |
| contextFolderId | Id of folder from which move conversation items. Note: If it's set to null(or empty), all conversation items will be moved |
| destinationFolderId | Id of folder into which move items |

---

## MoveConversationItems (2 of 2) {#moveconversationitems_2}

Moves the conversation items into the specified target folder

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
MoveConversationItems(System::String conversationId, System::String destinationFolderId)
```

| Parameter | Description |
| --- | --- |
| conversationId | Id of conversation to delete |
| destinationFolderId | Id of folder into which move items |

