---
title: "Aspose::Email::Clients::Imap::ImapClient::FetchAttachment method"
linktitle: "FetchAttachment"
articleTitle: "FetchAttachment"
second_title: "Aspose.Email for C++"
description: "Fetches the specified attachment"
type: docs
weight: 1110
url: /cpp/aspose.email.clients.imap/imapclient/fetchattachment/
---

## FetchAttachment (1 of 2) {#fetchattachment_1}

Fetches the specified attachment

**Returns:** Attachment that represents attachment

```cpp
FetchAttachment(int32_t sequenceNumber, System::String attachmentName)
```

| Parameter | Description |
| --- | --- |
| sequenceNumber | The sequence number of a message |
| attachmentName | A name of attachment |

---

## FetchAttachment (2 of 2) {#fetchattachment_2}

Fetches the specified attachment

**Returns:** Attachment that represents attachment

```cpp
FetchAttachment(System::SharedPtr < IConnection > connection, int32_t sequenceNumber, System::String attachmentName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumber | The sequence number of a message |
| attachmentName | A name of attachment |

