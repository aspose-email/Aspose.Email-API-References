---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::CopyConversationItems method"
linktitle: "CopyConversationItems"
articleTitle: "CopyConversationItems"
second_title: "Aspose.Email for C++"
description: "Copies the conversation items, which are located in the specified folder, into the specified target folder"
type: docs
weight: 100
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/copyconversationitems/
---

## CopyConversationItems (1 of 2) {#copyconversationitems_1}

Copies the conversation items, which are located in the specified folder, into the specified target folder

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
CopyConversationItems(System::String conversationId, System::String contextFolderId, System::String destinationFolderId)
```

| Parameter | Description |
| --- | --- |
| conversationId | Id of conversation to copy |
| contextFolderId | Id of folder in which conversation items are located. Note: If it's set to null(or empty), all conversation items will be copied |
| destinationFolderId | Id of folder into which copy items |

---

## CopyConversationItems (2 of 2) {#copyconversationitems_2}

Copies the conversation items into the specified target folder

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
CopyConversationItems(System::String conversationId, System::String destinationFolderId)
```

| Parameter | Description |
| --- | --- |
| conversationId | Id of conversation to copy |
| destinationFolderId | Id of folder into which copy items |

