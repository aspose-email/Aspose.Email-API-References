---
title: "Aspose::Email::Clients::Smtp::SmtpClient::Send method"
linktitle: "Send"
articleTitle: "Send"
second_title: "Aspose.Email for C++"
description: "Send the specified message."
type: docs
weight: 230
url: /cpp/aspose.email.clients.smtp/smtpclient/send/
---

## Send (1 of 10) {#send_1}

Send the specified message.

**Returns:** void Aspose::Email::Clients::Smtp::

```cpp
Send(const System::ArrayPtr< System::SharedPtr < MailMessage >> & messages)
```

| Parameter | Description |
| --- | --- |
| messages | The array of MailMessage that represents an email-messages to send. |

---

## Send (2 of 10) {#send_2}

Send the specified message.

**Returns:** void Aspose::Email::Clients::Smtp::

```cpp
Send(System::SharedPtr < IConnection > connection, const System::ArrayPtr< System::SharedPtr < MailMessage >> & messages)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messages | The array of MailMessage that represents an email-messages to send. |

---

## Send (3 of 10) {#send_3}

Send the specified message.

**Returns:** void Aspose::Email::Clients::Smtp::

```cpp
Send(System::SharedPtr < IConnection > connection, System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| message | The MailMessage that represents an email-message. |

---

## Send (4 of 10) {#send_4}

Send the specified message collection.

**Returns:** void Aspose::Email::Clients::Smtp::

```cpp
Send(System::SharedPtr < IConnection > connection, System::SharedPtr < MailMessageCollection > messages)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messages | The collection of messages. |

---

## Send (5 of 10) {#send_5}

Send the specified messages.

**Returns:** void Aspose::Email::Clients::Smtp::

```cpp
Send(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messages | The IEnumerator that supports a message iteration. |

---

## Send (6 of 10) {#send_6}

Creates and sends the specified message.

**Returns:** void Aspose::Email::Clients::Smtp::

```cpp
Send(System::SharedPtr < IConnection > connection, System::String from, System::String recipients, System::String subject, System::String body)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| from | A String that contains the address of message sender. |
| recipients | A String that contains the address of recipients. |
| subject | A subject of message. |
| body | A body of message. |

---

## Send (7 of 10) {#send_7}

Send the specified message.

**Returns:** void Aspose::Email::Clients::Smtp::

```cpp
Send(System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| message | The MailMessage that represents an email-message. |

---

## Send (8 of 10) {#send_8}

Send the specified message collection.

**Returns:** void Aspose::Email::Clients::Smtp::

```cpp
Send(System::SharedPtr < MailMessageCollection > messages)
```

| Parameter | Description |
| --- | --- |
| messages | The collection of messages. |

---

## Send (9 of 10) {#send_9}

Send the specified messages.

**Returns:** void Aspose::Email::Clients::Smtp::

```cpp
Send(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages)
```

| Parameter | Description |
| --- | --- |
| messages | The IEnumerator that supports a message iteration. |

---

## Send (10 of 10) {#send_10}

Creates and sends the specified message.

**Returns:** void Aspose::Email::Clients::Smtp::

```cpp
Send(System::String from, System::String recipients, System::String subject, System::String body)
```

| Parameter | Description |
| --- | --- |
| from | A String that contains the address of message sender. |
| recipients | A String that contains the address of recipients. |
| subject | A subject of message. |
| body | A body of message. |

