---
title: "Aspose::Email::Clients::Imap::ImapClient::BeginDeleteMessages method"
linktitle: "BeginDeleteMessages"
articleTitle: "BeginDeleteMessages"
second_title: "Aspose.Email for C++"
description: "Marks a message with the specified sequence number as deleted asynchronously"
type: docs
weight: 170
url: /cpp/aspose.email.clients.imap/imapclient/begindeletemessages/
---

## BeginDeleteMessages (1 of 96) {#begindeletemessages_1}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(int32_t startSequence, int32_t endSequence)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |

---

## BeginDeleteMessages (2 of 96) {#begindeletemessages_2}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(int32_t startSequence, int32_t endSequence, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginDeleteMessages (3 of 96) {#begindeletemessages_3}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(int32_t startSequence, int32_t endSequence, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (4 of 96) {#begindeletemessages_4}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(int32_t startSequence, int32_t endSequence, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (5 of 96) {#begindeletemessages_5}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(int32_t startSequence, int32_t endSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (6 of 96) {#begindeletemessages_6}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(int32_t startSequence, int32_t endSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (7 of 96) {#begindeletemessages_7}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |

---

## BeginDeleteMessages (8 of 96) {#begindeletemessages_8}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginDeleteMessages (9 of 96) {#begindeletemessages_9}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (10 of 96) {#begindeletemessages_10}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (11 of 96) {#begindeletemessages_11}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (12 of 96) {#begindeletemessages_12}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (13 of 96) {#begindeletemessages_13}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |

---

## BeginDeleteMessages (14 of 96) {#begindeletemessages_14}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginDeleteMessages (15 of 96) {#begindeletemessages_15}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (16 of 96) {#begindeletemessages_16}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (17 of 96) {#begindeletemessages_17}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (18 of 96) {#begindeletemessages_18}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (19 of 96) {#begindeletemessages_19}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo for deletion |

---

## BeginDeleteMessages (20 of 96) {#begindeletemessages_20}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## BeginDeleteMessages (21 of 96) {#begindeletemessages_21}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, bool commitNow, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (22 of 96) {#begindeletemessages_22}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, bool commitNow, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (23 of 96) {#begindeletemessages_23}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginDeleteMessages (24 of 96) {#begindeletemessages_24}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, int64_t modificationSequence, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## BeginDeleteMessages (25 of 96) {#begindeletemessages_25}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, int64_t modificationSequence, bool commitNow, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (26 of 96) {#begindeletemessages_26}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, int64_t modificationSequence, bool commitNow, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (27 of 96) {#begindeletemessages_27}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (28 of 96) {#begindeletemessages_28}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (29 of 96) {#begindeletemessages_29}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (30 of 96) {#begindeletemessages_30}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (31 of 96) {#begindeletemessages_31}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |

---

## BeginDeleteMessages (32 of 96) {#begindeletemessages_32}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## BeginDeleteMessages (33 of 96) {#begindeletemessages_33}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, bool commitNow, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (34 of 96) {#begindeletemessages_34}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, bool commitNow, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (35 of 96) {#begindeletemessages_35}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginDeleteMessages (36 of 96) {#begindeletemessages_36}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, int64_t modificationSequence, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## BeginDeleteMessages (37 of 96) {#begindeletemessages_37}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, int64_t modificationSequence, bool commitNow, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (38 of 96) {#begindeletemessages_38}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, int64_t modificationSequence, bool commitNow, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (39 of 96) {#begindeletemessages_39}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (40 of 96) {#begindeletemessages_40}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (41 of 96) {#begindeletemessages_41}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (42 of 96) {#begindeletemessages_42}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (43 of 96) {#begindeletemessages_43}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |

---

## BeginDeleteMessages (44 of 96) {#begindeletemessages_44}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## BeginDeleteMessages (45 of 96) {#begindeletemessages_45}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, bool commitNow, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (46 of 96) {#begindeletemessages_46}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, bool commitNow, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (47 of 96) {#begindeletemessages_47}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginDeleteMessages (48 of 96) {#begindeletemessages_48}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, int64_t modificationSequence, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## BeginDeleteMessages (49 of 96) {#begindeletemessages_49}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, int64_t modificationSequence, bool commitNow, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (50 of 96) {#begindeletemessages_50}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, int64_t modificationSequence, bool commitNow, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (51 of 96) {#begindeletemessages_51}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (52 of 96) {#begindeletemessages_52}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (53 of 96) {#begindeletemessages_53}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (54 of 96) {#begindeletemessages_54}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (55 of 96) {#begindeletemessages_55}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |

