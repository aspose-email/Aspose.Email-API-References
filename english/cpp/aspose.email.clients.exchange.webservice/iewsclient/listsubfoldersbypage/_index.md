---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::ListSubFoldersByPage method"
linktitle: "ListSubFoldersByPage"
articleTitle: "ListSubFoldersByPage"
second_title: "Aspose.Email for C++"
description: "Searches the specified folder in the given parent folder with paging Method supports paging."
type: docs
weight: 1060
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage/
---

## ListSubFoldersByPage (1 of 3) {#listsubfoldersbypage_1}

Searches the specified folder in the given parent folder with paging Method supports paging. Invokes for the first time in paging cycle.

**Returns:** A ExchangeFolderPageInfo containing the found folder if folder name is specified; otherwise, returns all subfolders

```cpp
ListSubFoldersByPage(System::String parentFolderUri, int32_t itemsPerPage)
```

| Parameter | Description |
| --- | --- |
| parentFolderUri | A parent folder URI |
| itemsPerPage | A number of folders in page |

---

## ListSubFoldersByPage (2 of 3) {#listsubfoldersbypage_2}

Searches the specified folder in the given parent folder with paging Method supports paging.

**Returns:** A ExchangeFolderPageInfo containing the found folder if folder name is specified; otherwise, returns all subfolders

```cpp
ListSubFoldersByPage(System::String parentFolderUri, int32_t itemsPerPage, int32_t pageOffset)
```

| Parameter | Description |
| --- | --- |
| parentFolderUri | A parent folder URI |
| itemsPerPage | A number of folders in page |
| pageOffset | An offset of next item in view |

---

## ListSubFoldersByPage (3 of 3) {#listsubfoldersbypage_3}

Searches the specified folder in the given parent folder with paging Method supports paging.

**Returns:** A ExchangeFolderPageInfo containing the found folder if folder name is specified; otherwise, returns all subfolders

```cpp
ListSubFoldersByPage(System::String parentFolderUri, System::SharedPtr < PageInfo > page)
```

| Parameter | Description |
| --- | --- |
| parentFolderUri | A parent folder URI |
| page | A page info |

