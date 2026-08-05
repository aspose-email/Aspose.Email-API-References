---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::ListMessages method"
linktitle: "ListMessages"
articleTitle: "ListMessages"
second_title: "Aspose.Email for C++"
description: "List the messages in the inbox folder."
type: docs
weight: 1010
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/listmessages/
---

## ListMessages (1 of 14) {#listmessages_1}

List the messages in the inbox folder.

**Returns:** ExchangeMessageInfoCollection from inbox folder.

```cpp
ListMessages()
```

---

## ListMessages (2 of 14) {#listmessages_2}

List the messages in the specified folder.

**Returns:** ExchangeMessageInfoCollection that contains messages with.

```cpp
ListMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> iDs)
```

| Parameter | Description |
| --- | --- |
| iDs | Enumeration of message ids |

---

## ListMessages (3 of 14) {#listmessages_3}

Lists the messages.

**Returns:** A ExchangeMessageInfoCollection

```cpp
ListMessages(System::String folder)
```

| Parameter | Description |
| --- | --- |
| folder | The folder. |

---

## ListMessages (4 of 14) {#listmessages_4}

List the messages in the specified folder

**Returns:** ExchangeMessageInfoCollection that contains messages from the specified folder

```cpp
ListMessages(System::String folder, bool recursive)
```

| Parameter | Description |
| --- | --- |
| folder | A folder to search messages in |
| recursive | Indicates whether recursive listing or not |

---

## ListMessages (5 of 14) {#listmessages_5}

Lists the messages.

**Returns:** A ExchangeMessageInfoCollection

```cpp
ListMessages(System::String folder, ExchangeListMessagesOptions options)
```

| Parameter | Description |
| --- | --- |
| folder | The folder. |
| options | Specifies the settings of listing |

---

## ListMessages (6 of 14) {#listmessages_6}

List the messages in the specified folder

**Returns:** ExchangeMessageInfoCollection that contains messages from the specified folder

```cpp
ListMessages(System::String folder, ExchangeListMessagesOptions options, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < Mapi::PropertyDescriptor >>> extendedProperties)
```

| Parameter | Description |
| --- | --- |
| folder | A folder to search messages in |
| options | Specifies the settings of listing |
| extendedProperties | Extended properties of retrieved messages |

---

## ListMessages (7 of 14) {#listmessages_7}

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

## ListMessages (8 of 14) {#listmessages_8}

Lists the messages.

**Returns:** A ExchangeMessageInfoCollection

```cpp
ListMessages(System::String folder, int32_t maxNumberOfMessages, ExchangeListMessagesOptions options)
```

| Parameter | Description |
| --- | --- |
| folder | The folder. |
| maxNumberOfMessages | Maximum number of messages |
| options | Specifies the settings of listing |

---

## ListMessages (9 of 14) {#listmessages_9}

Lists the messages.

**Returns:** A ExchangeMessageInfoCollection

```cpp
ListMessages(System::String folder, int32_t maxNumberOfMessages, System::SharedPtr < Tools::Search::MailQuery > query)
```

| Parameter | Description |
| --- | --- |
| folder | The folder. |
| extendedProperties | Extended properties of retrieved messages |

---

## ListMessages (10 of 14) {#listmessages_10}

List the messages in the specified folder.

**Returns:** ExchangeMessageInfoCollection that contains messages from the specified folder.

```cpp
ListMessages(System::String folder, int32_t maxNumberOfMessages, System::SharedPtr < Tools::Search::MailQuery > query, bool recursive)
```

| Parameter | Description |
| --- | --- |
| folder | A folder to search messages in. |
| maxNumberOfMessages | Maximum number of messages. |
| query | MailQuery that represents message search criteria. |
| recursive | Indicates whether recursive listing or not. |

---

## ListMessages (11 of 14) {#listmessages_11}

List the messages in the specified folder.

**Returns:** ExchangeMessageInfoCollection that contains messages from the specified folder.

```cpp
ListMessages(System::String folder, System::SharedPtr < Tools::Search::MailQuery > query)
```

| Parameter | Description |
| --- | --- |
| folder | A folder to search messages in. |
| query | MailQuery that represents message search criteria. |
| extendedProperties | Extended properties of retrieved messages |

---

## ListMessages (12 of 14) {#listmessages_12}

List the messages in the specified folder.

**Returns:** ExchangeMessageInfoCollection that contains messages from the specified folder.

```cpp
ListMessages(System::String folder, System::SharedPtr < Tools::Search::MailQuery > query, bool recursive)
```

| Parameter | Description |
| --- | --- |
| folder | A folder to search messages in. |
| query | MailQuery that represents message search criteria. |
| recursive | Indicates whether recursive listing or not. |

---

## ListMessages (13 of 14) {#listmessages_13}

List the messages in the specified folder

**Returns:** ExchangeMessageInfoCollection that contains messages from the specified folder

```cpp
ListMessages(System::String mailbox, System::String folder, bool recursive)
```

| Parameter | Description |
| --- | --- |
| mailbox | The mailbox that is used to initialize the folder id class. |
| folder | A folder to search messages in |
| recursive | Indicates whether recursive listing or not |

---

## ListMessages (14 of 14) {#listmessages_14}

List the messages in the specified folder.

**Returns:** ExchangeMessageInfoCollection that contains messages from the specified folder.

```cpp
ListMessages(System::String mailbox, System::String folder, System::SharedPtr < Tools::Search::MailQuery > query)
```

| Parameter | Description |
| --- | --- |
| mailbox | The mailbox that is used to initialize the folder id class. |
| folder | A folder to search messages in. |
| query | MailQuery that represents message search criteria. |

