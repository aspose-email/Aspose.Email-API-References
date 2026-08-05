---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::Send method"
linktitle: "Send"
articleTitle: "Send"
second_title: "Aspose.Email for C++"
description: "Sends the specified message."
type: docs
weight: 1270
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/send/
---

## Send (1 of 3) {#send_1}

Sends the specified message.

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
Send(System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| message | The message. |

---

## Send (2 of 3) {#send_2}

Sends the message.

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
Send(System::SharedPtr < MailMessage > message, System::SharedPtr < Mapi::FollowUpOptions > messageOptions)
```

| Parameter | Description |
| --- | --- |
| message | The MailMessage to be sent. |
| messageOptions | The FollowUpOptions that represents additional options for using follow-up flags and voting buttons. |

---

## Send (3 of 3) {#send_3}

Sends the specified message

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
Send(System::String from, System::String to, System::String subject, System::String body)
```

| Parameter | Description |
| --- | --- |
| from | From address |
| to | To address |
| subject | The subject of message |
| body | The body of message |

