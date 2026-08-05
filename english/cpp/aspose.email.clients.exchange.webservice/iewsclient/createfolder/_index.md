---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::CreateFolder method"
linktitle: "CreateFolder"
articleTitle: "CreateFolder"
second_title: "Aspose.Email for C++"
description: "Fetch the specified appointment from server."
type: docs
weight: 160
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/createfolder/
---

## CreateFolder (1 of 6) {#createfolder_1}

Fetch the specified appointment from server.

**Returns:** A fetched Appointment .

```cpp
CreateFolder(System::String name)
```

| Parameter | Description |
| --- | --- |
| appointmentUri | An uri of appointment to be fetched. |

---

## CreateFolder (2 of 6) {#createfolder_2}

Creates new folder in the root folder.

**Returns:** Returns folder information

```cpp
CreateFolder(System::String name, ExchangeFolderType folderType)
```

| Parameter | Description |
| --- | --- |
| name | The name of new folder |
| folderType | Type of folder |

---

## CreateFolder (3 of 6) {#createfolder_3}

Creates the new folder with the specified name in the specified parent folder.

**Returns:** virtual System::SharedPtr < ExchangeFolderInfo > Aspose::Email::Clients::Exchange::WebService::

```cpp
CreateFolder(System::String parentFolderUri, System::String name)
```

| Parameter | Description |
| --- | --- |
| parentFolderUri | An uri of parent folder. |
| name | A name of folder to be created. |

---

## CreateFolder (4 of 6) {#createfolder_4}

Creates the new folder

**Returns:** Returns folder information

```cpp
CreateFolder(System::String parentFolderUri, System::String name, ExchangeFolderType folderType)
```

| Parameter | Description |
| --- | --- |
| parentFolderUri | The URI of parent folder |
| name | The name of new folder |
| folderType | Type of folder |

---

## CreateFolder (5 of 6) {#createfolder_5}

Creates the new folder

**Returns:** Returns folder information

```cpp
CreateFolder(System::String parentFolderUri, System::String name, System::SharedPtr < ExchangeFolderPermissionCollection > permissions)
```

| Parameter | Description |
| --- | --- |
| parentFolderUri | The URI of parent folder |
| name | The name of new folder |
| permissions | A permission on new folder |

---

## CreateFolder (6 of 6) {#createfolder_6}

Creates the new folder

**Returns:** Returns folder information

```cpp
CreateFolder(System::String parentFolderUri, System::String name, System::SharedPtr < ExchangeFolderPermissionCollection > permissions, System::String folderClass)
```

| Parameter | Description |
| --- | --- |
| parentFolderUri | The URI of parent folder |
| name | The name of new folder |
| permissions | A permission on new folder |
| folderClass | The class of new folder |

