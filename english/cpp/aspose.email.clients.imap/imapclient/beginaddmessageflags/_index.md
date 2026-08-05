---
title: "Aspose::Email::Clients::Imap::ImapClient::BeginAddMessageFlags method"
linktitle: "BeginAddMessageFlags"
articleTitle: "BeginAddMessageFlags"
second_title: "Aspose.Email for C++"
description: "Adds the flags to the message asynchronously"
type: docs
weight: 50
url: /cpp/aspose.email.clients.imap/imapclient/beginaddmessageflags/
---

## BeginAddMessageFlags (1 of 84) {#beginaddmessageflags_1}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |
| flags | The flags to be added |

---

## BeginAddMessageFlags (2 of 84) {#beginaddmessageflags_2}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |
| flags | The flags to be added |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginAddMessageFlags (3 of 84) {#beginaddmessageflags_3}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |
| flags | The flags to be added |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (4 of 84) {#beginaddmessageflags_4}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |
| flags | The flags to be added |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAddMessageFlags (5 of 84) {#beginaddmessageflags_5}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |
| flags | The flags to be added |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (6 of 84) {#beginaddmessageflags_6}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |
| flags | The flags to be added |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAddMessageFlags (7 of 84) {#beginaddmessageflags_7}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | Flag value |

---

## BeginAddMessageFlags (8 of 84) {#beginaddmessageflags_8}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginAddMessageFlags (9 of 84) {#beginaddmessageflags_9}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (10 of 84) {#beginaddmessageflags_10}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
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

## BeginAddMessageFlags (11 of 84) {#beginaddmessageflags_11}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (12 of 84) {#beginaddmessageflags_12}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAddMessageFlags (13 of 84) {#beginaddmessageflags_13}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |
| flags | The flags to be added |

---

## BeginAddMessageFlags (14 of 84) {#beginaddmessageflags_14}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |
| flags | The flags to be added |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginAddMessageFlags (15 of 84) {#beginaddmessageflags_15}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |
| flags | The flags to be added |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (16 of 84) {#beginaddmessageflags_16}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |
| flags | The flags to be added |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAddMessageFlags (17 of 84) {#beginaddmessageflags_17}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |
| flags | The flags to be added |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (18 of 84) {#beginaddmessageflags_18}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |
| flags | The flags to be added |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAddMessageFlags (19 of 84) {#beginaddmessageflags_19}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | Flag value |

---

## BeginAddMessageFlags (20 of 84) {#beginaddmessageflags_20}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginAddMessageFlags (21 of 84) {#beginaddmessageflags_21}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
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

## BeginAddMessageFlags (22 of 84) {#beginaddmessageflags_22}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
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

## BeginAddMessageFlags (23 of 84) {#beginaddmessageflags_23}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (24 of 84) {#beginaddmessageflags_24}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
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

## BeginAddMessageFlags (25 of 84) {#beginaddmessageflags_25}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |

---

## BeginAddMessageFlags (26 of 84) {#beginaddmessageflags_26}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginAddMessageFlags (27 of 84) {#beginaddmessageflags_27}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (28 of 84) {#beginaddmessageflags_28}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
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

## BeginAddMessageFlags (29 of 84) {#beginaddmessageflags_29}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (30 of 84) {#beginaddmessageflags_30}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAddMessageFlags (31 of 84) {#beginaddmessageflags_31}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |

---

## BeginAddMessageFlags (32 of 84) {#beginaddmessageflags_32}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginAddMessageFlags (33 of 84) {#beginaddmessageflags_33}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (34 of 84) {#beginaddmessageflags_34}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
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

## BeginAddMessageFlags (35 of 84) {#beginaddmessageflags_35}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (36 of 84) {#beginaddmessageflags_36}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAddMessageFlags (37 of 84) {#beginaddmessageflags_37}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| flags | Flag value |

---

## BeginAddMessageFlags (38 of 84) {#beginaddmessageflags_38}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginAddMessageFlags (39 of 84) {#beginaddmessageflags_39}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (40 of 84) {#beginaddmessageflags_40}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
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

## BeginAddMessageFlags (41 of 84) {#beginaddmessageflags_41}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (42 of 84) {#beginaddmessageflags_42}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAddMessageFlags (43 of 84) {#beginaddmessageflags_43}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | Flag value |

---

## BeginAddMessageFlags (44 of 84) {#beginaddmessageflags_44}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginAddMessageFlags (45 of 84) {#beginaddmessageflags_45}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
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

## BeginAddMessageFlags (46 of 84) {#beginaddmessageflags_46}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
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

## BeginAddMessageFlags (47 of 84) {#beginaddmessageflags_47}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (48 of 84) {#beginaddmessageflags_48}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
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

## BeginAddMessageFlags (49 of 84) {#beginaddmessageflags_49}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | Unique identifier of a message |
| flags | The flags to be added |

---

## BeginAddMessageFlags (50 of 84) {#beginaddmessageflags_50}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | Unique identifier of a message |
| flags | The flags to be added |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginAddMessageFlags (51 of 84) {#beginaddmessageflags_51}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | Unique identifier of a message |
| flags | The flags to be added |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (52 of 84) {#beginaddmessageflags_52}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | Unique identifier of a message |
| flags | The flags to be added |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAddMessageFlags (53 of 84) {#beginaddmessageflags_53}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | Unique identifier of a message |
| flags | The flags to be added |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (54 of 84) {#beginaddmessageflags_54}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < IConnection > connection, System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | Unique identifier of a message |
| flags | The flags to be added |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAddMessageFlags (55 of 84) {#beginaddmessageflags_55}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |

---

## BeginAddMessageFlags (56 of 84) {#beginaddmessageflags_56}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginAddMessageFlags (57 of 84) {#beginaddmessageflags_57}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (58 of 84) {#beginaddmessageflags_58}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAddMessageFlags (59 of 84) {#beginaddmessageflags_59}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (60 of 84) {#beginaddmessageflags_60}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAddMessageFlags (61 of 84) {#beginaddmessageflags_61}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |

---

## BeginAddMessageFlags (62 of 84) {#beginaddmessageflags_62}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginAddMessageFlags (63 of 84) {#beginaddmessageflags_63}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (64 of 84) {#beginaddmessageflags_64}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAddMessageFlags (65 of 84) {#beginaddmessageflags_65}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (66 of 84) {#beginaddmessageflags_66}

Adds the flags of the message

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAddMessageFlags (67 of 84) {#beginaddmessageflags_67}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| flags | Flag value |

---

## BeginAddMessageFlags (68 of 84) {#beginaddmessageflags_68}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginAddMessageFlags (69 of 84) {#beginaddmessageflags_69}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (70 of 84) {#beginaddmessageflags_70}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAddMessageFlags (71 of 84) {#beginaddmessageflags_71}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (72 of 84) {#beginaddmessageflags_72}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAddMessageFlags (73 of 84) {#beginaddmessageflags_73}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | Flag value |

---

## BeginAddMessageFlags (74 of 84) {#beginaddmessageflags_74}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginAddMessageFlags (75 of 84) {#beginaddmessageflags_75}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | Flag value |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (76 of 84) {#beginaddmessageflags_76}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
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

## BeginAddMessageFlags (77 of 84) {#beginaddmessageflags_77}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (78 of 84) {#beginaddmessageflags_78}

Adds the flags of the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | Flag value |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAddMessageFlags (79 of 84) {#beginaddmessageflags_79}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| uniqueId | Unique identifier of a message |
| flags | The flags to be added |

---

## BeginAddMessageFlags (80 of 84) {#beginaddmessageflags_80}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| uniqueId | Unique identifier of a message |
| flags | The flags to be added |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginAddMessageFlags (81 of 84) {#beginaddmessageflags_81}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| uniqueId | Unique identifier of a message |
| flags | The flags to be added |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (82 of 84) {#beginaddmessageflags_82}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| uniqueId | Unique identifier of a message |
| flags | The flags to be added |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAddMessageFlags (83 of 84) {#beginaddmessageflags_83}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| uniqueId | Unique identifier of a message |
| flags | The flags to be added |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAddMessageFlags (84 of 84) {#beginaddmessageflags_84}

Adds the flags to the message asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAddMessageFlags(System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| uniqueId | Unique identifier of a message |
| flags | The flags to be added |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

