---
title: "Aspose::Email::Clients::Imap::ImapClient::BeginAppendMessages method"
linktitle: "BeginAppendMessages"
articleTitle: "BeginAppendMessages"
second_title: "Aspose.Email for C++"
description: "Begins append message to the end of the specified folder If current folder hasn't been specified default folder is used."
type: docs
weight: 70
url: /cpp/aspose.email.clients.imap/imapclient/beginappendmessages/
---

## BeginAppendMessages (1 of 16) {#beginappendmessages_1}

Begins append message to the end of the specified folder If current folder hasn't been specified default folder is used.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| messages | Enumeration of email messages to be upload |

---

## BeginAppendMessages (2 of 16) {#beginappendmessages_2}

Begins append message to the end of the current folder If current folder hasn't been specified default folder is used.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> fileNames)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| fileNames | File names (*.eml) of an email messages that will be uploaded |

---

## BeginAppendMessages (3 of 16) {#beginappendmessages_3}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessages(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder that will receive the mail message |
| messages | Enumeration of email messages to be upload |

---

## BeginAppendMessages (4 of 16) {#beginappendmessages_4}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessages(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder that will receive the mail message |
| messages | Enumeration of email messages to be upload |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAppendMessages (5 of 16) {#beginappendmessages_5}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessages(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder that will receive the mail message |
| messages | Enumeration of email messages to be upload |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAppendMessages (6 of 16) {#beginappendmessages_6}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessages(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> fileNames)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder that will receive the mail message |
| fileNames | File names (*.eml) of an email messages that will be uploaded |

---

## BeginAppendMessages (7 of 16) {#beginappendmessages_7}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessages(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> fileNames, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder that will receive the mail message |
| fileNames | File names (*.eml) of an email messages that will be uploaded |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAppendMessages (8 of 16) {#beginappendmessages_8}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessages(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> fileNames, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder that will receive the mail message |
| fileNames | File names (*.eml) of an email messages that will be uploaded |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAppendMessages (9 of 16) {#beginappendmessages_9}

Begins append message to the end of the specified folder If current folder hasn't been specified default folder is used.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages)
```

| Parameter | Description |
| --- | --- |
| messages | Enumeration of email messages to be upload |

---

## BeginAppendMessages (10 of 16) {#beginappendmessages_10}

Begins append message to the end of the current folder If current folder hasn't been specified default folder is used.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> fileNames)
```

| Parameter | Description |
| --- | --- |
| fileNames | File names (*.eml) of an email messages that will be uploaded |

---

## BeginAppendMessages (11 of 16) {#beginappendmessages_11}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessages(System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder that will receive the mail message |
| messages | Enumeration of email messages to be upload |

---

## BeginAppendMessages (12 of 16) {#beginappendmessages_12}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessages(System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder that will receive the mail message |
| messages | Enumeration of email messages to be upload |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAppendMessages (13 of 16) {#beginappendmessages_13}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessages(System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < MailMessage >>> messages, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder that will receive the mail message |
| messages | Enumeration of email messages to be upload |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginAppendMessages (14 of 16) {#beginappendmessages_14}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessages(System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> fileNames)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder that will receive the mail message |
| fileNames | File names (*.eml) of an email messages that will be uploaded |

---

## BeginAppendMessages (15 of 16) {#beginappendmessages_15}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessages(System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> fileNames, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder that will receive the mail message |
| fileNames | File names (*.eml) of an email messages that will be uploaded |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginAppendMessages (16 of 16) {#beginappendmessages_16}

Begins append message to the end of the specified folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginAppendMessages(System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> fileNames, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder that will receive the mail message |
| fileNames | File names (*.eml) of an email messages that will be uploaded |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

