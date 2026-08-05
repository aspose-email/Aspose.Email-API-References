---
title: "Aspose::Email::Clients::Imap::ImapClient::BeginFetchAttachment method"
linktitle: "BeginFetchAttachment"
articleTitle: "BeginFetchAttachment"
second_title: "Aspose.Email for C++"
description: "Begins fetch an attachment."
type: docs
weight: 190
url: /cpp/aspose.email.clients.imap/imapclient/beginfetchattachment/
---

## BeginFetchAttachment (1 of 6) {#beginfetchattachment_1}

Begins fetch an attachment.

**Returns:** Fetched attachment.

```cpp
BeginFetchAttachment(int32_t sequenceNumber, System::String attachmentName)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of a message |
| attachmentName | Attachment name |

---

## BeginFetchAttachment (2 of 6) {#beginfetchattachment_2}

Begins fetch an attachment.

**Returns:** Fetched attachment.

```cpp
BeginFetchAttachment(int32_t sequenceNumber, System::String attachmentName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of a message |
| attachmentName | Attachment name |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginFetchAttachment (3 of 6) {#beginfetchattachment_3}

Begins fetch an attachment.

**Returns:** Fetched attachment.

```cpp
BeginFetchAttachment(int32_t sequenceNumber, System::String attachmentName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of a message |
| attachmentName | Attachment name |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginFetchAttachment (4 of 6) {#beginfetchattachment_4}

Begins fetch an attachment.

**Returns:** Fetched attachment.

```cpp
BeginFetchAttachment(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::String attachmentName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of a message |
| attachmentName | Attachment name |

---

## BeginFetchAttachment (5 of 6) {#beginfetchattachment_5}

Begins fetch an attachment.

**Returns:** Fetched attachment.

```cpp
BeginFetchAttachment(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::String attachmentName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of a message |
| attachmentName | Attachment name |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginFetchAttachment (6 of 6) {#beginfetchattachment_6}

Begins fetch an attachment.

**Returns:** Fetched attachment.

```cpp
BeginFetchAttachment(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::String attachmentName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of a message |
| attachmentName | Attachment name |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

