---
title: "Aspose::Email::Clients::Imap::ImapClient::BeginListMessagesByPage method"
linktitle: "BeginListMessagesByPage"
articleTitle: "BeginListMessagesByPage"
second_title: "Aspose.Email for C++"
description: "Begins getting the list of messages asynchronously"
type: docs
weight: 320
url: /cpp/aspose.email.clients.imap/imapclient/beginlistmessagesbypage/
---

## BeginListMessagesByPage (1 of 2) {#beginlistmessagesbypage_1}

Begins getting the list of messages asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessagesByPage(int32_t itemsPerPage, int32_t pageOffset, System::SharedPtr < PageSettingsAsync > settings)
```

| Parameter | Description |
| --- | --- |
| itemsPerPage | A number of items in page |
| pageOffset | An offset of next page in view |
| settings | The settings. |

---

## BeginListMessagesByPage (2 of 2) {#beginlistmessagesbypage_2}

Begins getting the list of messages asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessagesByPage(System::SharedPtr < Tools::Search::MailQuery > query, System::SharedPtr < PageInfo > pageInfo, System::SharedPtr < PageSettingsAsync > settings)
```

| Parameter | Description |
| --- | --- |
| query | MailQuery that represents search query. |
| pageInfo | The next page to retrieve. |
| settings | The settings. |

