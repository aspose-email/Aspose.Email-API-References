---
title: "Aspose::Email::Clients::Imap::ImapClient::AppendMessages method"
linktitle: "AppendMessages"
articleTitle: "AppendMessages"
second_title: "Aspose.Email for C++"
description: "Uploads the mail message to the current folder If current folder hasn't been specified default folder is used."
type: docs
weight: 30
url: /cpp/aspose.email.clients.imap/imapclient/appendmessages/
---

## AppendMessages (1 of 4) {#appendmessages_1}

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

**Returns:** An unique id of appended message

```cpp
AppendMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messages | Enumeration of email messages to be upload |

---

## AppendMessages (2 of 4) {#appendmessages_2}

Uploads the mail message to the specified folder

**Returns:** An unique id of appended message

```cpp
AppendMessages(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder that will receive the mail message |
| messages | Enumeration of email messages to be upload |

---

## AppendMessages (3 of 4) {#appendmessages_3}

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

**Returns:** An unique id of appended message

```cpp
AppendMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages)
```

| Parameter | Description |
| --- | --- |
| messages | Enumeration of email messages to be upload |

---

## AppendMessages (4 of 4) {#appendmessages_4}

Uploads the mail message to the specified folder

**Returns:** An unique id of appended message

```cpp
AppendMessages(System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder that will receive the mail message |
| messages | Enumeration of email messages to be upload |

