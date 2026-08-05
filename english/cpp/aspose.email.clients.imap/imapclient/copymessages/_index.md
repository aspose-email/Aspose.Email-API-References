---
title: "Aspose::Email::Clients::Imap::ImapClient::CopyMessages method"
linktitle: "CopyMessages"
articleTitle: "CopyMessages"
second_title: "Aspose.Email for C++"
description: "Copy messages"
type: docs
weight: 570
url: /cpp/aspose.email.clients.imap/imapclient/copymessages/
---

## CopyMessages (1 of 11) {#copymessages_1}

Copy messages

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
CopyMessages(int32_t startSequence, int32_t endSequence, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |

---

## CopyMessages (2 of 11) {#copymessages_2}

Copy the messaeg

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
CopyMessages(System::SharedPtr < IConnection > connection, int32_t startSequence, int32_t endSequence, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startSequence | The starting sequence number of a message list |
| endSequence | The ending sequence number of a message list |
| folderName | Folder name where a message is to be moved |

---

## CopyMessages (3 of 11) {#copymessages_3}

Copy the messaeg

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
CopyMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |

---

## CopyMessages (4 of 11) {#copymessages_4}

Copy messages

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
CopyMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |

---

## CopyMessages (5 of 11) {#copymessages_5}

Copy messages

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
CopyMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |

---

## CopyMessages (6 of 11) {#copymessages_6}

Copy messages

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
CopyMessages(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |

---

## CopyMessages (7 of 11) {#copymessages_7}

Copy messages

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
CopyMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |

---

## CopyMessages (8 of 11) {#copymessages_8}

Copy messages

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
CopyMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceSet, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| sequenceSet | The set of sequence numbers for messages |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## CopyMessages (9 of 11) {#copymessages_9}

Copy messages

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
CopyMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ImapMessageInfo >>> messageInfoSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| messageInfoSet | The set of ImapMessageInfo |
| folderName | Folder name where a message is to be moved |

---

## CopyMessages (10 of 11) {#copymessages_10}

Copy messages

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
CopyMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| uidSet | The set of UID for messages |
| folderName | Folder name where a message is to be moved |

---

## CopyMessages (11 of 11) {#copymessages_11}

Copy messages

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
CopyMessages(System::String startUid, System::String endUid, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| folderName | Folder name where a message is to be moved |

