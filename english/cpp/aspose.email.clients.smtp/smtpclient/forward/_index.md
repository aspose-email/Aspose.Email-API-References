---
title: "Aspose::Email::Clients::Smtp::SmtpClient::Forward method"
linktitle: "Forward"
articleTitle: "Forward"
second_title: "Aspose.Email for C++"
description: "Forwards specified message to recipient"
type: docs
weight: 110
url: /cpp/aspose.email.clients.smtp/smtpclient/forward/
---

## Forward (1 of 6) {#forward_1}

Forwards specified message to recipient

**Returns:** void Aspose::Email::Clients::Smtp::

```cpp
Forward(System::SharedPtr < IConnection > connection, System::String sender, System::SharedPtr < MailAddressCollection > recipients, System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sender | Sender of the forwarded message. |
| recipients | Recipients of the forwarded message. |
| message | The message for a forwarding. |

---

## Forward (2 of 6) {#forward_2}

Forwards specified message to recipient

**Returns:** void Aspose::Email::Clients::Smtp::

```cpp
Forward(System::SharedPtr < IConnection > connection, System::String sender, System::SharedPtr < MailAddressCollection > recipients, System::SharedPtr < System::IO::Stream > messageStream)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sender | Sender of the forwarded message. |
| recipients | Recipients of the forwarded message. |
| messageStream | The stream that represents message in eml format. |

---

## Forward (3 of 6) {#forward_3}

Forwards specified message to recipient

**Returns:** void Aspose::Email::Clients::Smtp::

```cpp
Forward(System::SharedPtr < IConnection > connection, System::String sender, System::String recipient, System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sender | Sender of the forwarded message. |
| recipient | Recipient of the forwarded message. |
| message | The message for a forwarding. |

---

## Forward (4 of 6) {#forward_4}

Forwards specified message to recipient

**Returns:** void Aspose::Email::Clients::Smtp::

```cpp
Forward(System::String sender, System::SharedPtr < MailAddressCollection > recipients, System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| sender | Sender of the forwarded message. |
| recipients | Recipients of the forwarded message. |
| message | The message for a forwarding. |

---

## Forward (5 of 6) {#forward_5}

Forwards specified message to recipient

**Returns:** void Aspose::Email::Clients::Smtp::

```cpp
Forward(System::String sender, System::SharedPtr < MailAddressCollection > recipients, System::SharedPtr < System::IO::Stream > messageStream)
```

| Parameter | Description |
| --- | --- |
| sender | Sender of the forwarded message. |
| recipients | Recipients of the forwarded message. |
| messageStream | The stream that represents message in eml format. |

---

## Forward (6 of 6) {#forward_6}

Forwards specified message to recipient

**Returns:** void Aspose::Email::Clients::Smtp::

```cpp
Forward(System::String sender, System::String recipient, System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| sender | Sender of the forwarded message. |
| recipient | Recipient of the forwarded message. |
| message | The message for a forwarding. |

