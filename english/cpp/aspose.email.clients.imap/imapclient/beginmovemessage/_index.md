---
title: "Aspose::Email::Clients::Imap::ImapClient::BeginMoveMessage method"
linktitle: "BeginMoveMessage"
articleTitle: "BeginMoveMessage"
second_title: "Aspose.Email for C++"
description: "Begins an asynchronous moving."
type: docs
weight: 360
url: /cpp/aspose.email.clients.imap/imapclient/beginmovemessage/
---

## BeginMoveMessage (1 of 24) {#beginmovemessage_1}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(int32_t sequenceNumber, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |
| folderName | Folder name where a message is to be moved |

---

## BeginMoveMessage (2 of 24) {#beginmovemessage_2}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(int32_t sequenceNumber, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## BeginMoveMessage (3 of 24) {#beginmovemessage_3}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(int32_t sequenceNumber, System::String folderName, bool commitDeletions, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessage (4 of 24) {#beginmovemessage_4}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(int32_t sequenceNumber, System::String folderName, bool commitDeletions, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessage (5 of 24) {#beginmovemessage_5}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(int32_t sequenceNumber, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessage (6 of 24) {#beginmovemessage_6}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(int32_t sequenceNumber, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessage (7 of 24) {#beginmovemessage_7}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |
| folderName | Folder name where a message is to be moved |

---

## BeginMoveMessage (8 of 24) {#beginmovemessage_8}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## BeginMoveMessage (9 of 24) {#beginmovemessage_9}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::String folderName, bool commitDeletions, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessage (10 of 24) {#beginmovemessage_10}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::String folderName, bool commitDeletions, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessage (11 of 24) {#beginmovemessage_11}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessage (12 of 24) {#beginmovemessage_12}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessage (13 of 24) {#beginmovemessage_13}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(System::SharedPtr < IConnection > connection, System::String uniqueId, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The unique Id of the message |
| folderName | Folder name where a message is to be moved |

---

## BeginMoveMessage (14 of 24) {#beginmovemessage_14}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(System::SharedPtr < IConnection > connection, System::String uniqueId, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The unique Id of the message |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## BeginMoveMessage (15 of 24) {#beginmovemessage_15}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(System::SharedPtr < IConnection > connection, System::String uniqueId, System::String folderName, bool commitDeletions, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The unique Id of the message |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessage (16 of 24) {#beginmovemessage_16}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(System::SharedPtr < IConnection > connection, System::String uniqueId, System::String folderName, bool commitDeletions, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The unique Id of the message |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessage (17 of 24) {#beginmovemessage_17}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(System::SharedPtr < IConnection > connection, System::String uniqueId, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The unique Id of the message |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessage (18 of 24) {#beginmovemessage_18}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(System::SharedPtr < IConnection > connection, System::String uniqueId, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The unique Id of the message |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessage (19 of 24) {#beginmovemessage_19}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(System::String uniqueId, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The unique Id of the message |
| folderName | Folder name where a message is to be moved |

---

## BeginMoveMessage (20 of 24) {#beginmovemessage_20}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(System::String uniqueId, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The unique Id of the message |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## BeginMoveMessage (21 of 24) {#beginmovemessage_21}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(System::String uniqueId, System::String folderName, bool commitDeletions, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The unique Id of the message |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessage (22 of 24) {#beginmovemessage_22}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(System::String uniqueId, System::String folderName, bool commitDeletions, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The unique Id of the message |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessage (23 of 24) {#beginmovemessage_23}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(System::String uniqueId, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The unique Id of the message |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessage (24 of 24) {#beginmovemessage_24}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessage(System::String uniqueId, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The unique Id of the message |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

