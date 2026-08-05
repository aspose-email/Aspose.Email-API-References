---
title: "Aspose::Email::Clients::Imap::ImapClient::ChangeMessageFlags method"
linktitle: "ChangeMessageFlags"
articleTitle: "ChangeMessageFlags"
second_title: "Aspose.Email for C++"
description: "Changes the flags of the message"
type: docs
weight: 520
url: /cpp/aspose.email.clients.imap/imapclient/changemessageflags/
---

## ChangeMessageFlags (1 of 28) {#changemessageflags_1}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of the message |
| flags | The flags to be removed |

---

## ChangeMessageFlags (2 of 28) {#changemessageflags_2}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of the message |
| flags | The flags to be removed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## ChangeMessageFlags (3 of 28) {#changemessageflags_3}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | The flags to be removed |

---

## ChangeMessageFlags (4 of 28) {#changemessageflags_4}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | The flags to be removed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## ChangeMessageFlags (5 of 28) {#changemessageflags_5}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of the message |
| flags | The flags to be removed |

---

## ChangeMessageFlags (6 of 28) {#changemessageflags_6}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of the message |
| flags | The flags to be removed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## ChangeMessageFlags (7 of 28) {#changemessageflags_7}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | The flags to be removed |

---

## ChangeMessageFlags (8 of 28) {#changemessageflags_8}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | The flags to be removed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## ChangeMessageFlags (9 of 28) {#changemessageflags_9}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| flags | The flags to be removed |

---

## ChangeMessageFlags (10 of 28) {#changemessageflags_10}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| flags | The flags to be removed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## ChangeMessageFlags (11 of 28) {#changemessageflags_11}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| flags | The flags to be changed |

---

## ChangeMessageFlags (12 of 28) {#changemessageflags_12}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| flags | The flags to be changed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## ChangeMessageFlags (13 of 28) {#changemessageflags_13}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| flags | The flags to be changed |

---

## ChangeMessageFlags (14 of 28) {#changemessageflags_14}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| flags | The flags to be changed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## ChangeMessageFlags (15 of 28) {#changemessageflags_15}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | The flags to be changed |

---

## ChangeMessageFlags (16 of 28) {#changemessageflags_16}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | The flags to be changed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## ChangeMessageFlags (17 of 28) {#changemessageflags_17}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::SharedPtr < IConnection > connection, System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The uid of the message |
| flags | The flags to be changed |

---

## ChangeMessageFlags (18 of 28) {#changemessageflags_18}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::SharedPtr < IConnection > connection, System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The uid of the message |
| flags | The flags to be changed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## ChangeMessageFlags (19 of 28) {#changemessageflags_19}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| flags | The flags to be removed |

---

## ChangeMessageFlags (20 of 28) {#changemessageflags_20}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| flags | The flags to be removed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## ChangeMessageFlags (21 of 28) {#changemessageflags_21}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| flags | The flags to be changed |

---

## ChangeMessageFlags (22 of 28) {#changemessageflags_22}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| flags | The flags to be changed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## ChangeMessageFlags (23 of 28) {#changemessageflags_23}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| flags | The flags to be changed |

---

## ChangeMessageFlags (24 of 28) {#changemessageflags_24}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| flags | The flags to be changed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## ChangeMessageFlags (25 of 28) {#changemessageflags_25}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | The flags to be changed |

---

## ChangeMessageFlags (26 of 28) {#changemessageflags_26}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | The flags to be changed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## ChangeMessageFlags (27 of 28) {#changemessageflags_27}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The uid of the message |
| flags | The flags to be changed |

---

## ChangeMessageFlags (28 of 28) {#changemessageflags_28}

Changes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
ChangeMessageFlags(System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The uid of the message |
| flags | The flags to be changed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

