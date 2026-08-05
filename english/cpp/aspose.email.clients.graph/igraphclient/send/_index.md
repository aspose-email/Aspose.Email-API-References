---
title: "Aspose::Email::Clients::Graph::IGraphClient::Send method"
linktitle: "Send"
articleTitle: "Send"
second_title: "Aspose.Email for C++"
description: "Sends email message"
type: docs
weight: 530
url: /cpp/aspose.email.clients.graph/igraphclient/send/
---

## Send (1 of 4) {#send_1}

Sends email message

**Returns:** virtual void Aspose::Email::Clients::Graph::

```cpp
Send(System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| message | MailMessage Aspose::Email::MailMessage to send |

---

## Send (2 of 4) {#send_2}

Sends email message

**Returns:** virtual void Aspose::Email::Clients::Graph::

```cpp
Send(System::SharedPtr < Mapi::MapiMessage > message)
```

| Parameter | Description |
| --- | --- |
| message | Mapi message to send |

---

## Send (3 of 4) {#send_3}

Sends email message

**Returns:** virtual void Aspose::Email::Clients::Graph::

```cpp
Send(System::SharedPtr < Mapi::MapiMessage > message, bool saveToSentItems)
```

| Parameter | Description |
| --- | --- |
| message | Mapi message to send |
| saveToSentItems | Indicates whether to save the message in Sent Items. |

---

## Send (4 of 4) {#send_4}

Send a message in the draft folder. The draft message can be a new message draft, reply draft, reply-all draft, or a forward draft. The message is then saved in the Sent Items folder.

**Returns:** virtual void Aspose::Email::Clients::Graph::

```cpp
Send(System::String itemId)
```

| Parameter | Description |
| --- | --- |
| itemId | Item id of the draft message |

