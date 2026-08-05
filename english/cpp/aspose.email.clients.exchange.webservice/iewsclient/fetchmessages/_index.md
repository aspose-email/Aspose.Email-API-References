---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::FetchMessages method"
linktitle: "FetchMessages"
articleTitle: "FetchMessages"
second_title: "Aspose.Email for C++"
description: "Fetches the speciifed messages"
type: docs
weight: 470
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/fetchmessages/
---

## FetchMessages (1 of 4) {#fetchmessages_1}

Fetches the speciifed messages

**Returns:** A MailMessageCollection containing fetched messages

```cpp
FetchMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < ExchangeMessageInfo >>> messageInfos)
```

| Parameter | Description |
| --- | --- |
| messageInfos | A IEnumerable<ExchangeMessageInfo> "/> of messages to be retrieved |

---

## FetchMessages (2 of 4) {#fetchmessages_2}

Fetches the speciifed messages

**Returns:** A MailMessageCollection containing fetched messages

```cpp
FetchMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uris)
```

| Parameter | Description |
| --- | --- |
| uris | A StringCollection containing message uris to be retrieved |

---

## FetchMessages (3 of 4) {#fetchmessages_3}

Fetches the speciifed messages

**Returns:** A MailMessageCollection containing fetched messages

```cpp
FetchMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uris, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < Mapi::PropertyDescriptor >>> extendedProperties)
```

| Parameter | Description |
| --- | --- |
| uris | A StringCollection containing message uris to be retrieved |
| extendedProperties | An enumeration of extended properties |

---

## FetchMessages (4 of 4) {#fetchmessages_4}

Fetches the speciifed messages

**Returns:** A MailMessageCollection containing fetched messages

```cpp
FetchMessages(System::SharedPtr < System::Collections::Specialized::StringCollection > messageUris)
```

| Parameter | Description |
| --- | --- |
| messageUris | A StringCollection containing message uris to be retrieved |

