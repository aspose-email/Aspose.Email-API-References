---
title: "Aspose::Email::Clients::Imap::ImapClient::BeginGetMessageThreads method"
linktitle: "BeginGetMessageThreads"
articleTitle: "BeginGetMessageThreads"
second_title: "Aspose.Email for C++"
description: "Begins getting message threads asynchronously."
type: docs
weight: 230
url: /cpp/aspose.email.clients.imap/imapclient/begingetmessagethreads/
---

## BeginGetMessageThreads (1 of 2) {#begingetmessagethreads_1}

Begins getting message threads asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginGetMessageThreads(System::SharedPtr < BaseSearchConditions > conditions, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| conditions | Thread conditions. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginGetMessageThreads (2 of 2) {#begingetmessagethreads_2}

Begins getting message threads asynchronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginGetMessageThreads(System::SharedPtr < IConnection > connection, System::SharedPtr < BaseSearchConditions > conditions, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| conditions | Thread conditions. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

