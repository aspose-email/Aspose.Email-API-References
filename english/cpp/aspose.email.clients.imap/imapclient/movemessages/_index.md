---
title: "Aspose::Email::Clients::Imap::ImapClient::MoveMessages method"
linktitle: "MoveMessages"
articleTitle: "MoveMessages"
second_title: "Aspose.Email for C++"
description: "Moves the message"
type: docs
weight: 1650
url: /cpp/aspose.email.clients.imap/imapclient/movemessages/
---

## MoveMessages (1 of 20) {#movemessages_1}

Moves the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
MoveMessages(int32_t startSequence, int32_t endSequence, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |

---

## MoveMessages (2 of 20) {#movemessages_2}

Moves the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
MoveMessages(int32_t startSequence, int32_t endSequence, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## MoveMessages (3 of 20) {#movemessages_3}

Moves the messaeg

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
MoveMessages(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |

---

## MoveMessages (4 of 20) {#movemessages_4}

Moves the messaeg

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
MoveMessages(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## MoveMessages (5 of 20) {#movemessages_5}

Moves the messaeg

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
MoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |

---

## MoveMessages (6 of 20) {#movemessages_6}

Moves the messaeg

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
MoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## MoveMessages (7 of 20) {#movemessages_7}

Moves the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
MoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |

---

## MoveMessages (8 of 20) {#movemessages_8}

Moves the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
MoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## MoveMessages (9 of 20) {#movemessages_9}

Moves the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
MoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |

---

## MoveMessages (10 of 20) {#movemessages_10}

Moves the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
MoveMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## MoveMessages (11 of 20) {#movemessages_11}

Moves the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
MoveMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |

---

## MoveMessages (12 of 20) {#movemessages_12}

Moves the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
MoveMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## MoveMessages (13 of 20) {#movemessages_13}

Moves the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
MoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |

---

## MoveMessages (14 of 20) {#movemessages_14}

Moves the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
MoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## MoveMessages (15 of 20) {#movemessages_15}

Moves the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
MoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |

---

## MoveMessages (16 of 20) {#movemessages_16}

Moves the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
MoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## MoveMessages (17 of 20) {#movemessages_17}

Moves the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
MoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |

---

## MoveMessages (18 of 20) {#movemessages_18}

Moves the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
MoveMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## MoveMessages (19 of 20) {#movemessages_19}

Moves the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
MoveMessages(System::String startUid, System::String endUid, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |

---

## MoveMessages (20 of 20) {#movemessages_20}

Moves the message

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
MoveMessages(System::String startUid, System::String endUid, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

