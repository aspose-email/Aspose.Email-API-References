---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::FetchMessage method"
linktitle: "FetchMessage"
articleTitle: "FetchMessage"
second_title: "Aspose.Email for C++"
description: "Fetches the message."
type: docs
weight: 460
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/fetchmessage/
---

## FetchMessage (1 of 2) {#fetchmessage_1}

Fetches the message.

**Returns:** Returns a message

```cpp
FetchMessage(System::String messageUri)
```

| Parameter | Description |
| --- | --- |
| messageUri | The message URI. |

---

## FetchMessage (2 of 2) {#fetchmessage_2}

Fetches the message from server

**Returns:** MailMessage that represents e-mail message, if custom properties have been found and set you can access them using MailMessage::Headers collection.

```cpp
FetchMessage(System::String messageUri, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < Mapi::PropertyDescriptor >>> extendedProperties)
```

| Parameter | Description |
| --- | --- |
| messageUri | The URI of the message |
| extendedProperties | An enumeration of extended properties |

