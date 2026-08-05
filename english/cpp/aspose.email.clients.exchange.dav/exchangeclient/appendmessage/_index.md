---
title: "Aspose::Email::Clients::Exchange::Dav::ExchangeClient::AppendMessage method"
linktitle: "AppendMessage"
articleTitle: "AppendMessage"
second_title: "Aspose.Email for C++"
description: "Uploads the mail message to the specified folder"
type: docs
weight: 10
url: /cpp/aspose.email.clients.exchange.dav/exchangeclient/appendmessage/
---

## AppendMessage (1 of 2) {#appendmessage_1}

Uploads the mail message to the specified folder

**Returns:** An uri of created message

```cpp
AppendMessage(System::String folder, System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| folder | A folder to which message is uploaded |
| message | A message to upload |

---

## AppendMessage (2 of 2) {#appendmessage_2}

Uploads the mail message to the specified folder

**Returns:** An uri of created message

```cpp
AppendMessage(System::String folder, System::SharedPtr < MailMessage > message, bool markAsSent)
```

| Parameter | Description |
| --- | --- |
| folder | An uri of folder to which message is uploaded |
| message | A message to upload |
| markAsSent | A value indicating whether the message should be appended as a sent message or a draft. |

