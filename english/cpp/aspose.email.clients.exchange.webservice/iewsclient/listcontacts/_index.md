---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::ListContacts method"
linktitle: "ListContacts"
articleTitle: "ListContacts"
second_title: "Aspose.Email for C++"
description: "Lists contacts located in the specified folder on server"
type: docs
weight: 960
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/listcontacts/
---

## ListContacts (1 of 2) {#listcontacts_1}

Lists contacts located in the specified folder on server

**Returns:** An array of read MapiContact that represents contact information

```cpp
ListContacts(System::String folderUri)
```

| Parameter | Description |
| --- | --- |
| folderUri | The URI of folder |

---

## ListContacts (2 of 2) {#listcontacts_2}

Lists contacts located in the specified folder on server

**Returns:** An array of read MapiContact that represents contact information

```cpp
ListContacts(System::String folderUri, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < Mapi::PropertyDescriptor >>> mapiProperties)
```

| Parameter | Description |
| --- | --- |
| folderUri | A folder to search contacts in |
| mapiProperties | Required additional mapi properties |

