---
title: "Aspose::Email::Clients::Imap::ImapClient::BeginFetchMessage method"
linktitle: "BeginFetchMessage"
articleTitle: "BeginFetchMessage"
second_title: "Aspose.Email for C++"
description: "Begins an asynchronous message fetching."
type: docs
weight: 200
url: /cpp/aspose.email.clients.imap/imapclient/beginfetchmessage/
---

## BeginFetchMessage (1 of 18) {#beginfetchmessage_1}

Begins an asynchronous message fetching.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginFetchMessage(int32_t sequenceNumber)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |

---

## BeginFetchMessage (2 of 18) {#beginfetchmessage_2}

Begins an asynchronous message fetching.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginFetchMessage(int32_t sequenceNumber, bool ignoreAttachment)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |
| ignoreAttachment | A value that defines whether the attachments should not be loaded. If it is set to true , then only message headers, message body and attachment information are fetched. Attachment content is not loaded |

---

## BeginFetchMessage (3 of 18) {#beginfetchmessage_3}

Begins an asynchronous message fetching.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginFetchMessage(int32_t sequenceNumber, bool ignoreAttachment, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |
| ignoreAttachment | A value that defines whether the attachments should not be loaded. If it is set to true , then only message headers, message body and attachment information are fetched. Attachment content is not loaded |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginFetchMessage (4 of 18) {#beginfetchmessage_4}

Begins an asynchronous message fetching.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginFetchMessage(int32_t sequenceNumber, bool ignoreAttachment, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |
| ignoreAttachment | A value that defines whether the attachments should not be loaded. If it is set to true , then only message headers, message body and attachment information are fetched. Attachment content is not loaded |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginFetchMessage (5 of 18) {#beginfetchmessage_5}

Begins an asynchronous message fetching.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginFetchMessage(int32_t sequenceNumber, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginFetchMessage (6 of 18) {#beginfetchmessage_6}

Begins an asynchronous message fetching.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginFetchMessage(int32_t sequenceNumber, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginFetchMessage (7 of 18) {#beginfetchmessage_7}

Begins an asynchronous message fetching.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginFetchMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |

---

## BeginFetchMessage (8 of 18) {#beginfetchmessage_8}

Begins an asynchronous message fetching.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginFetchMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, bool ignoreAttachment)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |
| ignoreAttachment | A value that defines whether the attachments should not be loaded. If it is set to true , then only message headers, message body and attachment information are fetched. Attachment content is not loaded |

---

## BeginFetchMessage (9 of 18) {#beginfetchmessage_9}

Begins an asynchronous message fetching.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginFetchMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, bool ignoreAttachment, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |
| ignoreAttachment | A value that defines whether the attachments should not be loaded. If it is set to true , then only message headers, message body and attachment information are fetched. Attachment content is not loaded |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginFetchMessage (10 of 18) {#beginfetchmessage_10}

Begins an asynchronous message fetching.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginFetchMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, bool ignoreAttachment, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |
| ignoreAttachment | A value that defines whether the attachments should not be loaded. If it is set to true , then only message headers, message body and attachment information are fetched. Attachment content is not loaded |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginFetchMessage (11 of 18) {#beginfetchmessage_11}

Begins an asynchronous message fetching.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginFetchMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginFetchMessage (12 of 18) {#beginfetchmessage_12}

Begins an asynchronous message fetching.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginFetchMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginFetchMessage (13 of 18) {#beginfetchmessage_13}

Begins an asynchronous message fetching.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginFetchMessage(System::SharedPtr < IConnection > connection, System::String uniqueId)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The unique id of message |

---

## BeginFetchMessage (14 of 18) {#beginfetchmessage_14}

Begins an asynchronous message fetching.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginFetchMessage(System::SharedPtr < IConnection > connection, System::String uniqueId, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The unique id of message |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginFetchMessage (15 of 18) {#beginfetchmessage_15}

Begins an asynchronous message fetching.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginFetchMessage(System::SharedPtr < IConnection > connection, System::String uniqueId, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The unique id of message |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginFetchMessage (16 of 18) {#beginfetchmessage_16}

Begins an asynchronous message fetching.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginFetchMessage(System::String uniqueId)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The unique id of message |

---

## BeginFetchMessage (17 of 18) {#beginfetchmessage_17}

Begins an asynchronous message fetching.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginFetchMessage(System::String uniqueId, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The unique id of message |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginFetchMessage (18 of 18) {#beginfetchmessage_18}

Begins an asynchronous message fetching.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginFetchMessage(System::String uniqueId, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The unique id of message |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