---

## BeginDeleteMessages (56 of 96) {#begindeletemessages_56}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginDeleteMessages (57 of 96) {#begindeletemessages_57}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (58 of 96) {#begindeletemessages_58}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (59 of 96) {#begindeletemessages_59}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (60 of 96) {#begindeletemessages_60}

Marks a message with the specified sequence number as deleted asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (61 of 96) {#begindeletemessages_61}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo for deletion |

---

## BeginDeleteMessages (62 of 96) {#begindeletemessages_62}

Begins an asynchronous messages deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## BeginDeleteMessages (63 of 96) {#begindeletemessages_63}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, bool commitNow, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (64 of 96) {#begindeletemessages_64}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, bool commitNow, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (65 of 96) {#begindeletemessages_65}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginDeleteMessages (66 of 96) {#begindeletemessages_66}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, int64_t modificationSequence, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## BeginDeleteMessages (67 of 96) {#begindeletemessages_67}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, int64_t modificationSequence, bool commitNow, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (68 of 96) {#begindeletemessages_68}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, int64_t modificationSequence, bool commitNow, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (69 of 96) {#begindeletemessages_69}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (70 of 96) {#begindeletemessages_70}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (71 of 96) {#begindeletemessages_71}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (72 of 96) {#begindeletemessages_72}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (73 of 96) {#begindeletemessages_73}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |

---

## BeginDeleteMessages (74 of 96) {#begindeletemessages_74}

Begins an asynchronous messages deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## BeginDeleteMessages (75 of 96) {#begindeletemessages_75}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, bool commitNow, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (76 of 96) {#begindeletemessages_76}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, bool commitNow, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (77 of 96) {#begindeletemessages_77}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginDeleteMessages (78 of 96) {#begindeletemessages_78}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, int64_t modificationSequence, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## BeginDeleteMessages (79 of 96) {#begindeletemessages_79}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, int64_t modificationSequence, bool commitNow, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (80 of 96) {#begindeletemessages_80}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, int64_t modificationSequence, bool commitNow, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (81 of 96) {#begindeletemessages_81}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (82 of 96) {#begindeletemessages_82}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (83 of 96) {#begindeletemessages_83}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (84 of 96) {#begindeletemessages_84}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (85 of 96) {#begindeletemessages_85}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::String startUid, System::String endUid)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |

---

## BeginDeleteMessages (86 of 96) {#begindeletemessages_86}

Begins an asynchronous messages deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::String startUid, System::String endUid, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## BeginDeleteMessages (87 of 96) {#begindeletemessages_87}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::String startUid, System::String endUid, bool commitNow, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (88 of 96) {#begindeletemessages_88}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::String startUid, System::String endUid, bool commitNow, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (89 of 96) {#begindeletemessages_89}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::String startUid, System::String endUid, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## BeginDeleteMessages (90 of 96) {#begindeletemessages_90}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::String startUid, System::String endUid, int64_t modificationSequence, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## BeginDeleteMessages (91 of 96) {#begindeletemessages_91}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::String startUid, System::String endUid, int64_t modificationSequence, bool commitNow, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (92 of 96) {#begindeletemessages_92}

Begins an asynchronous message deletion. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::String startUid, System::String endUid, int64_t modificationSequence, bool commitNow, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (93 of 96) {#begindeletemessages_93}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::String startUid, System::String endUid, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (94 of 96) {#begindeletemessages_94}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::String startUid, System::String endUid, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginDeleteMessages (95 of 96) {#begindeletemessages_95}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::String startUid, System::String endUid, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginDeleteMessages (96 of 96) {#begindeletemessages_96}

Begins an asynchronous message deletion.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginDeleteMessages(System::String startUid, System::String endUid, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

