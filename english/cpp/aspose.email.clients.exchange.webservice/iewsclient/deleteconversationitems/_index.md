---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::DeleteConversationItems method"
linktitle: "DeleteConversationItems"
articleTitle: "DeleteConversationItems"
second_title: "Aspose.Email for C++"
description: "Deletes all items of the specified conversation"
type: docs
weight: 240
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/deleteconversationitems/
---

## DeleteConversationItems (1 of 2) {#deleteconversationitems_1}

Deletes all items of the specified conversation

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
DeleteConversationItems(System::String conversationId)
```

| Parameter | Description |
| --- | --- |
| conversationId | Id of conversation to delete |

---

## DeleteConversationItems (2 of 2) {#deleteconversationitems_2}

Deletes the conversation items, which are located in the specified folder

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
DeleteConversationItems(System::String conversationId, System::String contextFolderId)
```

| Parameter | Description |
| --- | --- |
| conversationId | Id of conversation to delete |
| contextFolderId | Id of folder in which delete conversation items. Note: If it's set to null(or empty), all conversation items will be deleted |

