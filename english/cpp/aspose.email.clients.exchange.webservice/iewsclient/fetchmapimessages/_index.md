---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::FetchMapiMessages method"
linktitle: "FetchMapiMessages"
articleTitle: "FetchMapiMessages"
second_title: "Aspose.Email for C++"
description: "Fetches the speciifed messages"
type: docs
weight: 430
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/fetchmapimessages/
---

## FetchMapiMessages (1 of 2) {#fetchmapimessages_1}

Fetches the speciifed messages

**Returns:** virtual System::ArrayPtr< System::SharedPtr < Mapi::MapiMessage > > Aspose::Email::Clients::Exchange::WebService::

```cpp
FetchMapiMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uris)
```

| Parameter | Description |
| --- | --- |
| uris | A IEnumerable<string> "/> containing message uris to be retrieved</param> <returns>An array of <see cref="MapiMessage">containing fetched messages |

---

## FetchMapiMessages (2 of 2) {#fetchmapimessages_2}

Fetches the speciifed messages

**Returns:** An array of MapiMessage containing fetched messages

```cpp
FetchMapiMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uris, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < Mapi::PropertyDescriptor >>> extendedProperties)
```

| Parameter | Description |
| --- | --- |
| uris | A StringCollection containing message uris to be retrieved |
| extendedProperties | An enumeration of extended properties |

