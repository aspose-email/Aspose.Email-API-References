---
title: "Aspose::Email::Clients::Exchange::Dav::ExchangeClient::ListMessages method"
linktitle: "ListMessages"
articleTitle: "ListMessages"
second_title: "Aspose.Email for C++"
description: "Lists the messages."
type: docs
weight: 310
url: /cpp/aspose.email.clients.exchange.dav/exchangeclient/listmessages/
---

## ListMessages (1 of 8) {#listmessages_1}

Lists the messages.

**Returns:** A ExchangeMessageInfoCollection

```cpp
ListMessages(System::String folder)
```

| Parameter | Description |
| --- | --- |
| folder | The folder. |

---

## ListMessages (2 of 8) {#listmessages_2}

List the messages in the specified folder

**Returns:** A collection of message info

```cpp
ListMessages(System::String folder, bool recursive)
```

| Parameter | Description |
| --- | --- |
| folder | The folder Uri |
| recursive | Indicates whether recursive listing or not. |

---

## ListMessages (3 of 8) {#listmessages_3}

Lists the mail message in the specified folder.

**Returns:** A ExchangeMessageInfoCollection collection.

```cpp
ListMessages(System::String folder, ExchangeListMessagesOptions options)
```

| Parameter | Description |
| --- | --- |
| folder | The folder url |
| options | Specifies the settings of listing |

---

## ListMessages (4 of 8) {#listmessages_4}

Lists the messages.

**Returns:** A ExchangeMessageInfoCollection

```cpp
ListMessages(System::String folder, int32_t maxNumberOfMessages)
```

| Parameter | Description |
| --- | --- |
| folder | The folder. |
| maxNumberOfMessages | Maximum number of messages |

---

## ListMessages (5 of 8) {#listmessages_5}

List the messages in the specified folder

**Returns:** A collection of message info

```cpp
ListMessages(System::String folder, int32_t maxNumberOfMessages, ExchangeListMessagesOptions options)
```

| Parameter | Description |
| --- | --- |
| folder | The folder Uri |
| maxNumberOfMessages | Maximum number of messages |
| options | Specifies the settings of listing |

---

## ListMessages (6 of 8) {#listmessages_6}

Lists the messages.

**Returns:** The message info collection.

```cpp
ListMessages(System::String folder, System::SharedPtr < Tools::Search::MailQuery > query, bool recursive)
```

| Parameter | Description |
| --- | --- |
| folder | The Uri of folder that contains messages. |
| query | The MailQuery that represents search criteria. |
| recursive | Indicates whether recursive listing or not. |

---

## ListMessages (7 of 8) {#listmessages_7}

Lists the messages.

**Returns:** System::SharedPtr < ExchangeMessageInfoCollection > Aspose::Email::Clients::Exchange::Dav::

```cpp
ListMessages(System::String folder, System::String messageClass, bool recursive)
```

| Parameter | Description |
| --- | --- |
| folder | The folder. |
| messageClass | The message class. |
| recursive | if set to true [recursive]. |

---

## ListMessages (8 of 8) {#listmessages_8}

Lists the messages.

**Returns:** System::SharedPtr < ExchangeMessageInfoCollection > Aspose::Email::Clients::Exchange::Dav::

```cpp
ListMessages(System::String folder, System::String query)
```

| Parameter | Description |
| --- | --- |
| folder | The folder. |
| query | The query. |

