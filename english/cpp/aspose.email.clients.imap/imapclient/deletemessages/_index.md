---
title: "Aspose::Email::Clients::Imap::ImapClient::DeleteMessages method"
linktitle: "DeleteMessages"
articleTitle: "DeleteMessages"
second_title: "Aspose.Email for C++"
description: "Marks a message with the specified sequence number as deleted"
type: docs
weight: 610
url: /cpp/aspose.email.clients.imap/imapclient/deletemessages/
---

## DeleteMessages (1 of 32) {#deletemessages_1}

Marks a message with the specified sequence number as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(int32_t startSequence, int32_t endSequence)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |

---

## DeleteMessages (2 of 32) {#deletemessages_2}

Marks a message with the specified sequence number as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(int32_t startSequence, int32_t endSequence, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## DeleteMessages (3 of 32) {#deletemessages_3}

Marks a message with the specified sequence number as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |

---

## DeleteMessages (4 of 32) {#deletemessages_4}

Marks a message with the specified sequence number as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## DeleteMessages (5 of 32) {#deletemessages_5}

Marks a message with the specified sequence number as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |

---

## DeleteMessages (6 of 32) {#deletemessages_6}

Marks a message with the specified sequence number as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## DeleteMessages (7 of 32) {#deletemessages_7}

Marks a message with the specified sequence number as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo for deletion |

---

## DeleteMessages (8 of 32) {#deletemessages_8}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## DeleteMessages (9 of 32) {#deletemessages_9}

Marks a message with the specified unique identifier as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## DeleteMessages (10 of 32) {#deletemessages_10}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, int64_t modificationSequence, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## DeleteMessages (11 of 32) {#deletemessages_11}

Marks a message with the specified sequence number as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |

---

## DeleteMessages (12 of 32) {#deletemessages_12}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## DeleteMessages (13 of 32) {#deletemessages_13}

Marks a message with the specified unique identifier as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## DeleteMessages (14 of 32) {#deletemessages_14}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, int64_t modificationSequence, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## DeleteMessages (15 of 32) {#deletemessages_15}

Marks a message with the specified sequence number as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |

---

## DeleteMessages (16 of 32) {#deletemessages_16}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## DeleteMessages (17 of 32) {#deletemessages_17}

Marks a message with the specified unique identifier as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## DeleteMessages (18 of 32) {#deletemessages_18}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, int64_t modificationSequence, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## DeleteMessages (19 of 32) {#deletemessages_19}

Marks a message with the specified sequence number as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |

---

## DeleteMessages (20 of 32) {#deletemessages_20}

Marks a message with the specified sequence number as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## DeleteMessages (21 of 32) {#deletemessages_21}

Marks a message with the specified sequence number as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo for deletion |

---

## DeleteMessages (22 of 32) {#deletemessages_22}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## DeleteMessages (23 of 32) {#deletemessages_23}

Marks a message with the specified unique identifier as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## DeleteMessages (24 of 32) {#deletemessages_24}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, int64_t modificationSequence, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo for deletion |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## DeleteMessages (25 of 32) {#deletemessages_25}

Marks a message with the specified sequence number as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |

---

## DeleteMessages (26 of 32) {#deletemessages_26}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## DeleteMessages (27 of 32) {#deletemessages_27}

Marks a message with the specified unique identifier as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## DeleteMessages (28 of 32) {#deletemessages_28}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, int64_t modificationSequence, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## DeleteMessages (29 of 32) {#deletemessages_29}

Marks a message with the specified sequence number as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::String startUid, System::String endUid)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |

---

## DeleteMessages (30 of 32) {#deletemessages_30}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::String startUid, System::String endUid, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## DeleteMessages (31 of 32) {#deletemessages_31}

Marks a message with the specified unique identifier as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::String startUid, System::String endUid, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## DeleteMessages (32 of 32) {#deletemessages_32}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessages(System::String startUid, System::String endUid, int64_t modificationSequence, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

