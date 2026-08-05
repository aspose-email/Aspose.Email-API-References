---
title: "Aspose::Email::Clients::Pop3::Pop3Client::FetchMessage method"
linktitle: "FetchMessage"
articleTitle: "FetchMessage"
second_title: "Aspose.Email for C++"
description: "Fetches the message"
type: docs
weight: 400
url: /cpp/aspose.email.clients.pop3/pop3client/fetchmessage/
---

## FetchMessage (1 of 4) {#fetchmessage_1}

Fetches the message

**Returns:** MailMessage that represents e-mail message

```cpp
FetchMessage(int32_t sequenceNumber)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of the message |

---

## FetchMessage (2 of 4) {#fetchmessage_2}

Fetches the message

**Returns:** MailMessage that represents e-mail message

```cpp
FetchMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of the message |

---

## FetchMessage (3 of 4) {#fetchmessage_3}

Fetches the message

**Returns:** MailMessage that represents e-mail message

```cpp
FetchMessage(System::SharedPtr < IConnection > connection, System::String uniqueId)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The unique id of the message |

---

## FetchMessage (4 of 4) {#fetchmessage_4}

Fetches the message

**Returns:** MailMessage that represents e-mail message

```cpp
FetchMessage(System::String uniqueId)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The unique id of the message |

