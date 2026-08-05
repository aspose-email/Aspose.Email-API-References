---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::CreateItem method"
linktitle: "CreateItem"
articleTitle: "CreateItem"
second_title: "Aspose.Email for C++"
description: "Creates the given item in the default item folder."
type: docs
weight: 180
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/createitem/
---

## CreateItem (1 of 2) {#createitem_1}

Creates the given item in the default item folder.

**Returns:** The item Uri

```cpp
CreateItem(System::SharedPtr < Mapi::MapiMessageItemBase > item)
```

| Parameter | Description |
| --- | --- |
| item | An item to create. |

---

## CreateItem (2 of 2) {#createitem_2}

Creates the given item in the specified folder.

**Returns:** The item Uri

```cpp
CreateItem(System::String folderUri, System::SharedPtr < Mapi::MapiMessageItemBase > item)
```

| Parameter | Description |
| --- | --- |
| folderUri | A folder Uri where item should be created. |
| item | An item to create. |

