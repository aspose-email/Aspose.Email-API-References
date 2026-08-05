---
title: "Aspose::Email::Clients::Imap::ImapClient::SaveMessage method"
linktitle: "SaveMessage"
articleTitle: "SaveMessage"
second_title: "Aspose.Email for C++"
description: "Downloads the message with the specified sequence number and writes its data into a supplied stream"
type: docs
weight: 1730
url: /cpp/aspose.email.clients.imap/imapclient/savemessage/
---

## SaveMessage (1 of 8) {#savemessage_1}

Downloads the message with the specified sequence number and writes its data into a supplied stream

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
SaveMessage(int32_t sequenceNumber, System::SharedPtr < System::IO::Stream > resultStream)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of the message |
| resultStream | Stream that will receive the message |

---

## SaveMessage (2 of 8) {#savemessage_2}

Downloads the message with the specified sequence number and writes its data into a local file

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
SaveMessage(int32_t sequenceNumber, System::String fileName)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of the message |
| fileName | The path of the local file. This cannot be a directory |

---

## SaveMessage (3 of 8) {#savemessage_3}

Downloads the message with the specified sequence number and writes its data into a supplied stream

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
SaveMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::SharedPtr < System::IO::Stream > resultStream)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of the message |
| resultStream | Stream that will receive the message |

---

## SaveMessage (4 of 8) {#savemessage_4}

Downloads the message with the specified sequence number and writes its data into a local file

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
SaveMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::String fileName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of the message |
| fileName | The path of the local file. This cannot be a directory |

---

## SaveMessage (5 of 8) {#savemessage_5}

Downloads the message with the specified sequence number and writes its data into a supplied stream

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
SaveMessage(System::SharedPtr < IConnection > connection, System::String uniqueId, System::SharedPtr < System::IO::Stream > resultStream)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The unique Id of the message |
| resultStream | Stream that will receive the message |

---

## SaveMessage (6 of 8) {#savemessage_6}

Downloads the message with the specified sequence number and writes its data into a local file

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
SaveMessage(System::SharedPtr < IConnection > connection, System::String uniqueId, System::String fileName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The unique Id of the message |
| fileName | The path of the local file. This cannot be a directory |

---

## SaveMessage (7 of 8) {#savemessage_7}

Downloads the message with the specified sequence number and writes its data into a supplied stream

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
SaveMessage(System::String uniqueId, System::SharedPtr < System::IO::Stream > resultStream)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The unique Id of the message |
| resultStream | Stream that will receive the message |

---

## SaveMessage (8 of 8) {#savemessage_8}

Downloads the message with the specified sequence number and writes its data into a local file

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
SaveMessage(System::String uniqueId, System::String fileName)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The unique Id of the message |
| fileName | The path of the local file. This cannot be a directory |

