---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::ListMessagesByPage method"
linktitle: "ListMessagesByPage"
articleTitle: "ListMessagesByPage"
second_title: "Aspose.Email for C++"
description: "List the messages in the specified folder."
type: docs
weight: 1020
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage/
---

## ListMessagesByPage (1 of 7) {#listmessagesbypage_1}

List the messages in the specified folder.

**Returns:** ExchangeMessageInfoCollection that contains messages from the specified folder.

```cpp
ListMessagesByPage(System::String folder, int32_t itemsPerPage)
```

| Parameter | Description |
| --- | --- |
| folder | A folder to search messages in. |
| itemsPerPage | A number of items in page |

---

## ListMessagesByPage (2 of 7) {#listmessagesbypage_2}

List the messages in the specified folder.

**Returns:** ExchangeMessageInfoCollection that contains messages from the specified folder.

```cpp
ListMessagesByPage(System::String folder, int32_t itemsPerPage, int32_t offset)
```

| Parameter | Description |
| --- | --- |
| folder | A folder to search messages in. |
| itemsPerPage | A number of items in page |
| offset | An offset of next page in view |

---

## ListMessagesByPage (3 of 7) {#listmessagesbypage_3}

List the messages in the specified folder.

**Returns:** ExchangeMessageInfoCollection that contains messages from the specified folder.

```cpp
ListMessagesByPage(System::String folder, int32_t itemsPerPage, int32_t pageOffset, ExchangeListMessagesOptions options)
```

| Parameter | Description |
| --- | --- |
| folder | A folder to search messages in. |
| itemsPerPage | A number of items in page |
| pageOffset | An offset of next item in view |
| options | Specifies the settings of listing |

---

## ListMessagesByPage (4 of 7) {#listmessagesbypage_4}

List the messages in the specified folder.

**Returns:** ExchangeMessageInfoCollection that contains messages from the specified folder.

```cpp
ListMessagesByPage(System::String folder, System::SharedPtr < PageInfo > pageInfo)
```

| Parameter | Description |
| --- | --- |
| folder | A folder to search messages in. |
| pageInfo | A page info |

---

## ListMessagesByPage (5 of 7) {#listmessagesbypage_5}

List the messages in the specified folder.

**Returns:** ExchangeMessageInfoCollection that contains messages from the specified folder.

```cpp
ListMessagesByPage(System::String folder, System::SharedPtr < PageInfo > pageInfo, ExchangeListMessagesOptions options)
```

| Parameter | Description |
| --- | --- |
| folder | A folder to search messages in. |
| pageInfo | A page info |
| options | Specifies the settings of listing |

---

## ListMessagesByPage (6 of 7) {#listmessagesbypage_6}

List the messages in the specified folder.

**Returns:** ExchangeMessageInfoCollection that contains messages from the specified folder.

```cpp
ListMessagesByPage(System::String folder, System::SharedPtr < Tools::Search::MailQuery > query, int32_t itemsPerPage)
```

| Parameter | Description |
| --- | --- |
| folder | A folder to search messages in. |
| query | MailQuery that represents search criteria. |
| itemsPerPage | A number of items in page |

---

## ListMessagesByPage (7 of 7) {#listmessagesbypage_7}

List the messages in the specified folder.

**Returns:** ExchangeMessageInfoCollection that contains messages from the specified folder.

```cpp
ListMessagesByPage(System::String folder, System::SharedPtr < Tools::Search::MailQuery > query, int32_t itemsPerPage, int32_t offset)
```

| Parameter | Description |
| --- | --- |
| folder | A folder to search messages in. |
| query | MailQuery that represents search criteria. |
| itemsPerPage | A number of items in page |
| offset | An offset of next page in view |

