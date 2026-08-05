---
title: "Aspose::Email::Clients::Imap::ImapClient::AppendMessage method"
linktitle: "AppendMessage"
articleTitle: "AppendMessage"
second_title: "Aspose.Email for C++"
description: "Uploads the mail message to the current folder If current folder hasn't been specified default folder is used."
type: docs
weight: 20
url: /cpp/aspose.email.clients.imap/imapclient/appendmessage/
---

## AppendMessage (1 of 8) {#appendmessage_1}

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

**Returns:** An unique id of appended message

```cpp
AppendMessage(System::SharedPtr < IConnection > connection, System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| message | Mail message to be upload |

---

## AppendMessage (2 of 8) {#appendmessage_2}

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

**Returns:** An unique id of appended message

```cpp
AppendMessage(System::SharedPtr < IConnection > connection, System::String fileName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| fileName | File name (*.eml) of the mail message that will be uploaded |

---

## AppendMessage (3 of 8) {#appendmessage_3}

Uploads the mail message to the specified folder

**Returns:** An unique id of appended message

```cpp
AppendMessage(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder that will receive the mail message |
| message | Mail message to be upload |

---

## AppendMessage (4 of 8) {#appendmessage_4}

Uploads the mail message to the specified folder

**Returns:** An unique id of appended message

```cpp
AppendMessage(System::SharedPtr < IConnection > connection, System::String folderName, System::String fileName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder that will receive the mail message |
| fileName | File name (*.eml) of the mail message that will be uploaded |

---

## AppendMessage (5 of 8) {#appendmessage_5}

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

**Returns:** An unique id of appended message

```cpp
AppendMessage(System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| message | Mail message to be upload |

---

## AppendMessage (6 of 8) {#appendmessage_6}

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

**Returns:** An unique id of appended message

```cpp
AppendMessage(System::String fileName)
```

| Parameter | Description |
| --- | --- |
| fileName | File name (*.eml) of the mail message that will be uploaded |

---

## AppendMessage (7 of 8) {#appendmessage_7}

Uploads the mail message to the specified folder

**Returns:** An unique id of appended message

```cpp
AppendMessage(System::String folderName, System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder that will receive the mail message |
| message | Mail message to be upload |

---

## AppendMessage (8 of 8) {#appendmessage_8}

Uploads the mail message to the specified folder

**Returns:** An unique id of appended message

```cpp
AppendMessage(System::String folderName, System::String fileName)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder that will receive the mail message |
| fileName | File name (*.eml) of the mail message that will be uploaded |

