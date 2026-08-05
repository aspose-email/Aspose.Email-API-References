---
title: "Aspose::Email::Clients::Imap::ImapClient::BeginSortMessageThreads method"
linktitle: "BeginSortMessageThreads"
articleTitle: "BeginSortMessageThreads"
second_title: "Aspose.Email for C++"
description: "Begins sorting message threads asynchronously."
type: docs
weight: 460
url: /cpp/aspose.email.clients.imap/imapclient/beginsortmessagethreads/
---

## BeginSortMessageThreads (1 of 2) {#beginsortmessagethreads_1}

Begins sorting message threads asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSortMessageThreads(System::SharedPtr < IConnection > connection, System::SharedPtr < SortConditions > conditions, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| conditions | Sort conditions. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginSortMessageThreads (2 of 2) {#beginsortmessagethreads_2}

Begins sorting message threads asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSortMessageThreads(System::SharedPtr < SortConditions > conditions, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| conditions | Sort conditions. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

