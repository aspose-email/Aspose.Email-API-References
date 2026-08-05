---
title: "Aspose::Email::Clients::Imap::ImapClient::BeginCopyMessages method"
linktitle: "BeginCopyMessages"
articleTitle: "BeginCopyMessages"
second_title: "Aspose.Email for C++"
description: "Begins copy operation asynchronously."
type: docs
weight: 130
url: /cpp/aspose.email.clients.imap/imapclient/begincopymessages/
---

## BeginCopyMessages (1 of 30) {#begincopymessages_1}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(int32_t startSequence, int32_t endSequence, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |

---

## BeginCopyMessages (2 of 30) {#begincopymessages_2}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(int32_t startSequence, int32_t endSequence, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginCopyMessages (3 of 30) {#begincopymessages_3}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(int32_t startSequence, int32_t endSequence, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginCopyMessages (4 of 30) {#begincopymessages_4}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |

---

## BeginCopyMessages (5 of 30) {#begincopymessages_5}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginCopyMessages (6 of 30) {#begincopymessages_6}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginCopyMessages (7 of 30) {#begincopymessages_7}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |

---

## BeginCopyMessages (8 of 30) {#begincopymessages_8}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginCopyMessages (9 of 30) {#begincopymessages_9}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginCopyMessages (10 of 30) {#begincopymessages_10}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |

---

## BeginCopyMessages (11 of 30) {#begincopymessages_11}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginCopyMessages (12 of 30) {#begincopymessages_12}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginCopyMessages (13 of 30) {#begincopymessages_13}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |

---

## BeginCopyMessages (14 of 30) {#begincopymessages_14}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginCopyMessages (15 of 30) {#begincopymessages_15}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginCopyMessages (16 of 30) {#begincopymessages_16}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |

---

## BeginCopyMessages (17 of 30) {#begincopymessages_17}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginCopyMessages (18 of 30) {#begincopymessages_18}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginCopyMessages (19 of 30) {#begincopymessages_19}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |

---

## BeginCopyMessages (20 of 30) {#begincopymessages_20}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginCopyMessages (21 of 30) {#begincopymessages_21}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginCopyMessages (22 of 30) {#begincopymessages_22}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |

---

## BeginCopyMessages (23 of 30) {#begincopymessages_23}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginCopyMessages (24 of 30) {#begincopymessages_24}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginCopyMessages (25 of 30) {#begincopymessages_25}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |

---

## BeginCopyMessages (26 of 30) {#begincopymessages_26}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginCopyMessages (27 of 30) {#begincopymessages_27}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginCopyMessages (28 of 30) {#begincopymessages_28}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::String startUid, System::String endUid, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |

---

## BeginCopyMessages (29 of 30) {#begincopymessages_29}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::String startUid, System::String endUid, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginCopyMessages (30 of 30) {#begincopymessages_30}

Begins copy operation asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCopyMessages(System::String startUid, System::String endUid, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

