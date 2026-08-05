---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::AppendMessage method"
linktitle: "AppendMessage"
articleTitle: "AppendMessage"
second_title: "Aspose.Email for C++"
description: "Uploads the mail message to the Inbox folder"
type: docs
weight: 30
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/appendmessage/
---

## AppendMessage (1 of 5) {#appendmessage_1}

Uploads the mail message to the Inbox folder

**Returns:** An uri of created message

```cpp
AppendMessage(System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| message | A message to upload |

---

## AppendMessage (2 of 5) {#appendmessage_2}

Uploads the mail message to the specified folder

**Returns:** An uri of created message

```cpp
AppendMessage(System::SharedPtr < Mapi::MapiMessage > mapiMessage)
```

| Parameter | Description |
| --- | --- |
| mapiMessage | A message to upload |

---

## AppendMessage (3 of 5) {#appendmessage_3}

Uploads the mail message to the specified folder

**Returns:** An uri of created message

```cpp
AppendMessage(System::SharedPtr < Mapi::MapiMessage > mapiMessage, bool markAsSent)
```

| Parameter | Description |
| --- | --- |
| mapiMessage | A message to upload |
| markAsSent | A value indicating whether the message should be appended as a sent message or a draft. |

---

## AppendMessage (4 of 5) {#appendmessage_4}

Uploads the mail message to the specified folder

**Returns:** An uri of created message

```cpp
AppendMessage(System::String folderUri, System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| folderUri | A folder URI to which message is uploaded. |
| message | A message to upload |

---

## AppendMessage (5 of 5) {#appendmessage_5}

Uploads the mail message to the specified folder

**Returns:** An uri of created message

```cpp
AppendMessage(System::String folderUri, System::SharedPtr < Mapi::MapiMessage > mapiMessage, bool markAsSent)
```

| Parameter | Description |
| --- | --- |
| folderUri | A folder URI to which message is uploaded. |
| mapiMessage | A message to upload |
| markAsSent | A value indicating whether the message should be appended as a sent message or a draft. |

