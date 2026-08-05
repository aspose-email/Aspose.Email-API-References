---
title: "Aspose::Email::Clients::Imap::ImapClient::AddMessageFlags method"
linktitle: "AddMessageFlags"
articleTitle: "AddMessageFlags"
second_title: "Aspose.Email for C++"
description: "Adds the flags to the message"
type: docs
weight: 10
url: /cpp/aspose.email.clients.imap/imapclient/addmessageflags/
---

## AddMessageFlags (1 of 28) {#addmessageflags_1}

Adds the flags to the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of the message |
| flags | The flags to be added |

---

## AddMessageFlags (2 of 28) {#addmessageflags_2}

Adds the flags to the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of the message |
| flags | The flags to be added |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## AddMessageFlags (3 of 28) {#addmessageflags_3}

Adds the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | The flags to be removed |

---

## AddMessageFlags (4 of 28) {#addmessageflags_4}

Adds the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | The flags to be removed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## AddMessageFlags (5 of 28) {#addmessageflags_5}

Adds the flags to the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of the message |
| flags | The flags to be added |

---

## AddMessageFlags (6 of 28) {#addmessageflags_6}

Adds the flags to the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of the message |
| flags | The flags to be added |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## AddMessageFlags (7 of 28) {#addmessageflags_7}

Adds the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | The flags to be removed |

---

## AddMessageFlags (8 of 28) {#addmessageflags_8}

Adds the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | The flags to be removed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## AddMessageFlags (9 of 28) {#addmessageflags_9}

Adds the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| flags | The flags to be removed |

---

## AddMessageFlags (10 of 28) {#addmessageflags_10}

Adds the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| flags | The flags to be removed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## AddMessageFlags (11 of 28) {#addmessageflags_11}

Adds the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| flags | The flags to be changed |

---

## AddMessageFlags (12 of 28) {#addmessageflags_12}

Adds the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| flags | The flags to be changed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## AddMessageFlags (13 of 28) {#addmessageflags_13}

Adds the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| flags | The flags to be changed |

---

## AddMessageFlags (14 of 28) {#addmessageflags_14}

Adds the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| flags | The flags to be changed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## AddMessageFlags (15 of 28) {#addmessageflags_15}

Adds the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | The flags to be changed |

---

## AddMessageFlags (16 of 28) {#addmessageflags_16}

Adds the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | The flags to be changed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## AddMessageFlags (17 of 28) {#addmessageflags_17}

Adds the flags to the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::SharedPtr < IConnection > connection, System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | Unique identifier of a message |
| flags | The flags to be added |

---

## AddMessageFlags (18 of 28) {#addmessageflags_18}

Adds the flags to the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::SharedPtr < IConnection > connection, System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | Unique identifier of a message |
| flags | The flags to be added |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## AddMessageFlags (19 of 28) {#addmessageflags_19}

Adds the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| flags | The flags to be removed |

---

## AddMessageFlags (20 of 28) {#addmessageflags_20}

Adds the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| flags | The flags to be removed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## AddMessageFlags (21 of 28) {#addmessageflags_21}

Adds the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| flags | The flags to be changed |

---

## AddMessageFlags (22 of 28) {#addmessageflags_22}

Adds the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| flags | The flags to be changed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## AddMessageFlags (23 of 28) {#addmessageflags_23}

Adds the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| flags | The flags to be changed |

---

## AddMessageFlags (24 of 28) {#addmessageflags_24}

Adds the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| flags | The flags to be changed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## AddMessageFlags (25 of 28) {#addmessageflags_25}

Adds the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | The flags to be changed |

---

## AddMessageFlags (26 of 28) {#addmessageflags_26}

Adds the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | The flags to be changed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## AddMessageFlags (27 of 28) {#addmessageflags_27}

Adds the flags to the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| uniqueId | Unique identifier of a message |
| flags | The flags to be added |

---

## AddMessageFlags (28 of 28) {#addmessageflags_28}

Adds the flags to the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
AddMessageFlags(System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| uniqueId | Unique identifier of a message |
| flags | The flags to be added |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

