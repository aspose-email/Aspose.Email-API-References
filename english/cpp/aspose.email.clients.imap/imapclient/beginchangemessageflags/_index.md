---
title: "Aspose::Email::Clients::Imap::ImapClient::BeginChangeMessageFlags method"
linktitle: "BeginChangeMessageFlags"
articleTitle: "BeginChangeMessageFlags"
second_title: "Aspose.Email for C++"
description: "Changes the flags of the message"
type: docs
weight: 90
url: /cpp/aspose.email.clients.imap/imapclient/beginchangemessageflags/
---

## BeginChangeMessageFlags (1 of 84) {#beginchangemessageflags_1}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | Sequence number of a message |
| flags | Flag value |

---

## BeginChangeMessageFlags (2 of 84) {#beginchangemessageflags_2}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | Sequence number of a message |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginChangeMessageFlags (3 of 84) {#beginchangemessageflags_3}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | Sequence number of a message |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (4 of 84) {#beginchangemessageflags_4}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | Sequence number of a message |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (5 of 84) {#beginchangemessageflags_5}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | Sequence number of a message |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (6 of 84) {#beginchangemessageflags_6}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | Sequence number of a message |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (7 of 84) {#beginchangemessageflags_7}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | Flag value |

---

## BeginChangeMessageFlags (8 of 84) {#beginchangemessageflags_8}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginChangeMessageFlags (9 of 84) {#beginchangemessageflags_9}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (10 of 84) {#beginchangemessageflags_10}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (11 of 84) {#beginchangemessageflags_11}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (12 of 84) {#beginchangemessageflags_12}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (13 of 84) {#beginchangemessageflags_13}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | Sequence number of a message |
| flags | Flag value |

---

## BeginChangeMessageFlags (14 of 84) {#beginchangemessageflags_14}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | Sequence number of a message |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginChangeMessageFlags (15 of 84) {#beginchangemessageflags_15}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | Sequence number of a message |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (16 of 84) {#beginchangemessageflags_16}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | Sequence number of a message |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (17 of 84) {#beginchangemessageflags_17}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | Sequence number of a message |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (18 of 84) {#beginchangemessageflags_18}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | Sequence number of a message |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (19 of 84) {#beginchangemessageflags_19}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | Flag value |

---

## BeginChangeMessageFlags (20 of 84) {#beginchangemessageflags_20}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginChangeMessageFlags (21 of 84) {#beginchangemessageflags_21}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (22 of 84) {#beginchangemessageflags_22}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (23 of 84) {#beginchangemessageflags_23}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (24 of 84) {#beginchangemessageflags_24}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (25 of 84) {#beginchangemessageflags_25}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |

---

## BeginChangeMessageFlags (26 of 84) {#beginchangemessageflags_26}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginChangeMessageFlags (27 of 84) {#beginchangemessageflags_27}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (28 of 84) {#beginchangemessageflags_28}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (29 of 84) {#beginchangemessageflags_29}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (30 of 84) {#beginchangemessageflags_30}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (31 of 84) {#beginchangemessageflags_31}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |

---

## BeginChangeMessageFlags (32 of 84) {#beginchangemessageflags_32}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginChangeMessageFlags (33 of 84) {#beginchangemessageflags_33}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (34 of 84) {#beginchangemessageflags_34}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (35 of 84) {#beginchangemessageflags_35}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (36 of 84) {#beginchangemessageflags_36}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (37 of 84) {#beginchangemessageflags_37}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| flags | Flag value |

---

## BeginChangeMessageFlags (38 of 84) {#beginchangemessageflags_38}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginChangeMessageFlags (39 of 84) {#beginchangemessageflags_39}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (40 of 84) {#beginchangemessageflags_40}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (41 of 84) {#beginchangemessageflags_41}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (42 of 84) {#beginchangemessageflags_42}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (43 of 84) {#beginchangemessageflags_43}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | Flag value |

---

## BeginChangeMessageFlags (44 of 84) {#beginchangemessageflags_44}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginChangeMessageFlags (45 of 84) {#beginchangemessageflags_45}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (46 of 84) {#beginchangemessageflags_46}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (47 of 84) {#beginchangemessageflags_47}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (48 of 84) {#beginchangemessageflags_48}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (49 of 84) {#beginchangemessageflags_49}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | Unique identifier of a message |
| flags | Flag value |

---

## BeginChangeMessageFlags (50 of 84) {#beginchangemessageflags_50}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | Unique identifier of a message |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginChangeMessageFlags (51 of 84) {#beginchangemessageflags_51}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | Unique identifier of a message |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (52 of 84) {#beginchangemessageflags_52}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | Unique identifier of a message |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (53 of 84) {#beginchangemessageflags_53}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | Unique identifier of a message |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (54 of 84) {#beginchangemessageflags_54}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < IConnection > connection, System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | Unique identifier of a message |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (55 of 84) {#beginchangemessageflags_55}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |

---

## BeginChangeMessageFlags (56 of 84) {#beginchangemessageflags_56}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginChangeMessageFlags (57 of 84) {#beginchangemessageflags_57}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (58 of 84) {#beginchangemessageflags_58}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (59 of 84) {#beginchangemessageflags_59}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (60 of 84) {#beginchangemessageflags_60}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (61 of 84) {#beginchangemessageflags_61}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |

---

## BeginChangeMessageFlags (62 of 84) {#beginchangemessageflags_62}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginChangeMessageFlags (63 of 84) {#beginchangemessageflags_63}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (64 of 84) {#beginchangemessageflags_64}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (65 of 84) {#beginchangemessageflags_65}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (66 of 84) {#beginchangemessageflags_66}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (67 of 84) {#beginchangemessageflags_67}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| flags | Flag value |

---

## BeginChangeMessageFlags (68 of 84) {#beginchangemessageflags_68}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginChangeMessageFlags (69 of 84) {#beginchangemessageflags_69}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (70 of 84) {#beginchangemessageflags_70}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (71 of 84) {#beginchangemessageflags_71}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (72 of 84) {#beginchangemessageflags_72}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (73 of 84) {#beginchangemessageflags_73}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | Flag value |

---

## BeginChangeMessageFlags (74 of 84) {#beginchangemessageflags_74}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginChangeMessageFlags (75 of 84) {#beginchangemessageflags_75}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (76 of 84) {#beginchangemessageflags_76}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (77 of 84) {#beginchangemessageflags_77}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (78 of 84) {#beginchangemessageflags_78}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (79 of 84) {#beginchangemessageflags_79}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| uniqueId | Unique identifier of a message |
| flags | Flag value |

---

## BeginChangeMessageFlags (80 of 84) {#beginchangemessageflags_80}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| uniqueId | Unique identifier of a message |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginChangeMessageFlags (81 of 84) {#beginchangemessageflags_81}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| uniqueId | Unique identifier of a message |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (82 of 84) {#beginchangemessageflags_82}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| uniqueId | Unique identifier of a message |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginChangeMessageFlags (83 of 84) {#beginchangemessageflags_83}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| uniqueId | Unique identifier of a message |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginChangeMessageFlags (84 of 84) {#beginchangemessageflags_84}

Changes the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginChangeMessageFlags(System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| uniqueId | Unique identifier of a message |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

