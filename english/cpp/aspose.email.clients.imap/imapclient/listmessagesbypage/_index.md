---
title: "Aspose::Email::Clients::Imap::ImapClient::ListMessagesByPage method"
linktitle: "ListMessagesByPage"
articleTitle: "ListMessagesByPage"
second_title: "Aspose.Email for C++"
description: "Gets the list of messages"
type: docs
weight: 1600
url: /cpp/aspose.email.clients.imap/imapclient/listmessagesbypage/
---

## ListMessagesByPage (1 of 4) {#listmessagesbypage_1}

Gets the list of messages

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
ListMessagesByPage(int32_t itemsPerPage, int32_t pageOffset, System::SharedPtr < PageSettings > settings)
```

| Parameter | Description |
| --- | --- |
| itemsPerPage | A number of items in page |
| pageOffset | An offset of next page in view |
| settings | The settings. |

---

## ListMessagesByPage (2 of 4) {#listmessagesbypage_2}

Gets the list of messages

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
ListMessagesByPage(int32_t itemsPerPage, System::SharedPtr < PageSettings > settings)
```

| Parameter | Description |
| --- | --- |
| itemsPerPage | A number of items in page |
| settings | The settings. |

---

## ListMessagesByPage (3 of 4) {#listmessagesbypage_3}

Gets the list of messages

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
ListMessagesByPage(System::SharedPtr < PageInfo > pageInfo, System::SharedPtr < PageSettings > settings)
```

| Parameter | Description |
| --- | --- |
| pageInfo | The next page to retrieve. |
| settings | The settings. |

---

## ListMessagesByPage (4 of 4) {#listmessagesbypage_4}

Gets the list of messages

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
ListMessagesByPage(System::SharedPtr < Tools::Search::MailQuery > query, System::SharedPtr < PageInfo > pageInfo, System::SharedPtr < PageSettings > settings)
```

| Parameter | Description |
| --- | --- |
| query | MailQuery that represents search query. |
| pageInfo | The next page to retrieve. |
| settings | The settings. |

