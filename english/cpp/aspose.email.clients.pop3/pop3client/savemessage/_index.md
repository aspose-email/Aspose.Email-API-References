---
title: "Aspose::Email::Clients::Pop3::Pop3Client::SaveMessage method"
linktitle: "SaveMessage"
articleTitle: "SaveMessage"
second_title: "Aspose.Email for C++"
description: "Fetches and save the message as a stream"
type: docs
weight: 560
url: /cpp/aspose.email.clients.pop3/pop3client/savemessage/
---

## SaveMessage (1 of 8) {#savemessage_1}

Fetches and save the message as a stream

**Returns:** void Aspose::Email::Clients::Pop3::

```cpp
SaveMessage(int32_t sequenceNumber, System::SharedPtr < System::IO::Stream > outputStream)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of the message |
| outputStream | Stream where message will be saved |

---

## SaveMessage (2 of 8) {#savemessage_2}

Fetches and save the message into a file

**Returns:** void Aspose::Email::Clients::Pop3::

```cpp
SaveMessage(int32_t sequenceNumber, System::String fileName)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of the message |
| fileName | File name for message |

---

## SaveMessage (3 of 8) {#savemessage_3}

Fetches and save the message as a stream

**Returns:** void Aspose::Email::Clients::Pop3::

```cpp
SaveMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::SharedPtr < System::IO::Stream > outputStream)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of the message |
| outputStream | Stream where message will be saved |

---

## SaveMessage (4 of 8) {#savemessage_4}

Fetches and save the message into a file

**Returns:** void Aspose::Email::Clients::Pop3::

```cpp
SaveMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::String fileName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of the message |
| fileName | File name for message |

---

## SaveMessage (5 of 8) {#savemessage_5}

Fetches and save the message as a stream

**Returns:** void Aspose::Email::Clients::Pop3::

```cpp
SaveMessage(System::SharedPtr < IConnection > connection, System::String uniqueId, System::SharedPtr < System::IO::Stream > outputStream)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The unique Id of the message |
| outputStream | Stream where message will be saved |

---

## SaveMessage (6 of 8) {#savemessage_6}

Fetches and save the message into a file

**Returns:** void Aspose::Email::Clients::Pop3::

```cpp
SaveMessage(System::SharedPtr < IConnection > connection, System::String uniqueId, System::String fileName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The unique Id of the message |
| fileName | File name for message |

---

## SaveMessage (7 of 8) {#savemessage_7}

Fetches and save the message as a stream

**Returns:** void Aspose::Email::Clients::Pop3::

```cpp
SaveMessage(System::String uniqueId, System::SharedPtr < System::IO::Stream > outputStream)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The unique Id of the message |
| outputStream | Stream where message will be saved |

---

## SaveMessage (8 of 8) {#savemessage_8}

Fetches and save the message into a file

**Returns:** void Aspose::Email::Clients::Pop3::

```cpp
SaveMessage(System::String uniqueId, System::String fileName)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The unique Id of the message |
| fileName | File name for message |

