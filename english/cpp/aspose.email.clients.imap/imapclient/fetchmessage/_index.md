---
title: "Aspose::Email::Clients::Imap::ImapClient::FetchMessage method"
linktitle: "FetchMessage"
articleTitle: "FetchMessage"
second_title: "Aspose.Email for C++"
description: "Fetches the message"
type: docs
weight: 1120
url: /cpp/aspose.email.clients.imap/imapclient/fetchmessage/
---

## FetchMessage (1 of 6) {#fetchmessage_1}

Fetches the message

**Returns:** MailMessage that represents e-mail message

```cpp
FetchMessage(int32_t sequenceNumber)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |

---

## FetchMessage (2 of 6) {#fetchmessage_2}

Fetches the message

**Returns:** MailMessage that represents e-mail message

```cpp
FetchMessage(int32_t sequenceNumber, bool ignoreAttachment)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of message |
| ignoreAttachment | A value that defines whether the attachments should not be loaded. If it is set to true , then only message headers, message body and attachment information are fetched. Attachment content is not loaded |

---

## FetchMessage (3 of 6) {#fetchmessage_3}

Fetches the message

**Returns:** MailMessage that represents e-mail message

```cpp
FetchMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |

---

## FetchMessage (4 of 6) {#fetchmessage_4}

Fetches the message

**Returns:** MailMessage that represents e-mail message

```cpp
FetchMessage(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, bool ignoreAttachment)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of message |
| ignoreAttachment | A value that defines whether the attachments should not be loaded. If it is set to true , then only message headers, message body and attachment information are fetched. Attachment content is not loaded |

---

## FetchMessage (5 of 6) {#fetchmessage_5}

Fetches the message

**Returns:** MailMessage that represents e-mail message

```cpp
FetchMessage(System::SharedPtr < IConnection > connection, System::String uniqueId)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The unique id of message |

---

## FetchMessage (6 of 6) {#fetchmessage_6}

Fetches the message

**Returns:** MailMessage that represents e-mail message

```cpp
FetchMessage(System::String uniqueId)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The unique id of message |

