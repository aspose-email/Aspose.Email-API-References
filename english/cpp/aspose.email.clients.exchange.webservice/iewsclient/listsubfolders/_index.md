---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::ListSubFolders method"
linktitle: "ListSubFolders"
articleTitle: "ListSubFolders"
second_title: "Aspose.Email for C++"
description: "Gets collection of child public folders from parent"
type: docs
weight: 1050
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/listsubfolders/
---

## ListSubFolders (1 of 3) {#listsubfolders_1}

Gets collection of child public folders from parent

**Returns:** ExchangeFolderInfoCollection that contains subfolders from the parent folder

```cpp
ListSubFolders(System::SharedPtr < ExchangeFolderInfo > parentFolder)
```

| Parameter | Description |
| --- | --- |
| parentFolder | The parent ExchangeFolderInfo |

---

## ListSubFolders (2 of 3) {#listsubfolders_2}

Gets collection of child folders from parent

**Returns:** ExchangeFolderInfoCollection that contains subfolders from the parent folder

```cpp
ListSubFolders(System::String mailbox, System::String parentFolderUri)
```

| Parameter | Description |
| --- | --- |
| mailbox | The mailbox that is used to initialize the folder id class. |
| parentFolderUri | A parent folder |

---

## ListSubFolders (3 of 3) {#listsubfolders_3}

Gets collection of child folders from parent

**Returns:** ExchangeFolderInfoCollection that contains subfolders from the parent folder

```cpp
ListSubFolders(System::String parentFolderUri)
```

| Parameter | Description |
| --- | --- |
| parentFolderUri | The uri of the parent folder |

