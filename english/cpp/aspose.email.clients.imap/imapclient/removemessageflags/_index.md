---
title: "Aspose::Email::Clients::Imap::ImapClient::RemoveMessageFlags method"
linktitle: "RemoveMessageFlags"
articleTitle: "RemoveMessageFlags"
second_title: "Aspose.Email for C++"
description: "Removes the flags of the message"
type: docs
weight: 1680
url: /cpp/aspose.email.clients.imap/imapclient/removemessageflags/
---

## RemoveMessageFlags (1 of 28) {#removemessageflags_1}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of the message |
| flags | The flags to be added |

---

## RemoveMessageFlags (2 of 28) {#removemessageflags_2}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of the message |
| flags | The flags to be added |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## RemoveMessageFlags (3 of 28) {#removemessageflags_3}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | The flags to be removed |

---

## RemoveMessageFlags (4 of 28) {#removemessageflags_4}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | The flags to be removed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## RemoveMessageFlags (5 of 28) {#removemessageflags_5}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of the message |
| flags | The flags to be added |

---

## RemoveMessageFlags (6 of 28) {#removemessageflags_6}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of the message |
| flags | The flags to be added |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## RemoveMessageFlags (7 of 28) {#removemessageflags_7}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | The flags to be removed |

---

## RemoveMessageFlags (8 of 28) {#removemessageflags_8}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| flags | The flags to be removed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## RemoveMessageFlags (9 of 28) {#removemessageflags_9}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| flags | The flags to be removed |

---

## RemoveMessageFlags (10 of 28) {#removemessageflags_10}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| flags | The flags to be removed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## RemoveMessageFlags (11 of 28) {#removemessageflags_11}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| flags | The flags to be changed |

---

## RemoveMessageFlags (12 of 28) {#removemessageflags_12}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| flags | The flags to be changed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## RemoveMessageFlags (13 of 28) {#removemessageflags_13}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| flags | The flags to be changed |

---

## RemoveMessageFlags (14 of 28) {#removemessageflags_14}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of set of UID for messages |
| flags | The flags to be changed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## RemoveMessageFlags (15 of 28) {#removemessageflags_15}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | The flags to be changed |

---

## RemoveMessageFlags (16 of 28) {#removemessageflags_16}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | The flags to be changed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## RemoveMessageFlags (17 of 28) {#removemessageflags_17}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::SharedPtr < IConnection > connection, System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | Unique identifier of a message |
| flags | The flags to be added |

---

## RemoveMessageFlags (18 of 28) {#removemessageflags_18}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::SharedPtr < IConnection > connection, System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | Unique identifier of a message |
| flags | The flags to be added |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## RemoveMessageFlags (19 of 28) {#removemessageflags_19}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| flags | The flags to be removed |

---

## RemoveMessageFlags (20 of 28) {#removemessageflags_20}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| flags | The flags to be removed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## RemoveMessageFlags (21 of 28) {#removemessageflags_21}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| flags | The flags to be changed |

---

## RemoveMessageFlags (22 of 28) {#removemessageflags_22}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| flags | The flags to be changed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## RemoveMessageFlags (23 of 28) {#removemessageflags_23}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| flags | The flags to be changed |

---

## RemoveMessageFlags (24 of 28) {#removemessageflags_24}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| flags | The flags to be changed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## RemoveMessageFlags (25 of 28) {#removemessageflags_25}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | The flags to be changed |

---

## RemoveMessageFlags (26 of 28) {#removemessageflags_26}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::String startUid, System::String endUid, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| flags | The flags to be changed |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## RemoveMessageFlags (27 of 28) {#removemessageflags_27}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags)
```

| Parameter | Description |
| --- | --- |
| uniqueId | Unique identifier of a message |
| flags | The flags to be added |

---

## RemoveMessageFlags (28 of 28) {#removemessageflags_28}

Removes the flags of the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
RemoveMessageFlags(System::String uniqueId, System::SharedPtr < ImapMessageFlags > flags, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| uniqueId | Unique identifier of a message |
| flags | The flags to be added |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

