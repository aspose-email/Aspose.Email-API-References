---
title: "Aspose::Email::Clients::Imap::ImapClient::FetchMessages method"
linktitle: "FetchMessages"
articleTitle: "FetchMessages"
second_title: "Aspose.Email for C++"
description: "Fetches the messages"
type: docs
weight: 1130
url: /cpp/aspose.email.clients.imap/imapclient/fetchmessages/
---

## FetchMessages (1 of 4) {#fetchmessages_1}

Fetches the messages

**Returns:** List of MailMessage objects

```cpp
FetchMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceNumbers)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumbers | The sequence numbers of the messages |

---

## FetchMessages (2 of 4) {#fetchmessages_2}

Fetches the messages

**Returns:** List of MailMessage objects

```cpp
FetchMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uids)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uids | The sequence numbers of the messages |

---

## FetchMessages (3 of 4) {#fetchmessages_3}

Fetches the messages

**Returns:** List of MailMessage objects

```cpp
FetchMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceNumbers)
```

| Parameter | Description |
| --- | --- |
| sequenceNumbers | The sequence numbers of the messages |

---

## FetchMessages (4 of 4) {#fetchmessages_4}

Fetches the messages

**Returns:** List of MailMessage objects

```cpp
FetchMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uids)
```

| Parameter | Description |
| --- | --- |
| uids | The sequence numbers of the messages |

