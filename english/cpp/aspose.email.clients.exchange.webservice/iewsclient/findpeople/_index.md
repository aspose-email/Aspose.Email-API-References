---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::FindPeople method"
linktitle: "FindPeople"
articleTitle: "FindPeople"
second_title: "Aspose.Email for C++"
description: "Find contacts located in the specified user's personal mailbox on server."
type: docs
weight: 510
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/findpeople/
---

## FindPeople (1 of 2) {#findpeople_1}

Find contacts located in the specified user's personal mailbox on server.

**Returns:** An array of Contact that represents contact information

```cpp
FindPeople(System::String folderUri, System::SharedPtr < Tools::Search::MailQuery > query, int32_t maxNumberOfItems)
```

| Parameter | Description |
| --- | --- |
| folderUri | The URI of folder. |
| query | MailQuery that represents contact search criteria. |
| maxNumberOfItems | Maximum number of items. |

---

## FindPeople (2 of 2) {#findpeople_2}

Find contacts located in the global address list (GAL) on server.

**Returns:** An array of Contact that represents contact information

```cpp
FindPeople(System::String queryString, int32_t maxNumberOfItems)
```

| Parameter | Description |
| --- | --- |
| queryString | Represents contact search criteria. |
| maxNumberOfItems | Maximum number of items. |

