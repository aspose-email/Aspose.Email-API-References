---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::SetConversationReadState method"
linktitle: "SetConversationReadState"
articleTitle: "SetConversationReadState"
second_title: "Aspose.Email for C++"
description: "Set read state of the conversation items to the specified value"
type: docs
weight: 1470
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/setconversationreadstate/
---

## SetConversationReadState (1 of 2) {#setconversationreadstate_1}

Set read state of the conversation items to the specified value

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
SetConversationReadState(System::String conversationId, bool isRead)
```

| Parameter | Description |
| --- | --- |
| conversationId | Id of conversation to be changed |
| isRead | A flag that enables setting the read state of items in a conversation. |

---

## SetConversationReadState (2 of 2) {#setconversationreadstate_2}

Set read state of the conversation items, which are located in the specified folder, to the specified value

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
SetConversationReadState(System::String conversationId, System::String contextFolderId, bool isRead)
```

| Parameter | Description |
| --- | --- |
| conversationId | Id of conversation to be changed |
| contextFolderId | Id of folder in which conversation items are located. Note: If it's set to null(or empty), all conversation items will be copied |
| isRead | A flag that enables setting the read state of items in a conversation. |

