---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::AppendMessages method"
linktitle: "AppendMessages"
articleTitle: "AppendMessages"
second_title: "Aspose.Email for C++"
description: "Uploads the mail message to the specified folder"
type: docs
weight: 40
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/appendmessages/
---

## AppendMessages (1 of 5) {#appendmessages_1}

Uploads the mail message to the specified folder

**Returns:** List of uri of created messages

```cpp
AppendMessages(const System::ArrayPtr< System::SharedPtr < MailMessage >> & messages)
```

| Parameter | Description |
| --- | --- |
| messages | A messages to upload |

---

## AppendMessages (2 of 5) {#appendmessages_2}

Uploads the mail message to the specified folder

**Returns:** List of uri of created messages

```cpp
AppendMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages)
```

| Parameter | Description |
| --- | --- |
| messages | A messages to upload |

---

## AppendMessages (3 of 5) {#appendmessages_3}

Uploads the mail message to the specified folder

**Returns:** List of uri of created messages

```cpp
AppendMessages(System::String folderUri, const System::ArrayPtr< System::SharedPtr < MailMessage >> & messages)
```

| Parameter | Description |
| --- | --- |
| folderUri | A folder URI to which message is uploaded. |
| messages | A messages to upload |

---

## AppendMessages (4 of 5) {#appendmessages_4}

Uploads the mail messages to the specified folder

**Returns:** List of uri of created messages

```cpp
AppendMessages(System::String folderUri, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages)
```

| Parameter | Description |
| --- | --- |
| folderUri | A folder URI to which message is uploaded. |
| messages | A messages to upload |

---

## AppendMessages (5 of 5) {#appendmessages_5}

Uploads the mapi messages to the specified folder

**Returns:** List of uri of created messages

```cpp
AppendMessages(System::String folderUri, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < Mapi::MapiMessage >>> messages)
```

| Parameter | Description |
| --- | --- |
| folderUri | A folder URI to which message is uploaded. |
| messages | A messages to upload |

