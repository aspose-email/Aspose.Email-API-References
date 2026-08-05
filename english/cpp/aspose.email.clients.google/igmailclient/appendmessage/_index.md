---
title: "Aspose::Email::Clients::Google::IGmailClient::AppendMessage method"
linktitle: "AppendMessage"
articleTitle: "AppendMessage"
second_title: "Aspose.Email for C++"
description: "Directly appends a message into INBOX similar to IMAP APPEND, bypassing most scanning and classification."
type: docs
weight: 10
url: /cpp/aspose.email.clients.google/igmailclient/appendmessage/
---

## AppendMessage (1 of 2) {#appendmessage_1}

Directly appends a message into INBOX similar to IMAP APPEND, bypassing most scanning and classification. Does not send a message.

**Returns:** The Id of appended message.

```cpp
AppendMessage(System::SharedPtr < MailMessage > msg)
```

| Parameter | Description |
| --- | --- |
| msg | MailMerssage that will be appended. |

---

## AppendMessage (2 of 2) {#appendmessage_2}

Directly appends a message into only this user's mailbox similar to IMAP APPEND, bypassing most scanning and classification. Does not send a message.

**Returns:** The Id of appended message.

```cpp
AppendMessage(System::SharedPtr < MailMessage > msg, System::String labelName)
```

| Parameter | Description |
| --- | --- |
| msg | MailMerssage that will be appended. |
| labelName | The name of Label that will be appplied to appended message.If name null or empty then label INBOX will be applied. |

