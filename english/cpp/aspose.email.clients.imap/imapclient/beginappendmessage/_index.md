---
title: "Aspose::Email::Clients::Imap::ImapClient::BeginAppendMessage method"
linktitle: "BeginAppendMessage"
articleTitle: "BeginAppendMessage"
second_title: "Aspose.Email for C++"
description: "Begins append message to the end of the specified folder If current folder hasn't been specified default folder is used."
type: docs
weight: 60
url: /cpp/aspose.email.clients.imap/imapclient/beginappendmessage/
---

## BeginAppendMessage (1 of 16) {#beginappendmessage_1}

Begins append message to the end of the specified folder If current folder hasn't been specified default folder is used.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessage(System::SharedPtr < IConnection > connection, System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| message | Mail message to be upload |

---

## BeginAppendMessage (2 of 16) {#beginappendmessage_2}

Begins append message to the end of the current folder If current folder hasn't been specified default folder is used.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessage(System::SharedPtr < IConnection > connection, System::String fileName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| fileName | File name (*.eml) of the mail message that will be uploaded |

---

## BeginAppendMessage (3 of 16) {#beginappendmessage_3}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessage(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder that will receive the mail message |
| message | Mail message to be upload |

---

## BeginAppendMessage (4 of 16) {#beginappendmessage_4}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessage(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < MailMessage > message, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder that will receive the mail message |
| message | Mail message to be upload |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAppendMessage (5 of 16) {#beginappendmessage_5}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessage(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < MailMessage > message, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder that will receive the mail message |
| message | Mail message to be upload |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAppendMessage (6 of 16) {#beginappendmessage_6}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessage(System::SharedPtr < IConnection > connection, System::String folderName, System::String fileName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder that will receive the mail message |
| fileName | File name (*.eml) of the mail message that will be uploaded |

---

## BeginAppendMessage (7 of 16) {#beginappendmessage_7}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessage(System::SharedPtr < IConnection > connection, System::String folderName, System::String fileName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder that will receive the mail message |
| fileName | File name (*.eml) of the mail message that will be uploaded |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAppendMessage (8 of 16) {#beginappendmessage_8}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessage(System::SharedPtr < IConnection > connection, System::String folderName, System::String fileName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder that will receive the mail message |
| fileName | File name (*.eml) of the mail message that will be uploaded |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAppendMessage (9 of 16) {#beginappendmessage_9}

Begins append message to the end of the specified folder If current folder hasn't been specified default folder is used.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessage(System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| message | Mail message to be upload |

---

## BeginAppendMessage (10 of 16) {#beginappendmessage_10}

Begins append message to the end of the current folder If current folder hasn't been specified default folder is used.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessage(System::String fileName)
```

| Parameter | Description |
| --- | --- |
| fileName | File name (*.eml) of the mail message that will be uploaded |

---

## BeginAppendMessage (11 of 16) {#beginappendmessage_11}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessage(System::String folderName, System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder that will receive the mail message |
| message | Mail message to be upload |

---

## BeginAppendMessage (12 of 16) {#beginappendmessage_12}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessage(System::String folderName, System::SharedPtr < MailMessage > message, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder that will receive the mail message |
| message | Mail message to be upload |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAppendMessage (13 of 16) {#beginappendmessage_13}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessage(System::String folderName, System::SharedPtr < MailMessage > message, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder that will receive the mail message |
| message | Mail message to be upload |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAppendMessage (14 of 16) {#beginappendmessage_14}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessage(System::String folderName, System::String fileName)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder that will receive the mail message |
| fileName | File name (*.eml) of the mail message that will be uploaded |

---

## BeginAppendMessage (15 of 16) {#beginappendmessage_15}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessage(System::String folderName, System::String fileName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder that will receive the mail message |
| fileName | File name (*.eml) of the mail message that will be uploaded |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAppendMessage (16 of 16) {#beginappendmessage_16}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessage(System::String folderName, System::String fileName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder that will receive the mail message |
| fileName | File name (*.eml) of the mail message that will be uploaded |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

