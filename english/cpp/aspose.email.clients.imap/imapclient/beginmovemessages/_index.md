---
title: "Aspose::Email::Clients::Imap::ImapClient::BeginMoveMessages method"
linktitle: "BeginMoveMessages"
articleTitle: "BeginMoveMessages"
second_title: "Aspose.Email for C++"
description: "Begins an asynchronous moving."
type: docs
weight: 370
url: /cpp/aspose.email.clients.imap/imapclient/beginmovemessages/
---

## BeginMoveMessages (1 of 60) {#beginmovemessages_1}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(int32_t startSequence, int32_t endSequence, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |

---

## BeginMoveMessages (2 of 60) {#beginmovemessages_2}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(int32_t startSequence, int32_t endSequence, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## BeginMoveMessages (3 of 60) {#beginmovemessages_3}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(int32_t startSequence, int32_t endSequence, System::String folderName, bool commitDeletions, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessages (4 of 60) {#beginmovemessages_4}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(int32_t startSequence, int32_t endSequence, System::String folderName, bool commitDeletions, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessages (5 of 60) {#beginmovemessages_5}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(int32_t startSequence, int32_t endSequence, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessages (6 of 60) {#beginmovemessages_6}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(int32_t startSequence, int32_t endSequence, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessages (7 of 60) {#beginmovemessages_7}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |

---

## BeginMoveMessages (8 of 60) {#beginmovemessages_8}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## BeginMoveMessages (9 of 60) {#beginmovemessages_9}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::String folderName, bool commitDeletions, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessages (10 of 60) {#beginmovemessages_10}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::String folderName, bool commitDeletions, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessages (11 of 60) {#beginmovemessages_11}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessages (12 of 60) {#beginmovemessages_12}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
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

## BeginMoveMessages (13 of 60) {#beginmovemessages_13}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |

---

## BeginMoveMessages (14 of 60) {#beginmovemessages_14}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## BeginMoveMessages (15 of 60) {#beginmovemessages_15}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName, bool commitDeletions, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessages (16 of 60) {#beginmovemessages_16}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName, bool commitDeletions, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessages (17 of 60) {#beginmovemessages_17}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessages (18 of 60) {#beginmovemessages_18}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessages (19 of 60) {#beginmovemessages_19}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |

---

## BeginMoveMessages (20 of 60) {#beginmovemessages_20}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## BeginMoveMessages (21 of 60) {#beginmovemessages_21}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName, bool commitDeletions, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessages (22 of 60) {#beginmovemessages_22}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName, bool commitDeletions, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessages (23 of 60) {#beginmovemessages_23}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessages (24 of 60) {#beginmovemessages_24}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessages (25 of 60) {#beginmovemessages_25}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |

---

## BeginMoveMessages (26 of 60) {#beginmovemessages_26}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## BeginMoveMessages (27 of 60) {#beginmovemessages_27}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName, bool commitDeletions, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessages (28 of 60) {#beginmovemessages_28}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName, bool commitDeletions, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessages (29 of 60) {#beginmovemessages_29}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessages (30 of 60) {#beginmovemessages_30}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessages (31 of 60) {#beginmovemessages_31}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |

---

## BeginMoveMessages (32 of 60) {#beginmovemessages_32}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## BeginMoveMessages (33 of 60) {#beginmovemessages_33}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::String folderName, bool commitDeletions, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessages (34 of 60) {#beginmovemessages_34}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::String folderName, bool commitDeletions, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessages (35 of 60) {#beginmovemessages_35}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessages (36 of 60) {#beginmovemessages_36}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
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

## BeginMoveMessages (37 of 60) {#beginmovemessages_37}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |

---

## BeginMoveMessages (38 of 60) {#beginmovemessages_38}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## BeginMoveMessages (39 of 60) {#beginmovemessages_39}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName, bool commitDeletions, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessages (40 of 60) {#beginmovemessages_40}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName, bool commitDeletions, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessages (41 of 60) {#beginmovemessages_41}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessages (42 of 60) {#beginmovemessages_42}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessages (43 of 60) {#beginmovemessages_43}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |

---

## BeginMoveMessages (44 of 60) {#beginmovemessages_44}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## BeginMoveMessages (45 of 60) {#beginmovemessages_45}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName, bool commitDeletions, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessages (46 of 60) {#beginmovemessages_46}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName, bool commitDeletions, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessages (47 of 60) {#beginmovemessages_47}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessages (48 of 60) {#beginmovemessages_48}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessages (49 of 60) {#beginmovemessages_49}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |

---

## BeginMoveMessages (50 of 60) {#beginmovemessages_50}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## BeginMoveMessages (51 of 60) {#beginmovemessages_51}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName, bool commitDeletions, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessages (52 of 60) {#beginmovemessages_52}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName, bool commitDeletions, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessages (53 of 60) {#beginmovemessages_53}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessages (54 of 60) {#beginmovemessages_54}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessages (55 of 60) {#beginmovemessages_55}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::String startUid, System::String endUid, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |

---

## BeginMoveMessages (56 of 60) {#beginmovemessages_56}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::String startUid, System::String endUid, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## BeginMoveMessages (57 of 60) {#beginmovemessages_57}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::String startUid, System::String endUid, System::String folderName, bool commitDeletions, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessages (58 of 60) {#beginmovemessages_58}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::String startUid, System::String endUid, System::String folderName, bool commitDeletions, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginMoveMessages (59 of 60) {#beginmovemessages_59}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::String startUid, System::String endUid, System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginMoveMessages (60 of 60) {#beginmovemessages_60}

Begins an asynchronous moving.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginMoveMessages(System::String startUid, System::String endUid, System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

