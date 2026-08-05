---
title: "Aspose::Email::Clients::Imap::ImapClient::ListMessage method"
linktitle: "ListMessage"
articleTitle: "ListMessage"
second_title: "Aspose.Email for C++"
description: "Gets information about a message."
type: docs
weight: 1580
url: /cpp/aspose.email.clients.imap/imapclient/listmessage/
---

## ListMessage (1 of 8) {#listmessage_1}

Gets information about a message.

**Returns:** Returns ImapMessageInfo objects

```cpp
ListMessage(int32_t sequenceNumber)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |

---

## ListMessage (2 of 8) {#listmessage_2}

Gets information about a message.

**Returns:** Returns ImapMessageInfo objects

```cpp
ListMessage(int32_t sequenceNumber, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> messageExtraFields)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |
| messageExtraFields | List of extra parameters for a message wich will be requested. |

---

## ListMessage (3 of 8) {#listmessage_3}

Gets information about a message.

**Returns:** Returns ImapMessageInfo objects

```cpp
ListMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |

---

## ListMessage (4 of 8) {#listmessage_4}

Gets information about a message.

**Returns:** Returns ImapMessageInfo objects

```cpp
ListMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> messageExtraFields)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |
| messageExtraFields | List of extra parameters for a message wich will be requested. |

---

## ListMessage (5 of 8) {#listmessage_5}

Gets information about a message.

**Returns:** Returns ImapMessageInfo objects

```cpp
ListMessage(System::SharedPtr < IConnection > connection, System::String uniqueId)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The unique Id of the message |

---

## ListMessage (6 of 8) {#listmessage_6}

Gets information about a message.

**Returns:** Returns ImapMessageInfo objects

```cpp
ListMessage(System::SharedPtr < IConnection > connection, System::String uniqueId, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> messageExtraFields)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The unique Id of the message |
| messageExtraFields | List of extra parameters for a message wich will be requested. |

---

## ListMessage (7 of 8) {#listmessage_7}

Gets information about a message.

**Returns:** Returns ImapMessageInfo objects

```cpp
ListMessage(System::String uniqueId)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The unique Id of the message |

---

## ListMessage (8 of 8) {#listmessage_8}

Gets information about a message.

**Returns:** Returns ImapMessageInfo objects

```cpp
ListMessage(System::String uniqueId, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> messageExtraFields)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The unique Id of the message |
| messageExtraFields | List of extra parameters for a message wich will be requested. |

