---
title: "Aspose::Email::Clients::Imap::ImapClient::DeleteMessage method"
linktitle: "DeleteMessage"
articleTitle: "DeleteMessage"
second_title: "Aspose.Email for C++"
description: "Marks a message with the specified sequence number as deleted"
type: docs
weight: 600
url: /cpp/aspose.email.clients.imap/imapclient/deletemessage/
---

## DeleteMessage (1 of 12) {#deletemessage_1}

Marks a message with the specified sequence number as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessage(int32_t sequenceNumber)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | Sequence number of a message |

---

## DeleteMessage (2 of 12) {#deletemessage_2}

Marks a message with the specified sequence number as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessage(int32_t sequenceNumber, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | Sequence number of a message |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## DeleteMessage (3 of 12) {#deletemessage_3}

Marks a message with the specified sequence number as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | Sequence number of a message |

---

## DeleteMessage (4 of 12) {#deletemessage_4}

Marks a message with the specified sequence number as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | Sequence number of a message |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## DeleteMessage (5 of 12) {#deletemessage_5}

Marks a message with the specified sequence number as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessage(System::SharedPtr < IConnection > connection, System::String uniqueId)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The uid of the message |

---

## DeleteMessage (6 of 12) {#deletemessage_6}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessage(System::SharedPtr < IConnection > connection, System::String uniqueId, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The uid of the message |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## DeleteMessage (7 of 12) {#deletemessage_7}

Marks a message with the specified unique identifier as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessage(System::SharedPtr < IConnection > connection, System::String uniqueId, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The uid of the message |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## DeleteMessage (8 of 12) {#deletemessage_8}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessage(System::SharedPtr < IConnection > connection, System::String uniqueId, int64_t modificationSequence, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The uid of the message |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## DeleteMessage (9 of 12) {#deletemessage_9}

Marks a message with the specified sequence number as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessage(System::String uniqueId)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The uid of the message |

---

## DeleteMessage (10 of 12) {#deletemessage_10}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessage(System::String uniqueId, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The uid of the message |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

---

## DeleteMessage (11 of 12) {#deletemessage_11}

Marks a message with the specified unique identifier as deleted

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessage(System::String uniqueId, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The uid of the message |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |

---

## DeleteMessage (12 of 12) {#deletemessage_12}

Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
DeleteMessage(System::String uniqueId, int64_t modificationSequence, bool commitNow)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The uid of the message |
| modificationSequence | Modification sequence. Please, read more https://tools.ietf.org/html/rfc7162 |
| commitNow | Defines whether message must be commited now. Please, read more https://tools.ietf.org/html/rfc4315 |

