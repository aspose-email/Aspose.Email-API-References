---
title: "Aspose::Email::Clients::Smtp::SmtpClient::BeginSend method"
linktitle: "BeginSend"
articleTitle: "BeginSend"
second_title: "Aspose.Email for C++"
description: "Please note: this method is used only for the .NET framework with versions earlier than 4.5."
type: docs
weight: 30
url: /cpp/aspose.email.clients.smtp/smtpclient/beginsend/
---

## BeginSend (1 of 26) {#beginsend_1}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(const System::ArrayPtr< System::SharedPtr < MailMessage >> & messages)
```

| Parameter | Description |
| --- | --- |
| messages | The array of MailMessage that represents an email-messages to send. |

---

## BeginSend (2 of 26) {#beginsend_2}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < IConnection > connection, const System::ArrayPtr< System::SharedPtr < MailMessage >> & messages)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messages | The array of MailMessage that represents an email-messages to send. |

---

## BeginSend (3 of 26) {#beginsend_3}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < IConnection > connection, System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| message | Represents an e-mail message |

---

## BeginSend (4 of 26) {#beginsend_4}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < IConnection > connection, System::SharedPtr < MailMessage > message, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| message | Represents an e-mail message |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginSend (5 of 26) {#beginsend_5}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < IConnection > connection, System::SharedPtr < MailMessage > message, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| message | Represents an e-mail message |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginSend (6 of 26) {#beginsend_6}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messages | The array of MailMessage that represents an email-messages to send. |

---

## BeginSend (7 of 26) {#beginsend_7}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messages | The array of MailMessage that represents an email-messages to send. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginSend (8 of 26) {#beginsend_8}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messages | The array of MailMessage that represents an email-messages to send. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginSend (9 of 26) {#beginsend_9}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages, System::EventHandler< System::SharedPtr < MailMessageEventArgs >> messageSentDelegate)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messages | The array of MailMessage that represents an email-messages to send. |
| messageSentDelegate | References a method to be called when a message has been sent. |

---

## BeginSend (10 of 26) {#beginsend_10}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages, System::EventHandler< System::SharedPtr < MailMessageEventArgs >> messageSentDelegate, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messages | The array of MailMessage that represents an email-messages to send. |
| messageSentDelegate | References a method to be called when a message has been sent. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginSend (11 of 26) {#beginsend_11}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages, System::EventHandler< System::SharedPtr < MailMessageEventArgs >> messageSentDelegate, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messages | The array of MailMessage that represents an email-messages to send. |
| messageSentDelegate | References a method to be called when a message has been sent. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginSend (12 of 26) {#beginsend_12}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < IConnection > connection, System::String from, System::String recipients, System::String subject, System::String body)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| from | A String that contains the address of message sender. |
| recipients | A String that contains the address of recipients. |
| subject | A subject of message. |
| body | A body of message. |

---

## BeginSend (13 of 26) {#beginsend_13}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < IConnection > connection, System::String from, System::String recipients, System::String subject, System::String body, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| from | A String that contains the address of message sender. |
| recipients | A String that contains the address of recipients. |
| subject | A subject of message. |
| body | A body of message. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginSend (14 of 26) {#beginsend_14}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < IConnection > connection, System::String from, System::String recipients, System::String subject, System::String body, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| from | A String that contains the address of message sender. |
| recipients | A String that contains the address of recipients. |
| subject | A subject of message. |
| body | A body of message. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginSend (15 of 26) {#beginsend_15}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| message | Represents an e-mail message |

---

## BeginSend (16 of 26) {#beginsend_16}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < MailMessage > message, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| message | Represents an e-mail message |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginSend (17 of 26) {#beginsend_17}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < MailMessage > message, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| message | Represents an e-mail message |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginSend (18 of 26) {#beginsend_18}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages)
```

| Parameter | Description |
| --- | --- |
| messages | The array of MailMessage that represents an email-messages to send. |

---

## BeginSend (19 of 26) {#beginsend_19}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| messages | The array of MailMessage that represents an email-messages to send. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginSend (20 of 26) {#beginsend_20}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| messages | The array of MailMessage that represents an email-messages to send. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginSend (21 of 26) {#beginsend_21}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages, System::EventHandler< System::SharedPtr < MailMessageEventArgs >> messageSentDelegate)
```

| Parameter | Description |
| --- | --- |
| messages | The array of MailMessage that represents an email-messages to send. |
| messageSentDelegate | References a method to be called when a message has been sent. |

---

## BeginSend (22 of 26) {#beginsend_22}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages, System::EventHandler< System::SharedPtr < MailMessageEventArgs >> messageSentDelegate, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| messages | The array of MailMessage that represents an email-messages to send. |
| messageSentDelegate | References a method to be called when a message has been sent. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginSend (23 of 26) {#beginsend_23}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages, System::EventHandler< System::SharedPtr < MailMessageEventArgs >> messageSentDelegate, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| messages | The array of MailMessage that represents an email-messages to send. |
| messageSentDelegate | References a method to be called when a message has been sent. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginSend (24 of 26) {#beginsend_24}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::String from, System::String recipients, System::String subject, System::String body)
```

| Parameter | Description |
| --- | --- |
| from | A String that contains the address of message sender. |
| recipients | A String that contains the address of recipients. |
| subject | A subject of message. |
| body | A body of message. |

---

## BeginSend (25 of 26) {#beginsend_25}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::String from, System::String recipients, System::String subject, System::String body, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| from | A String that contains the address of message sender. |
| recipients | A String that contains the address of recipients. |
| subject | A subject of message. |
| body | A body of message. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginSend (26 of 26) {#beginsend_26}

Please note: this method is used only for the .NET framework with versions earlier than 4.5.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSend(System::String from, System::String recipients, System::String subject, System::String body, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| from | A String that contains the address of message sender. |
| recipients | A String that contains the address of recipients. |
| subject | A subject of message. |
| body | A body of message. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

