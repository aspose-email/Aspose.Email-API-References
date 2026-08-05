---
title: "Aspose::Email::Clients::Imap::ImapClient::CopyMessage method"
linktitle: "CopyMessage"
articleTitle: "CopyMessage"
second_title: "Aspose.Email for C++"
description: "Copies the message"
type: docs
weight: 560
url: /cpp/aspose.email.clients.imap/imapclient/copymessage/
---

## CopyMessage (1 of 4) {#copymessage_1}

Copies the message

**Returns:** If server supports UIDPLUS extension returns unique id of the copied message, otherwise returns null Please, read more https://tools.ietf.org/html/rfc4315

```cpp
CopyMessage(int32_t sequenceNumber, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of the message |
| folderName | Folder name where a message is to be copied |

---

## CopyMessage (2 of 4) {#copymessage_2}

Copies the message

**Returns:** If server supports UIDPLUS extension returns unique id of the copied message, otherwise returns null Please, read more https://tools.ietf.org/html/rfc4315

```cpp
CopyMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of the message |
| folderName | Folder name where a message is to be copied |

---

## CopyMessage (3 of 4) {#copymessage_3}

Copies the message

**Returns:** If server supports UIDPLUS extension returns unique id of the copied message, otherwise returns null Please, read more https://tools.ietf.org/html/rfc4315

```cpp
CopyMessage(System::SharedPtr < IConnection > connection, System::String uniqueId, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The uid of the message |
| folderName | Folder name where a message is to be copied |

---

## CopyMessage (4 of 4) {#copymessage_4}

Copies the message

**Returns:** If server supports UIDPLUS extension returns unique id of the copied message, otherwise returns null Please, read more https://tools.ietf.org/html/rfc4315

```cpp
CopyMessage(System::String uniqueId, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The uid of the message |
| folderName | Folder name where a message is to be copied |

