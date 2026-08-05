---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::FolderExists method"
linktitle: "FolderExists"
articleTitle: "FolderExists"
second_title: "Aspose.Email for C++"
description: "Checks whether the specified folder exists."
type: docs
weight: 520
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/folderexists/
---

## FolderExists (1 of 2) {#folderexists_1}

Checks whether the specified folder exists.

**Returns:** true if the specified folder exists in the specified parent folder; otherwise, false .

```cpp
FolderExists(System::String parentFolderUri, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| parentFolderUri | An uri of parent folder. |
| folderName | A folder name. |

---

## FolderExists (2 of 2) {#folderexists_2}

Checks whether the specified folder exists.

**Returns:** true if the specified folder exists in the specified parent folder; otherwise, false .

```cpp
FolderExists(System::String parentFolderUri, System::String folderName, System::SharedPtr < ExchangeFolderInfo > & folder)
```

| Parameter | Description |
| --- | --- |
| parentFolderUri | An uri of parent folder. |
| folderName | A folder name. |
| folder | A ExchangeFolderInfo that represents the found folder information, if folder exists. |

