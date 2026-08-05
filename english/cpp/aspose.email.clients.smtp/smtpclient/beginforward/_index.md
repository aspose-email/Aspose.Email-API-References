---
title: "Aspose::Email::Clients::Smtp::SmtpClient::BeginForward method"
linktitle: "BeginForward"
articleTitle: "BeginForward"
second_title: "Aspose.Email for C++"
description: "Please note: this method is used only for the .NET framework with versions earlier than 4.5."
type: docs
weight: 10
url: /cpp/aspose.email.clients.smtp/smtpclient/beginforward/
---

## BeginForward (1 of 13) {#beginforward_1}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginForward(System::SharedPtr < IConnection > connection, System::String sender, System::SharedPtr < MailAddressCollection > recipients, System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sender | Sender of the forwarded message. |
| recipients | Recipients of the forwarded message. |
| message | The message for a forwarding. |

---

## BeginForward (2 of 13) {#beginforward_2}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginForward(System::SharedPtr < IConnection > connection, System::String sender, System::SharedPtr < MailAddressCollection > recipients, System::SharedPtr < MailMessage > message, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sender | Sender of the forwarded message. |
| recipients | Recipients of the forwarded message. |
| message | The message for a forwarding. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginForward (3 of 13) {#beginforward_3}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginForward(System::SharedPtr < IConnection > connection, System::String sender, System::SharedPtr < MailAddressCollection > recipients, System::SharedPtr < MailMessage > message, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sender | Sender of the forwarded message. |
| recipients | Recipients of the forwarded message. |
| message | The message for a forwarding. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginForward (4 of 13) {#beginforward_4}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginForward(System::SharedPtr < IConnection > connection, System::String sender, System::SharedPtr < MailAddressCollection > recipients, System::SharedPtr < System::IO::Stream > messageStream, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sender | Sender of the forwarded message. |
| recipients | Recipients of the forwarded message. |
| messageStream | The stream that represents message in eml format. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginForward (5 of 13) {#beginforward_5}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginForward(System::SharedPtr < IConnection > connection, System::String sender, System::String recipient, System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sender | Sender of the forwarded message. |
| recipient | Recipient of the forwarded message. |
| message | The message for a forwarding. |

---

## BeginForward (6 of 13) {#beginforward_6}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginForward(System::SharedPtr < IConnection > connection, System::String sender, System::String recipient, System::SharedPtr < MailMessage > message, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sender | Sender of the forwarded message. |
| recipient | Recipients of the forwarded message. |
| message | The message for a forwarding. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginForward (7 of 13) {#beginforward_7}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginForward(System::SharedPtr < IConnection > connection, System::String sender, System::String recipient, System::SharedPtr < MailMessage > message, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sender | Sender of the forwarded message. |
| recipient | Recipients of the forwarded message. |
| message | The message for a forwarding. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginForward (8 of 13) {#beginforward_8}

Begins forward email asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginForward(System::String sender, System::SharedPtr < MailAddressCollection > recipients, System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| sender | Sender of the forwarded message. |
| recipients | Recipients of the forwarded message. |
| message | The message for a forwarding. |

---

## BeginForward (9 of 13) {#beginforward_9}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginForward(System::String sender, System::SharedPtr < MailAddressCollection > recipients, System::SharedPtr < MailMessage > message, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| sender | Sender of the forwarded message. |
| recipients | Recipients of the forwarded message. |
| message | The message for a forwarding. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginForward (10 of 13) {#beginforward_10}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginForward(System::String sender, System::SharedPtr < MailAddressCollection > recipients, System::SharedPtr < MailMessage > message, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sender | Sender of the forwarded message. |
| recipients | Recipients of the forwarded message. |
| message | The message for a forwarding. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginForward (11 of 13) {#beginforward_11}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginForward(System::String sender, System::String recipient, System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| sender | Sender of the forwarded message. |
| recipient | Recipients of the forwarded message. |
| message | The message for a forwarding. |

---

## BeginForward (12 of 13) {#beginforward_12}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginForward(System::String sender, System::String recipient, System::SharedPtr < MailMessage > message, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| sender | Sender of the forwarded message. |
| recipient | Recipients of the forwarded message. |
| message | The message for a forwarding. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginForward (13 of 13) {#beginforward_13}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginForward(System::String sender, System::String recipient, System::SharedPtr < MailMessage > message, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sender | Sender of the forwarded message. |
| recipient | Recipients of the forwarded message. |
| message | The message for a forwarding. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

