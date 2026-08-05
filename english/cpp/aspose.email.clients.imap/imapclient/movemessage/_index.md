---
title: "Aspose::Email::Clients::Imap::ImapClient::MoveMessage method"
linktitle: "MoveMessage"
articleTitle: "MoveMessage"
second_title: "Aspose.Email for C++"
description: "Moves the message"
type: docs
weight: 1640
url: /cpp/aspose.email.clients.imap/imapclient/movemessage/
---

## MoveMessage (1 of 8) {#movemessage_1}

Moves the message

**Returns:** System::String Aspose::Email::Clients::Imap::

```cpp
MoveMessage(int32_t sequenceNumber, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of the message |
| folderName | Folder name where a message is to be moved |

---

## MoveMessage (2 of 8) {#movemessage_2}

Moves the message

**Returns:** System::String Aspose::Email::Clients::Imap::

```cpp
MoveMessage(int32_t sequenceNumber, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of the message |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## MoveMessage (3 of 8) {#movemessage_3}

Moves the messaeg

**Returns:** System::String Aspose::Email::Clients::Imap::

```cpp
MoveMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of the message |
| folderName | Folder name where a message is to be moved |

---

## MoveMessage (4 of 8) {#movemessage_4}

Moves the messaeg

**Returns:** System::String Aspose::Email::Clients::Imap::

```cpp
MoveMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of the message |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## MoveMessage (5 of 8) {#movemessage_5}

Moves the message

**Returns:** System::String Aspose::Email::Clients::Imap::

```cpp
MoveMessage(System::SharedPtr < IConnection > connection, System::String uniqueId, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The uid of the message |
| folderName | Folder name where a message is to be moved |

---

## MoveMessage (6 of 8) {#movemessage_6}

Moves the message

**Returns:** System::String Aspose::Email::Clients::Imap::

```cpp
MoveMessage(System::SharedPtr < IConnection > connection, System::String uniqueId, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The uid of the message |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

---

## MoveMessage (7 of 8) {#movemessage_7}

Moves the message

**Returns:** System::String Aspose::Email::Clients::Imap::

```cpp
MoveMessage(System::String uniqueId, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The uid of the message |
| folderName | Folder name where a message is to be moved |

---

## MoveMessage (8 of 8) {#movemessage_8}

Moves the message

**Returns:** System::String Aspose::Email::Clients::Imap::

```cpp
MoveMessage(System::String uniqueId, System::String folderName, bool commitDeletions)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The uid of the message |
| folderName | Folder name where a message is to be moved |
| commitDeletions | Specifies whether deletions should be committed. |

